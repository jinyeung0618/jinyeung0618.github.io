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

> "Good design is as little design as possible." — Dieter Rams

이 시스템은 **명확함, 절제, 일관성**을 최우선 가치로 삼는다. Apple Human Interface Guidelines와 Dieter Rams의 디자인 철학을 기반으로, 모든 플랫폼에서 통일된 경험을 만든다.

### 핵심 가치

<div class="principle-card">
  <h4>Clarity (명확함)</h4>
  <p>모든 요소는 즉시 이해 가능해야 한다. 사용자가 "이게 뭐지?"라고 생각하는 순간 디자인은 실패한 것이다.</p>
</div>

<div class="principle-card">
  <h4>Deference (절제)</h4>
  <p>UI는 콘텐츠를 돋보이게 하는 것이지, UI 자체가 주인공이 되어선 안 된다. 그라디언트·그림자·테두리는 정보 전달에 필요할 때만 사용한다.</p>
</div>

<div class="principle-card">
  <h4>Consistency (일관성)</h4>
  <p>같은 패턴은 같은 방식으로 작동해야 한다. 한 번 배운 인터랙션은 모든 곳에서 동일하게 적용된다. 이것이 토큰과 컴포넌트를 사용하는 이유다.</p>
</div>

<div class="principle-card">
  <h4>Depth (깊이)</h4>
  <p>시각적 레이어와 자연스러운 모션은 사용자가 인터페이스를 이해하는 데 도움을 준다. 무엇이 위에 있고 무엇이 뒤에 있는지 — 계층이 맥락을 만든다.</p>
</div>

## Dieter Rams의 10원칙

1970년대에 쓰였지만 디지털 인터페이스에도 그대로 적용된다.

<div class="principle-card"><div class="principle-num">Principle 01</div><h4>Good design is innovative</h4><p>혁신 자체가 목적이 아니다. 기술이 아닌 사용자의 문제에서 출발하라.</p></div>

<div class="principle-card"><div class="principle-num">Principle 02</div><h4>Good design makes a product useful</h4><p>아름답지만 쓸 수 없는 인터페이스는 나쁜 디자인이다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 03</div><h4>Good design is aesthetic</h4><p>매일 사용하는 도구의 미적 품질은 사용자의 만족과 신뢰에 영향을 준다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 04</div><h4>Good design makes a product understandable</h4><p>제품은 스스로를 설명해야 한다. 별도 설명서가 필요한 UI는 실패한 것.</p></div>

<div class="principle-card"><div class="principle-num">Principle 05</div><h4>Good design is unobtrusive</h4><p>디자인은 도구다. 자기 주장이 강한 디자인은 사용자의 표현 공간을 침범한다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 06</div><h4>Good design is honest</h4><p>다크 패턴, 과장된 애니메이션, 허위 긴급성 — 정직하지 않은 디자인은 신뢰를 깎는다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 07</div><h4>Good design is long-lasting</h4><p>유행을 따르지 마라. 절제된 컬러와 기하학적 레이아웃은 시간이 지나도 우아하다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 08</div><h4>Good design is thorough down to the last detail</h4><p>4px의 패딩, 0.1초의 애니메이션 — 디테일에 대한 집착이 품질을 만든다.</p></div>

<div class="principle-card"><div class="principle-num">Principle 09</div><h4>Good design is environmentally friendly</h4><p>디지털 맥락에선 성능을 의미. 가벼운 것이 좋은 것.</p></div>

<div class="principle-card"><div class="principle-num">Principle 10</div><h4>Good design is as little design as possible</h4><p>제거할 수 있는 모든 것을 제거한 뒤 남는 것이 좋은 디자인이다.</p></div>

## Color

### Grayscale

UI의 90% 이상은 회색으로 구성한다. 색을 절제해야 강조색이 의미를 가진다.

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

### Primary

하나의 강조색만 사용한다. 이것이 브랜드이자 행동 유도(CTA)의 신호다.

