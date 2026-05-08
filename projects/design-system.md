---
layout: default
title: Design System
permalink: /projects/design-system/
description: Apple HIG + Dieter Rams 기반 토큰화된 디자인 시스템.
toc:
  - { id: philosophy, label: Philosophy }
  - { id: principles, label: "10 Principles" }
  - { id: color, label: Color }
  - { id: typography, label: Typography }
  - { id: spacing, label: "Spacing & Layout" }
  - { id: grid, label: "Grid System" }
  - { id: components, label: Components }
  - { id: buttons, label: "— Buttons", indent: true }
  - { id: inputs, label: "— Inputs", indent: true }
  - { id: cards, label: "— Cards", indent: true }
  - { id: badges-alerts, label: "— Badges & Alerts", indent: true }
  - { id: tables, label: "— Tables", indent: true }
  - { id: tabs, label: "— Tabs", indent: true }
  - { id: modals, label: "— Modals", indent: true }
  - { id: misc, label: "— Misc", indent: true }
  - { id: shadows, label: Shadows }
  - { id: motion, label: Motion }
  - { id: iconography, label: Iconography }
  - { id: darkmode, label: "Dark Mode" }
  - { id: accessibility, label: Accessibility }
  - { id: hierarchy, label: "Visual Hierarchy" }
  - { id: whitespace, label: Whitespace }
  - { id: tokens, label: "Design Tokens" }
  - { id: responsive, label: Responsive }
  - { id: changelog, label: Changelog }
---

<header class="page-header">
  <p class="meta">2026 · Design System</p>
  <h1>Design System</h1>
  <p>웹과 앱 어디에서든 적용 가능한, 토큰 기반의 미니멀 디자인 체계.</p>
</header>

## Philosophy {#philosophy}

> "Good design is as little design as possible." — Dieter Rams

이 시스템은 **명확함, 일관성, 절제**를 최우선 가치로 삼는다. Apple Human Interface Guidelines와 Dieter Rams의 디자인 철학을 기반으로, 모든 플랫폼에서 통일된 경험을 제공한다.

### 핵심 가치

<div class="principle-card">
  <h4>Clarity (명확함)</h4>
  <p>모든 요소는 즉시 이해 가능해야 한다. 텍스트는 읽기 쉽고, 아이콘은 직관적이며, 장식은 기능에 종속된다. 사용자가 "이게 뭐지?"라고 생각하는 순간 디자인은 실패한 것.</p>
</div>

<div class="principle-card">
  <h4>Deference (절제)</h4>
  <p>UI는 콘텐츠를 돋보이게 하는 것이지, UI 자체가 주인공이 되어선 안 된다. 그라디언트·그림자·테두리는 정보 전달에 필요할 때만 사용한다.</p>
</div>

<div class="principle-card">
  <h4>Consistency (일관성)</h4>
  <p>같은 패턴은 같은 방식으로 작동해야 한다. 한 번 배운 인터랙션은 모든 곳에서 동일하게 적용된다. 이것이 토큰과 컴포넌트를 사용하는 이유.</p>
</div>

<div class="principle-card">
  <h4>Depth (깊이)</h4>
  <p>시각적 레이어와 자연스러운 모션은 사용자가 인터페이스를 이해하는 데 도움을 준다. 무엇이 위에 있고 무엇이 뒤에 있는지 — 계층이 맥락을 만든다.</p>
</div>

## Dieter Rams의 10 Principles {#principles}

좋은 디자인이란 무엇인가? 1970년대에 쓰였지만 디지털 인터페이스에도 그대로 적용된다.

<div class="principle-card"><div class="principle-num">Principle 01</div><h4>Good design is innovative</h4><p>기술 발전은 항상 혁신적 디자인의 기회를 제공한다. 하지만 혁신 자체가 목적이 되어선 안 된다. 기술이 아닌 사용자의 문제에서 출발하라.</p></div>

<div class="principle-card"><div class="principle-num">Principle 02</div><h4>Good design makes a product useful</h4><p>제품은 사용되기 위해 존재한다. 디자인의 가장 중요한 역할은 유용성. 아름답지만 쓸 수 없는 인터페이스는 나쁜 디자인.</p></div>

<div class="principle-card"><div class="principle-num">Principle 03</div><h4>Good design is aesthetic</h4><p>매일 사용하는 도구의 미적 품질은 웰빙에 영향을 미친다. 잘 만들어진 인터페이스는 사용자에게 신뢰감과 만족감을 준다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 04</div><h4>Good design makes a product understandable</h4><p>제품은 스스로를 설명해야 한다. 버튼은 버튼처럼 보여야 하고, 링크는 링크처럼 보여야 한다. 별도의 설명서가 필요한 UI는 실패한 것.</p></div>

