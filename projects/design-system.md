---
layout: default
title: Design System
permalink: /projects/design-system/
description: Apple HIG + Dieter Rams 기반 토큰화된 디자인 시스템.
---

<header class="page-header">
  <p class="meta">2026 · Design System</p>
  <h1>Design System</h1>
  <p>웹과 앱 어디에서든 적용 가능한, 토큰 기반의 미니멀 디자인 체계.</p>
</header>

## 철학

> "Less, but better." — Dieter Rams

Apple Human Interface Guidelines와 Dieter Rams의 10원칙에서 출발했다. 둘 다 **명확함, 절제, 일관성**을 본질로 두는 점이 좋아서.

핵심 신념 셋:

1. **색은 정보가 아니다** — UI의 90%는 grayscale. Primary는 CTA에만.
2. **여백을 아끼지 마라** — 의심스러우면 늘려라.
3. **한 화면에 강조는 셋까지** — 모든 게 강조되면 아무것도 강조 안 된다.

## 컬러 — Grayscale

UI의 거의 모든 톤이 회색 11단계 안에서 결정된다.

<div class="token-grid">
  <div class="token-swatch"><div class="swatch" style="background:#FFFFFF;border-bottom:1px solid var(--border-color);"></div><div class="label"><span class="name">white</span><span class="value">#FFFFFF</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FAFAFA;"></div><div class="label"><span class="name">gray-50</span><span class="value">#FAFAFA</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#F5F5F7;"></div><div class="label"><span class="name">gray-100</span><span class="value">#F5F5F7</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#E8E8ED;"></div><div class="label"><span class="name">gray-200</span><span class="value">#E8E8ED</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#D2D2D7;"></div><div class="label"><span class="name">gray-300</span><span class="value">#D2D2D7</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#AEAEB2;"></div><div class="label"><span class="name">gray-400</span><span class="value">#AEAEB2</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#8E8E93;"></div><div class="label"><span class="name">gray-500</span><span class="value">#8E8E93</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#636366;"></div><div class="label"><span class="name">gray-600</span><span class="value">#636366</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#48484A;"></div><div class="label"><span class="name">gray-700</span><span class="value">#48484A</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#2C2C2E;"></div><div class="label"><span class="name">gray-800</span><span class="value">#2C2C2E</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#1C1C1E;"></div><div class="label"><span class="name">gray-900</span><span class="value">#1C1C1E</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#000000;"></div><div class="label"><span class="name">black</span><span class="value">#000000</span></div></div>
</div>

## 컬러 — Primary & Semantic

<div class="token-grid">
  <div class="token-swatch"><div class="swatch" style="background:#0071E3;"></div><div class="label"><span class="name">primary</span><span class="value">#0071E3</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#30D158;"></div><div class="label"><span class="name">success</span><span class="value">#30D158</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FFD60A;"></div><div class="label"><span class="name">warning</span><span class="value">#FFD60A</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FF453A;"></div><div class="label"><span class="name">error</span><span class="value">#FF453A</span></div></div>
</div>

Primary는 CTA(Call to Action) 1개에만. 페이지에 Primary 버튼이 두 개라면, 그건 둘 다 약해진다는 뜻.

## 타이포그래피

본문 기본 16px. 줄 길이 45~75자. 행간 1.5. 굵기는 Regular(400)과 Semibold(600) 두 가지면 충분.

| Token | Size | 용도 |
|---|---|---|
| `text-xs` | 12px | meta, caption |
| `text-sm` | 14px | label, button |
| `text-base` | 16px | body |
| `text-lg` | 18px | lead |
| `text-xl` | 20px | h3 |
| `text-2xl` | 24px | h2 |
| `text-3xl` | 30px | h1 (mobile) |
| `text-4xl` | 36px | h1 (desktop) |
| `text-5xl` | 48px | hero |

스케일은 Major Third(1.250) 기반. 인접 단계 차이가 명확해서 위계가 자연스럽게 형성된다.

폰트: `system-ui` 우선 (`-apple-system`, `Pretendard`, `Apple SD Gothic Neo`). OS의 한글 폰트를 신뢰한다. 웹 폰트 다운로드 비용 ❌.

## 간격 — 8px Grid

모든 간격은 8의 배수. 기억하기 쉽고, 디바이스마다 일관되게 보인다.

