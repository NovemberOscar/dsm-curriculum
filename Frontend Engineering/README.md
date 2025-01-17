# 목차

- [개요](#개요)

- [소개](#소개)
- [커리큘럼](#커리큘럼)
- [끝으로](#끝으로)

# 개요

 현재 실생활에서 가장 많이 사용되는 전자기기는 컴퓨터와 스마트폰이라하여도 과언이 아닐겁니다. 그만큼 사람들에게 익숙하며, 편리하고, 유용합니다.  하지만 컴퓨터와 스마트폰이 기기 자체로만 존재했다면 과연 이러하게 사용되었을까요? 이를 뒷받침 해주는데에는 여러 프로그램들이 있지만 사람과 사람을 연결해주는 웹이 단언 최고의 프로그램이라고 생각하게 됩니다. 저희는 웹 프론트엔드 개발자로 웹 중에서 UI와 반응형 웹은 물론 백엔드 API에서 가져온 데이터를 가공하고 이를 제공함으로써 사용자와 직접적으로 연결하여 주는 역할을 하고 있습니다. 그럼, 이제 우리 한번 프론트엔드를 배워봅시다.

# 소개

 웹 프론트엔드는 다음 주 기술들을 사용합니다.

- HTML
- CSS
- JS

사실 이 3개의 기술만 알아도 웹 프론트엔드 개발에는 크게 문제가 없습니다.

하지만 생산성과 효율, 그리고 퍼포먼스를 고려하여 프레임워크들이 생겨났고 많고 많은 프레임워크들 중에 크게 3개의 프레임워크가 떠오르게 됩니다.

- [Angular](https://angular.io/)
- [React.js](https://ko.reactjs.org/)
- [Vue.js](https://kr.vuejs.org/v2/guide/index.html)

저희는 이 3개의 프레임워크 중 React.js를 다루고 있으며 따라서 이를 어떻게 공부했느냐를 중점으로 커리큘럼을 제공하고자 합니다.

# 커리큘럼

### HTML

저희는 HTML을 이렇게 배웠습니다!

- <https://www.w3schools.com/html/default.asp>
- <https://ko.khanacademy.org/computing/computer-programming/html-css>

HTML5의 태그들은 너무나도 많습니다. 저 두 사이트를 공부하면서 전부 익히지 못할 수 있습니다. 저희도 그렇습니다. 저희는 좋은 검색엔진이 있습니다. 바로 구글입니다. HTML5의 태그들을 전부 익힐 수 있다면 좋겠지만, 그것은 사실상 불가능하니 저희는 구글을 이용해서 필요한 태그들을 찾아보고 그때마다 익혀나가는 것이 바름직한 길입니다.

### HTML 심화

js와 HTML을 연동하여 DOM을 조작합니다. DOM을 조작하여 제작한 HTML  Tag에 더 많은 기능과 역할을 부여 할 수 있습니다.

- [https://developer.mozilla.org/ko/docs/Web/API/Document_Object_Model/%EC%86%8C%EA%B0%9C](https://developer.mozilla.org/ko/docs/Web/API/Document_Object_Model/소개)

또한 장애인들의 시선으로 바라볼때, 어떻게 코드를 작성하면 좀 더 쉽고 거부감 없이 다가갈 수 있을지 생각해보세요.

- 웹 접근성
- 웹 표준

훌륭한 개발자가 되기 위해선 `Google`을 이용하는 방법을 익혀야 합니다. 구글링을 통해 많은 정보를 얻으시면 됩니다.

#### CSS

저희는 CSS를 이렇게 배웠습니다!

- <https://ko.khanacademy.org/computing/computer-programming/html-css>
- <https://www.w3schools.com/css/default.asp>
- <http://flexboxfroggy.com/#ko>

CSS도 너무 많습니다. 웹 브라우저에 따라 작동하지 않는 것도 있고, 모든 웹 브라우저에서 잘 작동하는 것도 있습니다. 크로스 브라우징을 위해서 이런 것들을 고려할 필요가 있습니다. 사실 개인적으로 CSS가 제일 어렵습니다.  원하는 대로 결과를 내기까지 고혈압을 느낄 수 있습니다. 하지만 우리는 참아야합니다.

CSS도 너무 많은 만큼 전부 익혀서 하긴 힘들 겁니다. 필요한 것을 그때마다 찾아서 익혀나가는 습관을 기릅시다.

### CSS 심화

- [css모듈](#css모듈)
- [css in js](#css_in_js)
- [css 플러그인](#css_플러그인)
- [css방법론](#css방법론)

CSS를 어느정도 익혀다 싶으면, CSS에 불편함에 찌들어 있을 것 입니다. CSS를 사용하며 for문을 돌거나, if문, 변수등을 사용할 수 있다면 얼마나 좋을까요?

그래서 등장했습니다. 더 강하고 편해진 CSS가 나왔습니다.

#### CSS 전처리기(CSS preprocessor)

- Sass
- Scss

<https://sass-lang.com/>

위 링크를 참고하세요.

#### css_in_js

코딩을 하다보면 캡슐화나, 가독성 때문에 한 파일로 작성된 코드를 각자의 역할에 맞춰 여러 개의 파일로 나누게 됩니다. CSS도 마찬가지 입니다. 만약 CSS파일이 200개가 넘는다면, 웹 브라우저가 하나의 웹페이지를 로딩할 때 200개에 해당하는 모든 파일들을 가져와야 합니다. 생각해보세요, 얼마나 무거울까요?

그리고 CSS와 js의 유연한 연결을 해야 하는데 CSS와 js를 따로 관리해야 하는 불편함을 해결하기 위해 css in js가 등장했습니다.

- [Styled-components](https://www.styled-components.com)
- [Jss](https://cssinjs.org)

위 링크를 참고하세요.

#### css_플러그인

sass를 사용하고, css in js를 사용하면 모르겠으나... (물론 어떠한 경우든 플러그인은 작동합니다.) 만약 순수 CSS를 사용해 개발을 하고 계시다면, 많은 불편함이 있을 것 입니다. 예를 들면 브라우저별 호환성을 생각하며 코딩을 할 경우에, 브라우저 호환성을 위한 브라우저 프리픽스를 적기 위해 매우 많은 라인 (--webkit--, 등..) 을 추가하여 적어야 합니다. 매우 귀찮은 일입니다. 이를 해결하기 위해 css플러그인이 등장했습니다.

- [postCss](https://github.com/postcss/postcss)

위 링크를 참고하세요.

#### CSS 방법론

CSS의 선택자를 명명하다보면, 이름이 겹치고, 뒤죽박죽으로 적히는 경우가 있습니다. 이를 해결하기 위해 CSS 방법론이 나타났습니다. 약 10년동안 쭉 CSS 방법론의 1등을 달려온 `BEM`방법론을 소개해드리겠습니다.

- BEM

[https://medium.com/witinweb/css-%EB%B0%A9%EB%B2%95%EB%A1%A0-1-bem-block-element-modifier-1c03034e65a1](https://medium.com/witinweb/css-방법론-1-bem-block-element-modifier-1c03034e65a1)

위 링크를 참고하세요.

### JS

저희는 JS를 이렇게 배웠습니다!

- [인사이드 자바스크립트](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788968480652&orderClick=LEB&Kc=)
- [러닝 자바스크립트](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788968483387&orderClick=LEB&Kc=)
- <https://poiemaweb.com/coding/>
- [자바스크립트 완벽가이드](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788968483387&orderClick=LEA&Kc=)

JS는 참으로 특별한 언어입니다. 설계를 7일만에 끝냈다는 말도 있고, 작동 방식이 이상하다는 말도 있습니다. 하지만 저희는 알아야합니다. 기초 문법 자체는 그렇게 어렵지 않으나, ES6 문법 부터는 좀 괴리감이 생길 수 있으니 조심하셔야 합니다.

자바스크립트 완벽가이드는 책이 두꺼워 다소 거부감이 들 수 있지만, 자바스크립트의 교과서라고 할 수 있을 만큼 좋은 책입니다. 한번씩은 읽어 보세요.

역시 자바스크립트 또한 구글의 도움을 필요로 합니다. 자바스크립트의 문법과 작동 원리가 연관성이 있기 때문입니다.

HTMl, CSS, JS까지 모두 배웠다면 이제 직접 개발해 볼 차례입니다. 현재 프론트엔드 개발에서 가장 인기있는 라이브러리인 React.js를 소개합니다.

### React.js

우리가 React.js를 선택한 이유는 정말 많습니다. 그 중에 3가지만 골라봅시다.

1. 개발 생태계가 크다. => 개발하다가 문제가 생겼을 때, 해결하기 쉽다. + 계속해서 라이브러리가 새롭게 개발된다.
2. 정말 인기있는 라이브러리다 (사용하는 사람이 많다.) => 개발하다가 문제가 생겼을 때, 해결하기 쉽다.
3. virtual DOM을 사용한다. => 일반적인 js만을 가지고 dom을 조작하는 것 보다 빠르다.

개인적으로 HTML, CSS, JS를 모두 익히고 React.js를 공부할 필요는 없다고 생각합니다. 어느정도 공부가 되었다 인지하였을 때는 React.js를 하셔도 될 때입니다.

절대로 모두 마스터 한 후 프레임워크, 라이브러리를 공부한다고 생각하지 마십시오. 언제나 부족하기 마련입니다.

- Learning React

- 리액트를 다루는 기술
- <http://velopert.com>

구글과 이 책에서 큰 도움을 얻었습니다. 꼭 읽어보시고  React.js의 마스터가 되시길 바랍니다.



# 끝으로

프론트엔드는 진입장벽이 그렇게 높은 편이 아닙니다. 여러분들도 할 수 있습니다. 남은 건 여러분들의 의지입니다. 좋은 프론트엔드 개발자가 되시길 바랍니다. 감사합니다. 