<div class="principle-card"><div class="principle-num">Principle 05</div><h4>Good design is unobtrusive</h4><p>디자인은 도구다. 자기 주장이 강한 디자인은 사용자의 자기 표현 공간을 침범한다. UI는 사용자가 자신의 목적을 달성하는 데 조용히 기여해야 한다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 06</div><h4>Good design is honest</h4><p>제품을 실제보다 혁신적이거나, 강력하거나, 가치 있게 보이도록 조작하지 마라. 다크 패턴, 과장된 애니메이션, 허위 긴급성 표시는 정직하지 않은 디자인.</p></div>

<div class="principle-card"><div class="principle-num">Principle 07</div><h4>Good design is long-lasting</h4><p>유행을 따르지 마라. 트렌디한 디자인은 빠르게 낡아 보인다. 클래식한 서체, 절제된 컬러, 기하학적 레이아웃은 시간이 지나도 우아하다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 08</div><h4>Good design is thorough down to the last detail</h4><p>어떤 것도 임의적이거나 우연에 맡겨져선 안 된다. 4px의 패딩 차이, 0.1초의 애니메이션 차이 — 디테일에 대한 집착이 품질을 만든다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 09</div><h4>Good design is environmentally friendly</h4><p>디지털 맥락에서 이는 성능을 의미한다. 불필요한 애니메이션, 무거운 이미지, 과도한 JS는 에너지를 낭비한다. 가벼운 것이 좋은 것.</p></div>

<div class="principle-card"><div class="principle-num">Principle 10</div><h4>Good design is as little design as possible</h4><p>본질에 집중하라. 제거할 수 있는 모든 것을 제거한 뒤에 남는 것이 좋은 디자인. "이 요소가 없으면 안 되는가?"를 항상 질문하라.</p></div>

## Color {#color}

색상은 정보를 전달하는 도구. 장식이 아니라 의미를 담아야 한다. 이 시스템은 Apple의 접근법처럼 중립적 Grayscale 기반에 최소한의 강조색을 사용한다.

### Grayscale

UI의 90% 이상은 Grayscale로 구성된다. 색을 절제해야 강조색이 의미를 가진다.

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

### Primary Color

하나의 강조색만 사용. 이것이 브랜드이자 행동 유도(CTA)의 신호.

<div class="token-grid">
  <div class="token-swatch"><div class="swatch" style="background:#E1F0FF;"></div><div class="label"><span class="name">primary-light</span><span class="value">#E1F0FF</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#0071E3;"></div><div class="label"><span class="name">primary</span><span class="value">#0071E3</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#0077ED;"></div><div class="label"><span class="name">hover</span><span class="value">#0077ED</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#006EDB;"></div><div class="label"><span class="name">active</span><span class="value">#006EDB</span></div></div>
</div>

### Semantic Colors

상태를 나타내는 색상. 전 세계적으로 통용되는 의미를 따른다. 초록 = 성공, 빨강 = 오류, 노랑 = 경고.

<div class="token-grid">
  <div class="token-swatch"><div class="swatch" style="background:#30D158;"></div><div class="label"><span class="name">success</span><span class="value">#30D158</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FFD60A;"></div><div class="label"><span class="name">warning</span><span class="value">#FFD60A</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FF453A;"></div><div class="label"><span class="name">error</span><span class="value">#FF453A</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#64D2FF;"></div><div class="label"><span class="name">info</span><span class="value">#64D2FF</span></div></div>
</div>

### 사용 규칙

- 배경은 White 또는 Gray 50~100을 사용
- 본문 텍스트는 Gray 900 (라이트) / Gray 100 (다크)
- 보조 텍스트는 Gray 600 (라이트) / Gray 400 (다크)
- Primary color는 CTA 버튼·링크·활성 상태에만 사용
- 색상만으로 정보 전달 ❌ 색맹 사용자를 위해 아이콘·텍스트 병행
- WCAG 2.1 AA 기준: 일반 텍스트 4.5:1, 큰 텍스트 3:1 대비 비율 유지

## Typography {#typography}

타이포그래피는 디자인의 90%. 인터페이스 대부분은 텍스트이므로 글꼴·크기 체계·행간이 전체 품질을 좌우한다.

### Font Stack

```css
--font-sans: -apple-system, BlinkMacSystemFont, 'Apple SD Gothic Neo',
             'Pretendard Variable', Pretendard, 'Noto Sans KR',
             system-ui, sans-serif;

--font-mono: 'SF Mono', 'Fira Code', 'Fira Mono',
             'Roboto Mono', 'Courier New', monospace;
```

