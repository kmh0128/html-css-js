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
