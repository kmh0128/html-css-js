html_12_정리
====

참고자료
---
https://velog.io/@dongeranguk/input-%ED%83%9C%EA%B7%B8-id%EC%99%80-name%EC%9D%98-%EC%B0%A8%EC%9D%B4

https://wikidocs.net/287996

https://www.youtube.com/watch?v=phiSW6Pr-gg&list=LL&index=12&t=3768s

input 태그
----

 HTML에서 가장 강력한 태그 중 하나이며, 이 태그 하나로 텍스트, 비밀번호, 이메일, 숫자 등 다양한 입력을 받을 수 있다.

type="text"는 가장 기본이 되는 텍스트 입력창



    <form>
        <input type="text">
    </form>

텍스트를 입력받는데 사용된다.


    form>
        <label for="name">제목</label>
        <input type="text" id="name" name="name">
    </form>
    
label for="" -> 어떤것을 위한 label이냐라는 뜻

input 태그를 위한 label이다.

for 안에다 id명을 기입

속성
---

- placeholder: 입력 힌트 표시
- 
- maxlength: 최대 입력 글자 수 제한
- 
- required: 필수 입력 항목 지정
- 
- size: 입력창의 크기 조절
- 
- value: 기본값 설정
- 
- readonly: 읽기 전용 (수정 불가)

비밀번호 입력 필드
---

input type="password"를 사용하면 사용자가 입력하는 비밀번호 (●)이나 별표(*)로 표시된다.

숨겨진 입력 필드(input type="hidden")는 사용자에게는 전혀 보이지 않지만 폼이 전송될 때 함께 서버로 보내지는 정보입니다.

예를 들어, 어떤 페이지에서 폼을 작성했는지, 현재 로그인한 사용자의 ID는 무엇인지 같은 뒤에서 필요한 정보들을 담아둡니다.

