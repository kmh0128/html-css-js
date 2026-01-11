label 태그
===

참조자료
---
https://anstrengung-jh.tistory.com/entry/label-%ED%83%9C%EA%B7%B8%EC%99%80-htmlFor

https://batcave.tistory.com/79

label 태그란
---

label 태그사이에 위치한 text, checkbox, radio 등 클릭 가능 영역이 텍스트로 확장됩니다

폼(form) 내부에서 해당 폼의 조작을 담당하는 태그의 이름표로 쓰입니다.

 for 속성을 통해 다른 요소와 결합할 수 있으며, 이때 label 요소의 for속성값은 결합하고자 하는 요소의 id 속성값과 같아야 합니다.

label 태그 사용이유
--

         <input type="text">

input 태그는 셀프-클로징(self-closing) 태그입니다.

셀프-클로징 태그는 다른 HTML 태그와 다르게, 내부에 다른 태그를 넣거나,

텍스트를 삽입할(innerText) 공간이 존재하지 않습니다.

그래서 해당 태그는 그 자신에 대한 정보를 제공하기 힘듭니다.

물론 placeholder  속성을 추가하면, input태그에 정보를 표시할 수 있습니다.

      placeholder 정보: 비밀번호 입력

하지만 이는 type="text"를 비롯한 몇몇 타입에 한정되는 이야기 입니다.

range타입처럼 placeholder를 집어넣을 수 없는 유형도 많이 존재합니다.

라벨을 사용하면 이런 태그에게 명시적으로 용도를 붙여줄 수 있습니다.

