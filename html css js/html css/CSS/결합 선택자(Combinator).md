결합 선택자(Combinator)
====


참고자료
---

https://inpa.tistory.com/entry/CSS-%F0%9F%93%9A-%EC%84%A0%ED%83%9D%EC%9E%90-%EB%AC%B8%EB%B2%95-%EC%A0%95%EB%A6%AC-%EC%8B%AC%ED%99%94#%EA%B8%B0%EB%B3%B8_%EC%84%A0%ED%83%9D%EC%9E%90

https://developer.mozilla.org/ko/docs/Learn_web_development/Core/Styling_basics/Combinators

https://www.youtube.com/watch?v=phiSW6Pr-gg&list=LL&index=45

https://ssocoit.tistory.com/274 [코딩하는 경제학도]

결합 선택자란?
----

다른 선택자를 서로 유용한 관계와 문서의 콘텐츠 위치를 제공하는 방식으로 결합한다.

요소간의 계층 관계를 결합하여 특정 요소나 하위 요소를 선택한다.

결합 선택자의 유형
---

자식 선택자

인접 형제 선택자

일반 형제 선택

속성 선택자

가상 클래스 선택


자손 선택자 (Descendant Selector)
---



자식 선택자(Child selector)
---

자식 선택자(>)는 두 CSS 선택자 사이에 배치됩니다. 

특정 요소의 직계 자식 요소 선택하는데 사용됩니다.


 인접 형제 선택자 (Adjacent Sibling)
 ---

문법적으로는  요소1 + 요소2 이다.

의미: 요소1 바로 다음에 오는 요소2를 선택한다.

("+")는 앞에서 지정한 요소의 바로 다음에 위치하는 형제 요소만 선택하는 결합자

 
일반 형제 선택자 (General Sibling)
---

서로 형제인 요소가 앞 요소 뒷 요소를 전부 선택한다.

문법적: 요소1 ~ 요소2
