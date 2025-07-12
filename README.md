# 사천우주체

[배포처 바로가기](https://www.sacheon.go.kr/intro/01096/05083.web)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SacheonUju`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/SacheonUju.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/SacheonUju.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'SacheonUju';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/SacheonUju-Regular.woff2') format('woff2'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/SacheonUju-Regular.woff') format('woff'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/SacheonUju-Regular.otf') format('opentype'),
      url('https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/SacheonUju-Regular.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/subsets/SacheonUju-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SacheonUju/subsets/SacheonUju-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SacheonUju", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
사천시 전용서체는 누구나 무료로 내려받아 사용할 수 있습니다. 영상, 인쇄, 출판, 웹, 모바일 등 다양한 매체에 개인, 단체 등이 특별한 허가 절차 없이 자유롭게 사용할 수 있습니다. 다만, 사천시 전용서체를 유료로 양도하거나 판매할 수 없으며, 반사회적 목적으로 사용은 금지하고 있습니다.
```
