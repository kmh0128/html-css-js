Margin, padding
====

참고자료
---

https://www.tcpschool.com/css/css_boxmodel_margins

https://mu-mu-syo.tistory.com/56#:~:text=margin%20%C2%B7%20%EC%9D%8C%EC%88%98%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%A0%20%EC%88%98%20%EC%9E%88%EC%9D%8C%20%C2%B7,vw%20%EB%93%B1%20%EB%8B%A8%EC%9C%84%EB%A1%9C%20%EC%A7%80%EC%A0%95%20%C2%B7%20%25%20:

https://webdir.tistory.com/346


마진(Margin)
---

요소의 외부 여백(공간)을 지정하는 단축 속성

margin 속성은 테두리(border)와 이웃하는 요소 사이의 간격인 마진 영역의 크기를 설정합니다.

이러한 마진 영역은 패딩 영역과는 달리 background-color 속성으로 설정하는 배경색의 영향을 받지 않습니다.

CSS를 사용하면 마진 영역의 크기를 방향별로 따로 설정할 수 있습니다.

<img width="400" height="361" alt="img_css_boxmodel_margin" src="https://github.com/user-attachments/assets/52d44ba2-9fb9-4508-9c7a-a1303cfb7c86" />

음수를 넣을 경우 겹쳐서 나온다 (외부여백이 줄어든다)


마진(margin) 속성
---

margin은	모든 margin 속성을 이용한 스타일을 한 줄에 설정할 수 있음.

1. margin-top 윗쪽의 마진(margin) 값을 설정함.

2. margin-right 오른쪽의 마진(margin) 값을 설정함.

3. margin-bottom 	아래쪽의 마진(margin) 값을 설정함.

4. margin-left 왼쪽의 마진(margin) 값을 설정함.


padding
---

요소의 내부 여백(공간)을 지정하는 단축 속성 (요소의 크기가 커짐)

0 : 내부 여백이 없음

단위 : px, em, vm 등 단위로 지정

% : 부모 요소의 가로 너비에 대한 비율로 지정

padding 속성값
---

length(길이) : 패딩을 부동 소수점 숫자 뒤에 절대 단위 지정자( cm , mm , in , pt , pc ) 또는 상대 단위 지정자( em , ex , px )가 오는 값을 지정한다. 기본값은 0px이다.

%(퍼센트) : 패딩을 퍼센트로 폭을 적용한다.

inherit : 부모 요소로부터 값을 상속 받는다.

padding-bottom, padding-top, padding-left, padding-right으로 사용가능

0px : (상하좌우 다 적용)

10px 20px : (top, bottom) (left right) ⇒ 세로 가로

10px 20px 30px : (top) (left right) (bottom) ⇒ 상 중 하

10px 20px 30px 40px : (top, right, bottom, left) 순으로 작성 ⇒ 시계방향