<div class="token-grid">
  <div class="token-swatch"><div class="swatch" style="background:#E1F0FF;"></div><div class="label"><span class="name">primary-light</span><span class="value">#E1F0FF</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#0071E3;"></div><div class="label"><span class="name">primary</span><span class="value">#0071E3</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#0077ED;"></div><div class="label"><span class="name">hover</span><span class="value">#0077ED</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#006EDB;"></div><div class="label"><span class="name">active</span><span class="value">#006EDB</span></div></div>
</div>

### Semantic

상태를 나타내는 색상. 전 세계적으로 통용되는 의미를 따른다.

<div class="token-grid">
  <div class="token-swatch"><div class="swatch" style="background:#30D158;"></div><div class="label"><span class="name">success</span><span class="value">#30D158</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FFD60A;"></div><div class="label"><span class="name">warning</span><span class="value">#FFD60A</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#FF453A;"></div><div class="label"><span class="name">error</span><span class="value">#FF453A</span></div></div>
  <div class="token-swatch"><div class="swatch" style="background:#64D2FF;"></div><div class="label"><span class="name">info</span><span class="value">#64D2FF</span></div></div>
</div>

### 사용 규칙

- 배경은 White 또는 Gray 50~100
- 본문은 Gray 900 (라이트) / Gray 100 (다크)
- 보조 텍스트는 Gray 600 / Gray 400
- Primary는 CTA, 링크, 활성 상태에만
- 색상만으로 정보 전달 ❌ (아이콘·텍스트 병행)
- WCAG 2.1 AA 대비 (텍스트 4.5:1, UI 3:1)

## Typography

타이포그래피는 디자인의 90%다. 인터페이스 대부분은 텍스트이므로, 글꼴·크기·행간이 전체 품질을 좌우한다.

### Type Scale

Major Third(1.250) 비율 기반.

<div class="demo-box">
  <div style="font-size:3rem;font-weight:700;letter-spacing:-0.022em;line-height:1.15;">Display</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-5xl / 48px / Bold</div>

  <div style="font-size:2.25rem;font-weight:600;letter-spacing:-0.022em;line-height:1.2;">Heading 1</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-4xl / 36px / Semibold</div>

  <div style="font-size:1.875rem;font-weight:600;line-height:1.25;">Heading 2</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-3xl / 30px / Semibold</div>

  <div style="font-size:1.5rem;font-weight:600;line-height:1.3;">Heading 3</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-2xl / 24px / Semibold</div>

  <div style="font-size:1.125rem;line-height:1.5;">Body Large — 본문이 길 때 사용. 블로그 포스트나 설명 페이지에 적합.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-lg / 18px / Regular</div>

  <div style="font-size:1rem;line-height:1.5;">Body — 기본 본문 크기. 대부분의 UI 텍스트에 사용.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-base / 16px / Regular</div>

  <div style="font-size:0.875rem;line-height:1.5;color:var(--text-secondary);">Small — 보조 정보, 캡션, 메타 데이터.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;margin-bottom:var(--space-5);">text-sm / 14px / Regular</div>

  <div style="font-size:0.75rem;line-height:1.5;color:var(--text-tertiary);">XS — 라벨, 배지, 타임스탬프.</div>
  <div style="font-family:var(--font-mono);font-size:var(--text-xs);color:var(--text-tertiary);margin-top:4px;">text-xs / 12px / Regular</div>
</div>

### Font Stack

```
--font-sans: -apple-system, BlinkMacSystemFont, 'Apple SD Gothic Neo',
             'Pretendard Variable', Pretendard, 'Noto Sans KR',
             system-ui, sans-serif;

--font-mono: 'SF Mono', 'Fira Code', 'Roboto Mono', monospace;
```

시스템 폰트 우선. 한글은 OS의 폰트를 신뢰한다 (Pretendard / Apple SD Gothic Neo). 웹 폰트 다운로드 비용 ❌.

### 규칙

- **본문 최소 16px**. 모바일에서도 14px 이하 ❌
- **줄 길이 45~75자** (한글 25~40자)
- **행간**: 본문 1.5, 헤딩 1.2~1.3
- **굵기**: Regular(400) + Semibold(600) 두 가지면 충분
- **자간**: 큰 글씨는 약간 좁게(-0.022em), 본문은 기본

## Spacing

