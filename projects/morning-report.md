---
layout: default
title: Morning Report
permalink: /projects/morning-report/
description: 매일 자동 발행되는 시장·뉴스 리포트.
---

<header class="page-header">
  <p class="meta">2026 · 자동화 도구</p>
  <h1>Morning Report</h1>
  <p>매일 평일 오전 10시, AI가 뉴스를 검색해 정리하고 GitHub에 자동 발행한다.</p>
</header>

## 라이브 사이트

[jinyeung0618.github.io/morning-report](https://jinyeung0618.github.io/morning-report/) →

## 시작 동기

주식을 처음 시작하면서 *매일 아침 무엇을 봐야 할지* 모르겠다는 게 출발점. 뉴스를 일일이 찾아 읽기엔 시간이 부족하고, 종목 리포트를 사기엔 부담스럽다. 그래서 직접 만들었다.

핵심 원칙:

- **사실 기반** — 검색 결과만 인용, 추측·예측 금지
- **간결함** — 출근길 5분 통독 가능한 길이
- **자동화** — 매일 사람 손 한 번 안 거치고 발행

## 시스템 구성

```
            매일 평일 10:03 KST
                 ↓
            cron 트리거
                 ↓
    ┌──── Claude (Claude Code 세션) ────┐
    │                                  │
    │  WebSearch × 10회                │
    │  (거시 뉴스 + 종목별 뉴스)         │
    │           ↓                      │
    │  마크다운 리포트 작성             │
    │   (Jekyll frontmatter 포함)      │
    │           ↓                      │
    │  ~/Personal/morning-report/      │
    │   _posts/YYYY-MM-DD-...md 저장   │
    │           ↓                      │
    │  git add + commit + push         │
    └──────────────────────────────────┘
                 ↓
       GitHub Pages 자동 빌드
                 ↓
        사이트 업데이트 (1-2분)
```

## 리포트 구조

매일 같은 형식으로 발행:

1. **오늘 한 줄** — 시장 분위기 1-2문장 요약
2. **큰 흐름 3가지** — 거시 뉴스 1-2개 + 산업 흐름 1-2개
3. **Watchlist 6종목** — 분위기(🟢🟡🔴) + 한 줄 요약
4. **오늘 알아야 할 것** — 핵심 변수 1-2개

## 결정 로그

- **출처 URL은 본문에 박지 않음** — 가독성을 위해. 요청 시에만 별도 제공.
- **수치 디테일 최소화** — 매출·EPS·capex 같은 분석가용 숫자는 빼고, 흐름과 방향성만.
- **추측 금지** — "~할 가능성이 높다" 같은 표현 금지. AI가 가장 빠지기 쉬운 함정.
- **평일만 발행** — 토·일은 시장 휴장이라 새 정보 없음. 월요일에 주말 누적 뉴스 정리.
- **6종목 watchlist** — 너무 많으면 리포트가 길어지고 결정 피곤해진다. 6개가 적정선.

## 한계와 다음 단계

**현재 한계**
- Claude Code 세션 의존 (Mac 끄거나 세션 종료 시 cron 사라짐)
- Mac 슬립 중 발사 시각 도래 시 누락
- 페이월 매체(NYT, WSJ) 본문 접근 불가 — 헤드라인·요약만

**다음 단계 후보**
- GitHub Actions로 옮겨서 클라우드 실행 (Mac 의존성 제거)
- 종목별 과거 가격 흐름 시각화 추가
- 모바일 푸시 알림 통합

## 적용된 디자인 시스템

[Design System](/projects/design-system/)을 그대로 적용. 헤더 sticky, 토큰 기반 컬러·타이포·간격, 다크 모드 토글까지 일관됨.
