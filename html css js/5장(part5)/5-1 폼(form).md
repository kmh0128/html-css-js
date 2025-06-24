폼(form)
===

폼이란
---

HTML에서 폼은 사용자가 데이터를 입력하거나 선택해서 서버로 전송 가능하게 만드는 UI 영역이다.

즉, 회원가입 폼이나 로그인 폼 같은 사용자 <-> 웹서버 사이의 데이터 교환 통로라고 보면 된다.

웹 사이트로 정보를 보낼 수 있는 요소다.

폼의 동작요소
---

사용자가 아이디와 비밀번호를 입력하고 로그인 버튼을 누르면 -> 웹서버로 전송 -> 데이터베이스가 확인하고 그 결과를 웹 브라우저로 보낸다.

폼으로 작동하는것은 대부분 데이터베이스 기반으로 작동한다.

텍스트 박스나 버튼 같은 폼 형태는 HTML 태그로 만들지만 폼에 입력한 사용자 정보는 ASP나 PHP or JSP같은 서버 프로그래밍을 이용해 처리한다.

form 태그
---

폼을 만드는 가장 기본적인 태그

    <form [속성="속성값"]>여러 폼 요소</form>

태그의 속성
---

method -> 사용자가 입력한 내용을 서버 쪽 프로그램으로 어떻게 넘겨줄 것인지 지정

method에서 사용할 수 있는 속성값은 get과 post입니다.

        get -데이터를 256~4096 byte까지만 서버로 넘길수 있다. 주소 표시줄에 사용자가 입력한 내용이 그대로 드러나는 단점이 있다.

        post - 입력한 내용의 길이에 제한받지 않고 사용자가 입력한 내용도 드러내지 않는다.

name -> 자바스크립트로 폼을 제어할 때 사용할 폼의 이름을 지정합니다.

action -> form 태그 안의 내용을 처리해 줄 서버 프로그램을 지정합니다.

target -> action 속성에서 지정한 스크립트 파일을 현재 창이 아닌 다른 위치에서 열도록 합니다.


폼을 서버로 보내기
---

        <form action = "register.php">
            /*여러 폼 요소*/
        </form>    

autocomplete속성
----

폼에서 내용을 입력할 때 예전에 입력한 내용을 자동으로 표시해주는 것이 자동 완성 기능이라 한다.

사용자가 입력한 내용을 기억했다가 비슷한 글자가 입력되면 이전에 입력한 내용을 힌트로 보여준다.

![images (1)](https://github.com/user-attachments/assets/f3ddff6b-73c5-4282-aabc-8c6e1440e9eb)

autocomplete 속성을 사용하면 기본 속성값은 "on"이다.

자동완성기능이 기본으로 켜져 있으므로 예전에 입력한 적 있는 한두 글자 정도 입력하면 자동으로 보여준다.

개인정보나 인증정보는 기능을 사용하지않는 것이 좋다

form 태그의 autocomplete 속성을 off로 지정하면 자동완성 기능을 끌 수 있다.

자동완성 기능 끄기
---

        <form action=""autocomplete = "off">
         여러 폼 요소
        </form> 

fieldset,legend 태그
----

하나의 폼 안에서 여러 구역을 나누어 표시할 때 fieldset 태그를 사용합니다. 

쇼핑몰 사이트에서 주문서를 작성할 때 개인 정보와 배송 정보를 나누어 표시하면 사용자가 입력하기도 편리하고 화면도 깔끔하게 정리 할 수 있다.

legend 태그는 fieldset 태그로 묶은 그룹에 제목으로 붙일수 있다.

        <fieldset>
            <legend>그룹 이름</legend>
        </fieldset>

예제
---

        <form>
            <fieldset>
                <legend>상품 선택</legend>
            </fieldset>
        </form>
        <form>
            <fieldset>
                <legend>배송 정보</legend>
            </fieldset>
        </form>

fieldset 태그와 legend 태그를 사용해서 상품 선택과 배송 정보를 그룹으로 묶은것이다.

![image](https://github.com/user-attachments/assets/063b5c05-ef9b-4e65-9cbd-5022f234913f)

label 태그
---

label 태그는 input 태그와 같은 폼 요소에 레이블을 붙일 때 사용합니다.

레이블(label)이란 입력란 가까이에 표시하는 텍스트를 말한다.

예시1
---

태그 안에 폼요소를 넣는것

        <label>레이블명<input></label>

예시1-2
--

    <form>
        <label>아이디(6자 이상)<inpu type="text"></label>
    </form>

예시2
---

label 태그와 폼 요소를 따로 사용하고 label 태그의 for 속성과 폼 요소의 id 속성을 이용해 서로 연결하는것

폼 요소의 id 속성값을 label 태그의 for 속성에게 알려주는것이다.


        <label for="id명">레이블명</label>
        <input id="id명">

![image](https://github.com/user-attachments/assets/3e721290-cdea-4e51-8b95-06b2702f2f1b)

아이디를 입력하는 폼 요소에 id="user-id"라고 지정한다.

폼 요소에 연결된 label 태그에 for="user-id"라고 입력해 폼 요소와 레이블을 연결한다.

예시2의 장점은 레이블과 사용자 정보를 입력받는 input 태그가 떨어져 있더라도 둘 사이를 쉽게 연결할 수 있다는 장점이 있다.



참조자료
---

https://lold2424.tistory.com/m/260#:~:text=%ED%8F%BC(Form)%EC%9D%B4%EB%9E%80?HTML%EC%97%90%EC%84%9C%20%ED%8F%BC%EC%9D%80%20%EC%82%AC%EC%9A%A9%EC%9E%90%EA%B0%80%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EC%9E%85%EB%A0%A5%ED%95%98%EA%B1%B0%EB%82%98%20%EC%84%A0%ED%83%9D%ED%95%B4%EC%84%9C%20%EC%84%9C%EB%B2%84%EB%A1%9C,%EB%93%B1)%EA%B0%80%20%EB%93%A4%EC%96%B4%EA%B0%84%EB%8B%A4.%EC%82%AC%EC%9A%A9%EC%9E%90%EA%B0%80%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EC%9E%85%EB%A0%A5%ED%95%98%EA%B1%B0%EB%82%98%20%EC%84%A0%ED%83%9D%ED%95%98%EC%97%AC%20%EC%A0%9C%EC%B6%9C(submit)%20%EB%B2%84%ED%8A%BC%EC%9D%84

https://blog.naver.com/s9soft/221483966082?viewType=pc
