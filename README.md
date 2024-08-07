# 김제시체

[배포처 바로가기](https://www.gimje.go.kr/index.gimje?menuCd=DOM_000000102003002001)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `GIMJE`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'GIMJE';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'GIMJE';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/GIMJE-Medium.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/subsets/GIMJE-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/GIMJE/subsets/GIMJE-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "GIMJE", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
1) 개인, 단체 그리고 기업에 상관없이 사용이 가능합니다. 
2) 간판, BI, CI, 현수막, 포스터, 영상, 서적, 전자책, 웹사이트, 상품포장지, 프레젠테이션, 가능합니다. 
3). (앱이나 기기에)임베디드, 원본 글꼴 일부 변형, cid, type3 등- 이는 저희와 라이센스를 해야 가능합니다. 
기타 자세한 것은 담당자 ( 010-2289-5203 송방용 실장)께 문의하세요.
```