시스템 폰트를 우선하면 로딩 시간이 0이고, OS와 자연스럽게 어울린다. 한글은 Pretendard 또는 Apple SD Gothic Neo가 가장 깔끔.

### Type Scale

Major Third(1.250) 비율 기반. 각 단계 사이의 차이가 명확하면서도 과하지 않다.

<div class="demo-box">
  <div style="font-size:3.75rem;font-weight:700;letter-spacing:-0.022em;line-height:1.1;">Display Large</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-6xl / 60px / Bold / tracking-tight / leading: 1.1</div>

  <div style="font-size:3rem;font-weight:700;letter-spacing:-0.022em;line-height:1.15;">Display</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-5xl / 48px / Bold / tracking-tight / leading: 1.15</div>

  <div style="font-size:2.25rem;font-weight:600;letter-spacing:-0.022em;line-height:1.2;">Heading 1</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-4xl / 36px / Semibold / tracking-tight / leading: 1.2</div>

  <div style="font-size:1.875rem;font-weight:600;letter-spacing:-0.022em;line-height:1.25;">Heading 2</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-3xl / 30px / Semibold / tracking-tight / leading: 1.25</div>

  <div style="font-size:1.5rem;font-weight:600;line-height:1.3;">Heading 3</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-2xl / 24px / Semibold / leading: 1.3</div>

  <div style="font-size:1.25rem;font-weight:600;line-height:1.4;">Heading 4</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-xl / 20px / Semibold / leading: 1.4</div>

  <div style="font-size:1.125rem;line-height:1.5;">Body Large — 본문이 길 때 사용. 블로그 포스트나 설명 페이지에 적합.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-lg / 18px / Regular / leading: 1.5</div>

  <div style="font-size:1rem;line-height:1.5;">Body — 기본 본문 크기. 대부분의 UI 텍스트에 사용.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-base / 16px / Regular / leading: 1.5</div>

  <div style="font-size:0.875rem;line-height:1.5;color:var(--text-secondary);">Small — 보조 정보, 캡션, 메타 데이터.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-sm / 14px / Regular / leading: 1.5</div>

  <div style="font-size:0.75rem;line-height:1.5;color:var(--text-tertiary);">XS — 라벨, 배지, 타임스탬프.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;">text-xs / 12px / Regular / leading: 1.5</div>
</div>

### 타이포그래피 규칙

- **본문 최소 크기**: 16px. 모바일에서도 14px 이하는 피한다
- **줄 길이**: 45~75자 (한글 25~40자). 이보다 길면 가독성이 크게 떨어진다
- **행간(line-height)**: 본문 1.5, 헤딩 1.2~1.3이 최적
- **자간(letter-spacing)**: 큰 글씨는 약간 좁게(-0.022em), 작은 글씨는 기본 또는 약간 넓게
- **굵기 사용**: Regular(400)과 Semibold(600) 두 가지면 충분. 굵기가 너무 많으면 계층이 무너진다
- **대문자**: 라벨이나 카테고리 등 짧은 텍스트에만. 긴 문장은 가독성이 30% 떨어진다

## Spacing & Layout {#spacing}

일관된 간격은 질서를 만든다. 8px 그리드를 기본 단위로 사용하면 모든 요소가 자연스럽게 정렬된다.

### 8px Grid System

모든 간격은 8의 배수가 기본. 세밀한 조정이 필요할 때 4px(half unit) 사용.

<div class="demo-box">
  <div class="spacing-demo">
    <div class="spacing-item"><div class="spacing-block" style="width:16px;height:16px;">4</div><div class="meta">space-1</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:24px;height:24px;">8</div><div class="meta">space-2</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:32px;height:32px;">12</div><div class="meta">space-3</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:40px;height:40px;">16</div><div class="meta">space-4</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:52px;height:52px;">24</div><div class="meta">space-6</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:64px;height:64px;">32</div><div class="meta">space-8</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:80px;height:80px;">48</div><div class="meta">space-12</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:96px;height:96px;">64</div><div class="meta">space-16</div></div>
  </div>
</div>

### 간격 사용 가이드

| 용도 | Token | 값 |
|---|---|---|
| 인라인 요소 사이 (아이콘-텍스트) | `space-2` | 8px |
| 관련 요소 사이 (라벨-인풋) | `space-2~3` | 8~12px |
| 컴포넌트 내부 패딩 | `space-4~6` | 16~24px |
| 컴포넌트 사이 간격 | `space-6~8` | 24~32px |
| 섹션 사이 간격 | `space-16~24` | 64~96px |
| 페이지 상하단 여백 | `space-16~32` | 64~128px |

## Grid System {#grid}

CSS Grid와 Flexbox를 사용하여 유연하고 반응형인 레이아웃을 구성한다. 12 컬럼 그리드를 기본으로 하되 필요에 따라 자유롭게 조정.

