css_정리_4_기본문법
===

참고자료
---

https://tadi-coding.tistory.com/158

https://coding-factory.tistory.com/896

https://velog.io/@jueunyang08/CSS-CSS-%EA%B8%B0%EB%B3%B8-%EC%84%A0%ED%83%9D%EC%9E%90-Selector-%EC%A0%84%EC%B2%B4-%EC%84%A0%ED%83%9D%EC%9E%90-%ED%83%80%EC%9E%85-%EC%84%A0%ED%83%9D%EC%9E%90-%ED%81%B4%EB%9E%98%EC%8A%A4-%EC%84%A0%ED%83%9D%EC%9E%90-id-%EC%84%A0%ED%83%9D%EC%9E%90-%EA%B7%B8%EB%A3%B9-%EC%84%A0%ED%83%9D%EC%9E%90

https://wikidocs.net/298956

https://inpa.tistory.com/entry/CSS-%F0%9F%93%9A-css-%EA%B8%B0%EB%B3%B8-%EB%AC%B8%EB%B2%95-%EC%A0%95%EB%A6%AC

선택자
---

CSS 선택자는 HTML 문서에서 스타일을 적용할 요소를 찾는 방법

주소록에서 특정 사람을 찾는 것처럼, 각각 다른 방식으로 요소를 식별가능

전체 선택자 (*)
---

모든 요소를 선택하는 만능 도구

학교에서  "전교생 집합!"과 같은 방식

                * {
                	color : black;
                }


타입 선택자 (태그명)
----

타입 선택자는 특정 태그를 사용한 모든 요소에 스타일을 적용합니다.

태그의 타입을 대상으로 하는 선택자입니다.

태그 선택자 라고도 합니다.


          tag명{속성 : 속성값;}
          
          tag명1, tag명2{속성 : 속성값;}
          
예시
---

          <h1>태그 선택자</h1>
          
          <h2>태그 선택자</h2> 
          
          <p>태그 선택자</p>