8px 그리드. 모든 간격은 8의 배수.

<div class="demo-box">
  <div class="spacing-demo">
    <div class="spacing-item"><div class="spacing-block" style="width:16px;height:16px;">4</div><div class="meta">space-1</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:24px;height:24px;">8</div><div class="meta">space-2</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:32px;height:32px;">12</div><div class="meta">space-3</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:40px;height:40px;">16</div><div class="meta">space-4</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:56px;height:56px;">24</div><div class="meta">space-6</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:72px;height:72px;">32</div><div class="meta">space-8</div></div>
    <div class="spacing-item"><div class="spacing-block" style="width:96px;height:96px;">48</div><div class="meta">space-12</div></div>
  </div>
</div>

### 사용 가이드

| 용도 | Token | 값 |
|---|---|---|
| 인라인 요소 사이 (아이콘-텍스트) | `space-2` | 8px |
| 라벨-인풋, 관련 요소 | `space-2~3` | 8~12px |
| 컴포넌트 내부 패딩 | `space-4~6` | 16~24px |
| 컴포넌트 사이 | `space-6~8` | 24~32px |
| 섹션 사이 | `space-16~24` | 64~96px |
| 페이지 상하 여백 | `space-16~32` | 64~128px |

의심스러우면 늘려라. 줄어든 여백은 답답함을 만든다.

## Components

### Buttons

페이지당 Primary는 1개. CTA가 둘이면 둘 다 약해진다.

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
<button class="btn btn-secondary btn-lg">Large Secondary</button>
```

### Inputs

<div class="demo-box">
  <div class="input-group" style="margin-bottom:var(--space-5);">
    <label class="input-label">이메일</label>
    <input class="input-field" type="email" placeholder="name@example.com">
    <span class="input-hint">로그인에 사용됩니다.</span>
  </div>
  <div class="input-group" style="margin-bottom:var(--space-5);">
    <label class="input-label">비밀번호</label>
    <input class="input-field input-error" type="password" value="abc">
    <span class="input-hint error">비밀번호는 8자 이상이어야 합니다.</span>
  </div>
  <div class="input-group">
    <label class="input-label">메모</label>
    <textarea class="textarea-field" placeholder="자유롭게 입력..."></textarea>
  </div>
</div>

### Toggle

<div class="demo-box">
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

### Card

<div class="demo-box">
  <div class="card card-interactive" style="max-width:320px;">
    <div class="card-image"></div>
    <div class="card-body">
      <h4>Card Title</h4>
      <p>호버하면 살짝 떠오르는 인터랙티브 카드. 클릭 가능한 콘텐츠를 담는 기본 단위.</p>
    </div>
  </div>
</div>

### Badge

<div class="demo-box">
  <div class="demo-row">
    <span class="badge badge-default">Default</span>
    <span class="badge badge-primary">Primary</span>
    <span class="badge badge-success">Success</span>
    <span class="badge badge-warning">Warning</span>
    <span class="badge badge-error">Error</span>
  </div>
</div>

### Alert

<div class="demo-box">
  <div class="alert alert-info">정보를 안내할 때 사용합니다.</div>
  <div class="alert alert-success">작업이 성공적으로 완료되었습니다.</div>
  <div class="alert alert-warning">신중한 진행이 필요합니다.</div>
  <div class="alert alert-error">오류가 발생했습니다. 다시 시도해주세요.</div>
</div>

### Avatar

<div class="demo-box">
  <div class="demo-row">
    <div class="avatar avatar-sm">S</div>
    <div class="avatar">M</div>
    <div class="avatar avatar-lg">L</div>
  </div>
</div>

### Tabs

<div class="demo-box">
  <div class="tabs">
    <button class="tab active">개요</button>
    <button class="tab">상세</button>
    <button class="tab">댓글</button>
  </div>
</div>

### Modal

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

### Progress & Skeleton

<div class="demo-box">
  <div class="progress"><div class="progress-bar" style="width:35%;"></div></div>
  <div class="progress"><div class="progress-bar" style="width:72%;"></div></div>
  <div style="margin-top:var(--space-5);">
    <div class="skeleton" style="height:16px;width:60%;margin-bottom:var(--space-2);"></div>
    <div class="skeleton" style="height:16px;width:80%;margin-bottom:var(--space-2);"></div>
    <div class="skeleton" style="height:16px;width:40%;"></div>
  </div>
</div>

## Border Radius

| Token | Value | 용도 |
|---|---|---|
| `radius-sm` | 6px | input, code chip |
| `radius-md` | 8px | tag, badge |
| `radius-lg` | 12px | card, panel (default) |
| `radius-xl` | 16px | feature card |
| `radius-full` | 9999px | button (pill), avatar |

직각은 거의 안 쓴다. 부드러움이 친근함을 만든다.

## Shadows

<div class="demo-box">
  <div class="shadow-demo-grid">
    <div class="shadow-box" style="box-shadow:var(--shadow-sm);">shadow-sm</div>
    <div class="shadow-box" style="box-shadow:var(--shadow-md);">shadow-md</div>
    <div class="shadow-box" style="box-shadow:var(--shadow-lg);">shadow-lg</div>
  </div>
</div>

다크 모드에서는 그림자 대신 *border 강조*와 *더 진한 배경 단계*로 깊이를 표현한다.

## Motion

| Token | Duration | 용도 |
|---|---|---|
| `duration-fast` | 120ms | hover, tap (마이크로) |
| `duration-normal` | 200ms | 토글, 드롭다운 |
| `duration-slow` | 350ms | 모달, 페이지 전환 |

300ms를 넘으면 사용자가 "느리다"고 느낀다. `prefers-reduced-motion`을 *반드시* 지원해야 한다.

## Dark Mode

`[data-theme="dark"]` 셀렉터로 토큰을 재정의한다. 핵심 변화 셋:

1. 배경은 `gray-900`. **순수 검정 ❌** — OLED 외엔 부담만 된다
2. Primary 컬러를 약간 더 밝게 (`#0071E3` → `#2997FF`)
3. 그림자 알파값을 강하게 (어두운 배경에서 보이도록)