### 12-Column Grid

<div class="demo-box">
  <div style="display:grid;grid-template-columns:repeat(12,1fr);gap:var(--space-2);">
    <div style="grid-column:span 12;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">12</div>
    <div style="grid-column:span 6;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">6</div>
    <div style="grid-column:span 6;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">6</div>
    <div style="grid-column:span 4;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">4</div>
    <div style="grid-column:span 4;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">4</div>
    <div style="grid-column:span 4;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">4</div>
    <div style="grid-column:span 3;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">3</div>
    <div style="grid-column:span 3;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">3</div>
    <div style="grid-column:span 3;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">3</div>
    <div style="grid-column:span 3;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">3</div>
    <div style="grid-column:span 8;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">8</div>
    <div style="grid-column:span 4;background:var(--color-primary-light);border:1px dashed var(--color-primary);border-radius:var(--radius-sm);padding:var(--space-3);text-align:center;font-family:var(--font-mono);font-size:var(--text-xs);color:var(--color-primary);">4</div>
  </div>
</div>

### Container Widths

| Token | Width | 용도 |
|---|---|---|
| `container-sm` | 640px | 텍스트 중심 콘텐츠 (블로그, 문서) |
| `container-md` | 768px | 폼, 설정 페이지 |
| `container-lg` | 1024px | 일반적인 앱 레이아웃 |
| `container-xl` | 1280px | 대시보드, 넓은 레이아웃 |
| `container-2xl` | 1440px | 최대 너비 (대형 모니터) |

### Breakpoints

```css
/* Mobile first approach */
/* Base:    0~639px   (모바일) */
/* sm:      640px+    (큰 모바일 / 작은 태블릿) */
/* md:      768px+    (태블릿) */
/* lg:      1024px+   (작은 데스크톱) */
/* xl:      1280px+   (데스크톱) */
/* 2xl:     1440px+   (대형 모니터) */

@media (min-width: 640px)  { /* sm */ }
@media (min-width: 768px)  { /* md */ }
@media (min-width: 1024px) { /* lg */ }
@media (min-width: 1280px) { /* xl */ }
@media (min-width: 1440px) { /* 2xl */ }
```

## Components {#components}

재사용 가능한 UI 빌딩 블록. 각 컴포넌트는 명확한 역할이 있으며 일관된 API(class naming)를 따른다.

### Buttons {#buttons}

버튼은 사용자가 할 수 있는 행동을 나타낸다. 한 화면에 Primary 버튼은 하나만.

<div class="demo-box">
  <div class="demo-row">
    <button class="btn btn-primary">Primary</button>
    <button class="btn btn-secondary">Secondary</button>
    <button class="btn btn-ghost">Ghost</button>
    <button class="btn btn-danger">Danger</button>
  </div>
  <div class="demo-row">
    <button class="btn btn-primary btn-sm">Small</button>
    <button class="btn btn-primary">Default</button>
    <button class="btn btn-primary btn-lg">Large</button>
  </div>
  <div class="demo-row">
    <button class="btn btn-primary" disabled>Disabled</button>
    <button class="btn btn-secondary" disabled>Disabled</button>
  </div>
</div>

```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-ghost">Ghost</button>
<button class="btn btn-danger">Danger</button>
```

#### 버튼 사용 규칙
- **Primary**: 페이지당 1개. 가장 중요한 행동 (저장, 제출, 구매)
- **Secondary**: 보조 행동 (취소, 뒤로가기)
- **Ghost**: 덜 중요한 행동, 인라인 사용
- **Danger**: 되돌릴 수 없는 파괴적 행동 (삭제)에만 사용
- 버튼 텍스트는 동사로 시작: "저장하기", "삭제", "보내기"
- "확인", "예" 같은 모호한 텍스트는 피한다

### Inputs {#inputs}

<div class="demo-box">
  <div class="input-group" style="margin-bottom:var(--space-5);">
    <label class="input-label">이메일</label>
    <input class="input-field" type="email" placeholder="hello@example.com">
    <span class="input-hint">업무용 이메일을 입력하세요.</span>
  </div>
  <div class="input-group" style="margin-bottom:var(--space-5);">
    <label class="input-label">비밀번호</label>
    <input class="input-field input-error" type="password" value="abc">
    <span class="input-hint error">8자 이상 입력하세요.</span>
  </div>
  <div class="input-group" style="margin-bottom:var(--space-5);">
    <label class="input-label">메시지</label>
    <textarea class="textarea-field" placeholder="내용을 입력하세요..."></textarea>
  </div>
  <div class="demo-row" style="gap:var(--space-5);">
    <label class="toggle">
      <input type="checkbox">
      <div class="track"></div>
      <div class="thumb"></div>
    </label>
    <label class="toggle">
      <input type="checkbox" checked>
      <div class="track"></div>
      <div class="thumb"></div>
    </label>
  </div>
