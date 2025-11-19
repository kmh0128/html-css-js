CSS_2_정리
===

참조 자료
---

https://wikidocs.net/288012

https://inpa.tistory.com/entry/CSS-📚-css-기본-문법-정리#css_선언_방식 [Inpa Dev 👨‍💻:티스토리]

https://abcdqbbq.tistory.com/10

CSS스타일
---

HTML문서에에 CSS를 더하려면 3가지 방법이 있다.

인라인 스타일(Inline Style)
--

HTML 요소(태그)에 직접 style 속성을 사용해 CSS를 적용하는 방식

장점은 즉시 적용되면서 우선순위가 가장 높음

단점 코드가 복잡해지고 재사용이 어려움

내부 스타일시트 (Internal Stylesheet)
--
HTML <style></style> 안에 작성하는 방식

장점은 HTML 파일 전체에 적용 된다.

단점은 다른 HTML 파일에는 사용불가

외부 스타일시트 (External Stylesheet)
--

Link 태그를 사용하여서 외부에 있는 별도의 css 파일을 연결시키는 방법

장점으로는 여러 HTML 파일에 적용가능

단점으로 별도의 파일을 필요로 한다는 점이다.

import사용한 방법
--

@import 방식은 다른 스타일 시트에서 또 다른 스타일을 가져올 때 사용한다.

즉 CSS @import를 이용하여 외부 문서로 CSS를 불러와 적용하는 방식

예를 들면 project.css 라는 파일을 외부 스타일 방식을 적용해서

문서에 적용시킨 후에 해당 css파일 안에 또 다른 css를 불러 오는 방법이다.