토글은 OS 시스템 설정을 우선 따르고, 사용자가 명시적으로 바꾸면 `localStorage`에 저장. 이 페이지의 우하단 토글로 직접 시험해볼 수 있다.

## Responsive

Mobile first. `min-width` 미디어 쿼리만 사용.

| Breakpoint | Min Width | 용도 |
|---|---|---|
| `sm` | 640px | 큰 폰 |
| `md` | 768px | 태블릿 |
| `lg` | 1024px | 데스크톱 |
| `xl` | 1280px | 큰 데스크톱 |

`px` 대신 `rem`을 쓴다. 사용자가 글자 크기를 키우면 레이아웃도 같이 적응한다.

## Accessibility

- WCAG 2.1 AA 대비 (텍스트 4.5:1, UI 3:1)
- 시맨틱 HTML (`<button>`, `<nav>`, `<article>` 등)
- `:focus-visible` 명시적 outline
- 터치 타깃 최소 44px
- `prefers-reduced-motion` 지원
- 색상만으로 정보 전달 ❌

## 결정 로그

- **순수 검정 X** — OLED만 빼면 모든 화면에서 부담스럽다. `gray-900`이 적정선.
- **시스템 폰트 우선** — 웹폰트 로딩 시간 + FOIT/FOUT 트레이드오프가 너무 크다. 한글은 OS가 잘 처리한다.
- **버튼은 pill** — 기능적 사각이 아닌, *친근함*을 표현하는 둥근 형태. iOS 기조와 일치.
- **Semantic 토큰 한 단계 더** — `--bg-primary`, `--text-secondary` 같이 의미 단위로 한 번 더 매핑. raw color 직접 사용 ❌. 다크 모드 시 한 줄 전환.
- **이 페이지가 곧 컴포넌트 데모** — 위에서 본 Button·Card·Alert는 모두 *지금 작동하는* 컴포넌트. 가이드와 코드의 거리를 0으로.

---

> 디자인 시스템은 한 번 만들고 끝이 아니다. 쓰면서 발견한 빈 곳을 메우고, 안 쓰는 토큰을 지운다. 살아있는 문서.
