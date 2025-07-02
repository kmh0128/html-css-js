CSS
===

CSS는 Cascading Style Sheet의 약자이다.

Cascading -> 세부적인정의 된것을 쓰고 거기에 정의된것이 없으면 다음 기본으로 지정된곳으로 넘어간다는뜻

AuthorStyle
---

저자(우리)가 만드는 css 파일이 대표적


UserStyle
---

사용자가 지정 사용자의 취향에 맞게 브라우저에서 스타일을 바꾼다.


Browser
---

브라우저상에서 지정된 기본적인 스타일

Cascading은 우선순위는 일단

AuthorStyle에 지정된것이 없으면 UserStyle로 또한 사용자가 지정한 스타일링이 없다면 브라우저에서 기본으로 지정한 스타일로 넘어간다.

우선순위는 AuthorStyle -> UserStyle -> Browser 순으로 지정되며 이 연결고리를 끊는것이 !important이다.

!important
----

!important는 css 스타일링을 정의시 이것을 쓰게되면 연결고리를 무시하게 되고 자기가 가장중요한 스타일이라고 말한다.


selectors(선택자)
====

HTML의 어떤 태그를 고를건지 규정하는 문법

Universal *
---

모든태그를 선택

type tag
---

tag를 쓰면 tag를 선택 div라고 쓰면 div 태그를 고른다.

ID
---

#id를 사용하면 해당아이디를 고른다.

class
---

.class로 사용

state
---

: 사용

Attribute
---

[]


CSS문법
---

    selector(선택자){ 
     property(속성): value(값); 
    } 


참조자료
--

https://www.youtube.com/watch?v=gGebK7lWnCk&list=PLv2d7VI9OotQ1F92Jp9Ce7ovHEsuRQB3Y&index=5