</div>

```html
<div class="input-group">
  <label class="input-label">이메일</label>
  <input class="input-field" type="email" placeholder="hello@example.com">
  <span class="input-hint">업무용 이메일을 입력하세요.</span>
</div>

<!-- Error state -->
<input class="input-field input-error" type="password">
<span class="input-hint error">8자 이상 입력하세요.</span>

<!-- Toggle -->
<label class="toggle">
  <input type="checkbox">
  <div class="track"></div>
  <div class="thumb"></div>
</label>
```

### Cards {#cards}

카드는 관련 정보를 하나의 단위로 묶어준다. 클릭 가능한 카드에는 hover 효과를 준다.

<div class="demo-box">
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:var(--space-4);">
    <div class="card card-interactive">
      <div class="card-image"></div>
      <div class="card-body">
        <h4>Card Title</h4>
        <p>카드의 간략한 설명. 2줄 이내를 권장한다.</p>
      </div>
    </div>
    <div class="card card-interactive">
      <div class="card-image"></div>
      <div class="card-body">
        <h4>Card Title</h4>
        <p>호버하면 살짝 떠오른다.</p>
      </div>
    </div>
    <div class="card card-interactive">
      <div class="card-image"></div>
      <div class="card-body">
        <h4>Card Title</h4>
        <p>이미지·제목·설명의 단순한 구조.</p>
      </div>
    </div>
  </div>
</div>

### Badges &amp; Alerts {#badges-alerts}

#### Badges

<div class="demo-box">
  <div class="demo-row">
    <span class="badge badge-default">Default</span>
    <span class="badge badge-primary">Primary</span>
    <span class="badge badge-success">Success</span>
    <span class="badge badge-warning">Warning</span>
    <span class="badge badge-error">Error</span>
  </div>
</div>

#### Alerts

<div class="demo-box">
  <div class="alert alert-info">ⓘ 새로운 버전이 출시되었습니다.</div>
  <div class="alert alert-success">✓ 변경사항이 성공적으로 저장되었습니다.</div>
  <div class="alert alert-warning">⚠ 이 작업은 되돌릴 수 없습니다.</div>
  <div class="alert alert-error">✗ 네트워크 오류가 발생했습니다. 다시 시도하세요.</div>
</div>

### Tables {#tables}

<div class="demo-box">
  <table>
    <thead>
      <tr><th>이름</th><th>역할</th><th>상태</th></tr>
    </thead>
    <tbody>
      <tr><td>김서준</td><td>Frontend Developer</td><td><span class="badge badge-success">Active</span></td></tr>
      <tr><td>이하은</td><td>Product Designer</td><td><span class="badge badge-success">Active</span></td></tr>
      <tr><td>박도윤</td><td>Backend Developer</td><td><span class="badge badge-warning">Away</span></td></tr>
    </tbody>
  </table>
</div>

### Tabs {#tabs}

<div class="demo-box">
  <div class="tabs">
    <button class="tab active">Overview</button>
    <button class="tab">Features</button>
    <button class="tab">Pricing</button>
    <button class="tab">FAQ</button>
  </div>
</div>

### Modals {#modals}

모달은 사용자의 주의를 강제하므로 신중하게 사용. 되돌릴 수 없는 행동 확인에 적합.

<div class="demo-box">
  <div class="modal-demo">
    <h4>변경사항을 저장할까요?</h4>
    <p>저장하지 않으면 작업 내용이 사라집니다.</p>
    <div class="modal-actions">
      <button class="btn btn-secondary">취소</button>
      <button class="btn btn-primary">저장</button>
    </div>
  </div>
</div>

### Misc {#misc}

#### Avatar
<div class="demo-box">
  <div class="demo-row">
    <div class="avatar avatar-sm">S</div>
    <div class="avatar">M</div>
    <div class="avatar avatar-lg">L</div>
  </div>
</div>

#### Progress
<div class="demo-box">
  <div class="progress"><div class="progress-bar" style="width:35%;"></div></div>
  <div class="progress"><div class="progress-bar" style="width:72%;"></div></div>
</div>

#### Skeleton Loader
<div class="demo-box">
  <div class="skeleton" style="height:16px;width:60%;margin-bottom:var(--space-2);"></div>
  <div class="skeleton" style="height:16px;width:80%;margin-bottom:var(--space-2);"></div>
  <div class="skeleton" style="height:16px;width:40%;"></div>
</div>

