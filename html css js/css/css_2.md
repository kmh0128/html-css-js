텍스트를 표현하는 스타일
===



글꼴을 지정하는 font-family 속성
---

font-family:<글꼴 이름>

    body {
        font-family: "맑은고딕", "Times New Roman", serif;
    }

"맑은고딕", "Times New Roman"은 특정 폰트를 지칭하지만 serif는 삐침 있는 명조계열 글꼴 모음을 의미합니다. 

serif, sans-serif, cursive, monospace 등을 generic-family라고 부르는데, 시스템 폰트 중에서 사용자가 의도한 스타일과 유사한 서체를 알아서 선택해서 사용하라고 할 때 사용합니다. 


          serif: 삐침 있는 명조계열 글꼴 모음
          
          sans-serif: 삐침 없는 고딕계열 글꼴 모음
          
          cursive: 손 필기체 같은 느낌의 글꼴 모음
          
          monospace: 글자 폭과 간격이 일정한 글꼴 모음

font-size
---


웹 폰트
--

웹 문서에서 사용한 글꼴 정보를 서버에 올려놓고, 사용자가 사이트에 접속하면 웹 문서를 내려 받으면서 웹 폰트도 사용자 시스템으로 내려받는 방식

사용자 시스템에 없는 글꼴이라도 글꼴을 내려받은 후 표시하므로 웹 제작자가 의도한 대로 텍스트를 보여 줄 수 있다.

아이콘 폰트
--

아이콘을 이미지가 아닌 글자형태로 사용할때 명칭한다.



참조자료
--


Do it 한권으로 끝내는 웹 기본 교과서 HTML CSS 자바스크립트  웹 표준의 정석

저자 고경희님  

https://bskyvision.com/entry/css-font-family-%EC%86%8D%EC%84%B1%EC%97%90-%EC%97%AC%EB%9F%AC-%ED%8F%B0%ED%8A%B8-%EB%93%B1%EB%A1%9D%ED%95%98%EC%97%AC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EA%B2%BD%EC%9A%B0-%EC%96%B8%EC%96%B4%EB%B3%84%EB%A1%9C-%ED%8F%B0%ED%8A%B8-%EC%84%A4%EC%A0%95%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95

https://developer.mozilla.org/ko/docs/Learn_web_development/Core/Text_styling/Fundamentals