| Token | Value | 용도 |
|---|---|---|
| `space-1` | 4px | 미세 조정 |
| `space-2` | 8px | base unit |
| `space-3` | 12px | tight |
| `space-4` | 16px | normal (default) |
| `space-6` | 24px | comfortable |
| `space-8` | 32px | loose |
| `space-12` | 48px | section |
| `space-16` | 64px | hero |

의심스러우면 늘린다. 줄어든 여백은 답답함을 만든다.

## 모서리 — Border Radius

| Token | Value | 용도 |
|---|---|---|
| `radius-sm` | 6px | input, code chip |
| `radius-md` | 8px | tag, badge |
| `radius-lg` | 12px | card, panel (default) |
| `radius-xl` | 16px | feature card |
| `radius-full` | 9999px | button (pill), avatar |

직각은 거의 안 쓴다. 부드러움 = 친근함.

## 그림자

| Token | 용도 |
|---|---|
| `shadow-sm` | 카드 정적 |
| `shadow-md` | 드롭다운, 카드 hover |
| `shadow-lg` | 모달, 두드러진 카드 |

다크 모드에서는 그림자 대신 *더 진한 검정 배경*과 *border 강조*로 깊이를 표현. 검은 배경에 검은 그림자는 안 보이니까.

## 모션

- `duration-fast` (120ms) — hover, tap 등 마이크로
- `duration-normal` (200ms) — 토글, 드롭다운
- `duration-slow` (350ms) — 모달, 페이지 전환

300ms를 넘으면 사용자가 "느리다"고 느낀다. `prefers-reduced-motion` 미디어 쿼리로 *반드시* 모션을 끌 수 있게 한다 (접근성).

## 다크 모드

`[data-theme="dark"]` 셀렉터로 토큰을 재정의한다. 핵심 변화 셋:

1. 배경은 `gray-900` (순수 검정 ❌. 검정은 OLED 외엔 부담만 됨)
2. Primary 컬러를 약간 더 밝게 (`#0071E3` → `#2997FF`)
3. 그림자 알파값을 강하게 (어두운 배경에서 잘 보이도록)

토글은 OS 시스템 설정을 우선 따르고, 사용자가 명시적으로 바꾸면 `localStorage`에 저장.

## 반응형

Mobile first. `min-width` 미디어 쿼리만 사용.

| Breakpoint | Min Width | 용도 |
|---|---|---|
| `sm` | 640px | 큰 폰 |
| `md` | 768px | 태블릿 |
| `lg` | 1024px | 데스크톱 |
| `xl` | 1280px | 큰 데스크톱 |

`px` 대신 `rem`을 쓴다 (사용자가 글자 크기 키우면 레이아웃도 같이 적응).

## 접근성

- WCAG 2.1 AA 대비 (텍스트 4.5:1, UI 3:1)
- 시맨틱 HTML 사용 (`<button>`, `<nav>`, `<article>` 등)
- `:focus-visible` 명시적 outline
- 터치 타깃 최소 44px
- `prefers-reduced-motion` 지원
- 색상만으로 정보 전달 ❌ (텍스트나 아이콘 병행)

## 컴포넌트

이 페이지 자체가 디자인 시스템을 그대로 적용한 결과다. 헤더, 카드(프로젝트 리스트), 표, 다크 모드 토글 — 모두 위 토큰들로 구성.

## 결정 로그

- **순수 검정 X** — OLED만 빼면 모든 화면에서 부담스럽다. `gray-900`이 적정선.
- **시스템 폰트 우선** — 웹폰트 로딩 시간 + FOIT/FOUT 트레이드오프가 너무 크다. 한글은 OS가 잘 처리한다.
- **버튼은 pill** — 기능적 목적의 사각이 아니라, *친근함*을 표현하는 둥근 형태. iOS 기조와 일치.
- **컬러 토큰을 의미 단위까지 한 번 더 매핑** — `--bg-primary`, `--text-secondary` 같이. raw color 직접 쓰지 않음. 다크 모드 시 한 줄로 전환 가능.

---

> 디자인 시스템은 한 번 만들고 끝이 아니다. 쓰면서 발견한 빈 곳을 메우고, 안 쓰는 토큰을 지운다. 살아있는 문서.