#### Divider
<div class="demo-box">
  <p>위의 콘텐츠</p>
  <hr style="margin:var(--space-6) 0;border:none;border-top:1px solid var(--border-color);">
  <p>아래의 콘텐츠</p>
</div>

## Shadows &amp; Elevation {#shadows}

그림자는 깊이감과 계층을 전달한다. 높이가 높을수록 그림자가 커지고, 사용자의 시선을 끌어 중요도를 나타낸다.

<div class="demo-box">
  <div class="shadow-demo-grid">
    <div class="shadow-box" style="box-shadow:var(--shadow-sm);">shadow-sm</div>
    <div class="shadow-box" style="box-shadow:var(--shadow-md);">shadow-md</div>
    <div class="shadow-box" style="box-shadow:var(--shadow-lg);">shadow-lg</div>
    <div class="shadow-box" style="box-shadow:0 16px 48px rgba(0,0,0,0.16);">shadow-xl</div>
  </div>
</div>

| Token | 용도 |
|---|---|
| `shadow-sm` | 카드, 인풋 기본 |
| `shadow-md` | 드롭다운, 팝오버 |
| `shadow-lg` | 카드 hover, 토스트 |
| `shadow-xl` | 모달, 다이얼로그 |

### 그림자 사용 규칙
- 그림자는 *상호작용 가능한 요소*에만 사용한다
- 정적인 텍스트 블록에 그림자를 주지 마라
- 그림자 색상은 순수 검정(rgba(0,0,0))을 사용. 컬러 쉐도우 ❌
- 다크 모드에서는 그림자 대신 *border*나 배경색 차이로 계층을 표현하는 것이 효과적

## Motion {#motion}

애니메이션은 인터페이스에 생명을 불어넣지만 과하면 방해가 된다. Apple의 접근법처럼 "물리적으로 자연스러운" 움직임을 추구한다.

### Duration

| Token | Duration | 용도 |
|---|---|---|
| `duration-fast` | 120ms | 버튼 hover, 색상 변경 등 마이크로 인터랙션 |
| `duration-normal` | 200ms | 토글, 드롭다운 열기/닫기 |
| `duration-slow` | 350ms | 모달 등장, 페이지 전환, 레이아웃 변경 |

### Easing

| Token | Curve | 용도 |
|---|---|---|
| `easing-default` | `cubic-bezier(0.25, 0.1, 0.25, 1)` | 대부분의 전환에 사용. 자연스러운 감속 |
| `easing-spring` | `cubic-bezier(0.34, 1.56, 0.64, 1)` | 토글, 바운스 효과. 약간의 오버슈트가 활력 |

### 모션 원칙

- **목적 있는 움직임만** — 모든 애니메이션은 "왜?"에 답할 수 있어야 한다. 피드백, 방향 안내, 연결 관계 표현
- **300ms 이하** — 대부분의 UI 전환은 300ms를 넘지 않는다. 그 이상은 느리게 느껴진다
- **ease-out 선호** — 요소가 나타날 때는 ease-out (빠르게 시작, 천천히 끝), 사라질 때는 ease-in
- **reduce-motion 존중** — `prefers-reduced-motion` 미디어 쿼리로 애니메이션을 끌 수 있게 한다

```css
/* reduce-motion 대응 */
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

## Iconography {#iconography}

아이콘은 텍스트를 보완하는 시각적 단서. 단독으로는 의미가 모호할 수 있으므로 항상 텍스트와 함께 사용한다.

### 권장 아이콘 라이브러리

| 라이브러리 | 스타일 | 추천 이유 |
|---|---|---|
| **Lucide** | Line (Outline) | 깔끔, 가벼움, Vue/React 지원, MIT 라이선스 |
| **Phosphor Icons** | 6가지 weight | 다양한 굵기 제공, 유연한 스타일링 |
| **SF Symbols** (Apple) | Multi-weight | Apple 생태계 최적화, macOS/iOS 전용 |
| **Material Symbols** | Variable font | 구글 생태계, 방대한 아이콘 수 |

### 아이콘 사용 규칙

- **크기**: 16px (인라인), 20px (버튼 내), 24px (내비게이션), 32px+ (기능 강조)
- **색상**: 아이콘 색상은 주변 텍스트 색상과 동일. 별도 색을 주지 마라
- **접근성**: 의미 있는 아이콘은 `aria-label`을, 장식용은 `aria-hidden="true"`
- **일관성**: 하나의 프로젝트에는 하나의 아이콘 라이브러리만. 섞지 마라
- **Stroke width**: 1.5~2px가 가장 깔끔. 너무 가늘면 안 보이고, 두꺼우면 답답하다

## Dark Mode {#darkmode}

다크 모드는 단순히 색을 반전하는 것이 아니다. Apple처럼 "어둠 위에 떠 있는 레이어"로 접근한다.

### 핵심 원칙

- **순수 검정(#000) 배경은 피한다** — OLED에서는 효과적이지만, 대부분의 화면에서 너무 강한 대비는 눈을 피로하게 한다. Gray 900 (#1C1C1E)이 적절
- **그림자 대신 border** — 어두운 배경에서 그림자는 잘 보이지 않는다. 밝은 border로 계층을 표현
- **Primary color 밝기 조정** — 라이트의 Primary (#0071E3)는 다크 배경에서 대비 부족. 더 밝은 변형 (#2997FF) 사용
- **이미지 밝기 조정** — 밝은 이미지는 `filter: brightness(0.9)`로 살짝 어둡게
- **Semantic Token 사용** — `#1C1C1E` 대신 `var(--bg-primary)`를 사용하면 테마 전환이 자동

### 구현

```css
/* CSS: data-theme 속성으로 전환 */
[data-theme="dark"] {
  --bg-primary:      var(--color-gray-900);
  --bg-secondary:    var(--color-gray-800);
  --text-primary:    var(--color-gray-100);
  --text-secondary:  var(--color-gray-400);
  --border-color:    var(--color-gray-700);
  --color-primary:   #2997FF;
}
```

```js
/* JS: 토글 */
function toggleTheme() {
  const isDark = document.documentElement.dataset.theme === 'dark';
  document.documentElement.dataset.theme = isDark ? 'light' : 'dark';
  localStorage.setItem('theme', isDark ? 'light' : 'dark');
}

/* 시스템 설정 감지 */
if (window.matchMedia('(prefers-color-scheme: dark)').matches) {
  document.documentElement.dataset.theme = 'dark';
}
```

이 페이지의 우하단 토글로 직접 시험해볼 수 있다.

## Accessibility {#accessibility}

접근성은 선택이 아니라 기본. 좋은 디자인은 모든 사람을 위한 디자인이다. WCAG 2.1 AA 수준을 최소 기준으로 삼는다.

### 체크리스트

- **색상 대비** — 일반 텍스트 4.5:1, 큰 텍스트(18px+) 3:1 이상
- **키보드 탐색** — 모든 인터랙티브 요소는 Tab으로 접근 가능해야 한다
- **Focus 표시** — `:focus-visible` 스타일을 절대 제거하지 마라. 사용자 정의는 OK
- **시맨틱 HTML** — `<button>`, `<nav>`, `<main>`, `<header>` 등을 올바르게 사용
- **ARIA** — 시맨틱 HTML로 충분하지 않을 때만 사용. 잘못된 ARIA는 없는 것보다 나쁘다
- **색상만으로 정보 전달 ❌** — 에러는 빨간색 + 아이콘 + 텍스트로 표현
- **터치 영역** — 최소 44x44px (Apple HIG 권장)
- **움직임** — `prefers-reduced-motion`을 반드시 지원
- **이미지** — 의미 있는 이미지는 `alt` 텍스트 필수
- **폰트 크기** — `rem` 단위 사용. 사용자의 브라우저 설정을 존중한다

```css
/* Focus visible — 키보드 사용자에게만 표시 */
:focus-visible {
  outline: 2px solid var(--color-primary);
  outline-offset: 2px;
}

/* 마우스 클릭 시에는 outline 숨김 */
:focus:not(:focus-visible) {
  outline: none;
}
```

## Visual Hierarchy {#hierarchy}

시각적 계층은 사용자의 시선을 안내한다. "무엇을 먼저 보여줄 것인가"를 의식적으로 결정하라.

### 계층을 만드는 도구

| 도구 | 효과 | 예시 |
|---|---|---|
| **크기 (Size)** | 큰 것이 먼저 눈에 들어옴 | 제목 > 본문 > 캡션 |
| **굵기 (Weight)** | 굵은 것이 더 강조됨 | Bold 제목 > Regular 본문 |
| **색상 (Color)** | 대비가 높은 것이 먼저 보임 | 검정 제목 > 회색 보조 텍스트 |
| **여백 (Space)** | 주변 여백이 넓으면 중요해 보임 | Apple.com의 제품 이미지 |
| **위치 (Position)** | 위, 왼쪽이 먼저 읽힘 (F-패턴) | 네비게이션 > 콘텐츠 > 사이드바 |
| **그림자/깊이** | 떠 있는 것이 더 중요해 보임 | 모달 > 페이지 콘텐츠 |

### 실전 규칙

- **3단계 법칙** — 한 화면에서 시각적 강도는 3단계면 충분 (Primary / Secondary / Tertiary)
- **대비를 아껴 쓰라** — 모든 것이 강조되면 아무것도 강조되지 않는다
- **그룹핑** — 관련 요소는 가까이, 무관한 요소는 멀리. 게슈탈트 근접성 원칙
- **정렬** — 보이지 않는 선에 맞춰 정렬하라. 어긋난 정렬은 즉시 "아마추어"로 느껴진다

## Whitespace {#whitespace}

여백은 "비어 있는 공간"이 아니라 "숨 쉬는 공간". Apple과 Dieter Rams의 디자인에서 여백은 가장 중요한 디자인 요소다.

### 여백의 역할

- **가독성 향상** — 텍스트 주변 여백이 넓을수록 읽기 쉽다
- **고급스러움** — 럭셔리 브랜드일수록 여백이 넓다. 여백은 여유와 자신감을 전달한다
- **시선 유도** — 여백으로 둘러싸인 요소는 자연스럽게 시선을 끈다
- **그룹핑** — 관련 요소 사이의 여백은 좁게, 다른 그룹과의 여백은 넓게

### Macro vs Micro Whitespace

| 유형 | 의미 | 예시 |
|---|---|---|
| **Macro** | 큰 구조적 여백 | 섹션 간격, 페이지 여백, 컬럼 간격 |
| **Micro** | 작은 세부 여백 | 행간, 글자 간격, 아이콘-텍스트 사이 |

> "의심스러우면 여백을 늘리세요. 공간이 부족한 것보다 넉넉한 것이 항상 낫습니다."

## Design Tokens {#tokens}

Design Token은 디자인 결정을 코드로 표현한 것. 색상·크기·간격 등의 값을 변수로 관리하면 일관성과 유지보수성을 모두 잡는다.

### 왜 Token을 사용하는가?

- **Single Source of Truth** — 색상을 바꾸고 싶으면 변수 하나만 수정
- **다크 모드** — Semantic token 덕분에 테마 전환이 자동
- **크로스 플랫폼** — 같은 토큰을 CSS, iOS (Swift), Android (Kotlin)에서 공유 가능
- **디자이너-개발자 소통** — 토큰 이름이 공통 언어가 된다

### Token 구조: 3-Layer System

```css
/* Layer 1: Global (원시값) — 절대 직접 사용하지 마라 */
--color-blue-500: #0071E3;
--color-gray-900: #1C1C1E;

/* Layer 2: Semantic (의미) — 이것을 사용하라 */
--color-primary:   var(--color-blue-500);
--text-primary:    var(--color-gray-900);
--bg-primary:      var(--color-white);

/* Layer 3: Component (컴포넌트 전용) — 필요할 때만 */
--btn-primary-bg:  var(--color-primary);
--btn-primary-text: var(--color-white);
```

개발할 때는 항상 Layer 2 (Semantic)를 사용한다. Layer 1은 정의용이고, Layer 3은 복잡한 컴포넌트에서만 필요하다.

## Responsive Design {#responsive}

모바일 퍼스트로 시작하고, 화면이 넓어질수록 레이아웃을 확장한다. 콘텐츠가 레이아웃을 결정하게 하라.

### 핵심 원칙

- **Mobile First** — 기본 CSS는 모바일. `min-width` 미디어 쿼리로 확장
- **유동적 단위** — `rem`, `%`, `vw` 사용. `px`은 border, shadow에만
- **콘텐츠 기반 breakpoint** — "768px에서 깨지니까"가 아니라 "이 콘텐츠가 답답해지는 시점"에서 전환
- **터치 vs 포인터** — 모바일은 터치 영역 44px+, 호버 없음. 데스크톱은 호버 가능
- **타이포그래피 조정** — 큰 화면에서 Display 크기를 키우되, 본문은 16px로 유지

```css
/* 반응형 타이포그래피 예시 */
h1 {
  font-size: var(--text-3xl);  /* 모바일: 30px */
}
@media (min-width: 768px) {
  h1 { font-size: var(--text-4xl); }  /* 태블릿: 36px */
}
@media (min-width: 1024px) {
  h1 { font-size: var(--text-5xl); }  /* 데스크톱: 48px */
}

/* 유동적 크기 (clamp) */
h1 {
  font-size: clamp(1.875rem, 1.5rem + 2vw, 3rem);
}
```

## Changelog {#changelog}

| 날짜 | 버전 | 변경 내용 |
|---|---|---|
| 2026-05-08 | 1.0.0 | 초안 작성 |

---

> "Less, but better." — Dieter Rams
>
> 이 가이드를 참고하되, 맹목적으로 따르지 마라. 원칙을 이해하고, 상황에 맞게 판단하라.

<p style="text-align:center;color:var(--text-tertiary);font-size:var(--text-xs);font-family:var(--font-mono);margin-top:var(--space-12);">© 최진영(Kcarl) · v1.0.0</p>
