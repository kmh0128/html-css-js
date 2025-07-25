input태그
====

input 태그란?
----

<input> 태그는 사용자로부터 입력을 받을 수 있는 입력 필드(input filed)를 정의할 때 사용합니다.

 
<input> 요소는 사용자가 데이터를 입력할 수 있는 입력 필드를 선언하기 위해 <form> 요소 내부에서 사용됩니다.

이러한 입력 필드는 <input> 요소의 type 속성값을 달리함으로써 여러 가지 모양으로 나타낼 수 있습니다.

 
<input> 요소는 빈 태그(empty tag)이며, 속성만을 포함하고 있습니다.

<label> 요소를 사용하면 <input> 요소의 라벨(label)을 정의할 수도 있습니다.

웹 폼의 input 태그
---

웹 사이트에서는 회원가입이나 로그인 퐈면은 폼을 사용해 작성한것이다.

![image](https://github.com/user-attachments/assets/393d7828-65e5-4f06-8ffc-8dd5c8ef6410)

네이버 검색창 input 태그 확인 

다양한 폼에서 사용자가 입력한 정보를 받을 때 사용한다는 것이다.

input 태그의 type 속성
---

       text -> 한 줄짜리 텍스트를 입력할 수 있는 텍스트 박스를 넣습니다.(기본값)
       
       password -> 비밀번호를 입력할 수 있는 필드를 넣습니다.
       
       search -> 검색할 때 입력하는 필드를 넣습니다.
       
       url -> URL 주소를 입력할 수 있는 필드를 넣습니다.
       
       email -> 이메일 주소를 입력할 수 있는 필드를 넣습니다.
       
       tel -> 전화번호를 입력할 수 있는 필드를 넣습니다.
       
       checkbox -> 주어진 여러 항목에서 2개 이상 선택할 수 있는 체크박스를 넣는다.
       
       radio -> 주어진 여러 항목에서 1개만 선택할 수 있는 라디오 버튼을 넣습니다.
       
       number -> 수량 숫자를 조절할 수 있는 스핀 박스를 넣습니다.
       
       range -> 크기 숫자를 조절할 수 있는 슬라이드 막대를 넣습니다.
       
       date -> 사용자 지역을 기준으로 날짜(연, 월, 일)를 넣습니다.
       
       month -> 사용자 지역을 기준으로 날짜(연, 월)을 넣습니다.
       
       week -> 사용자 지역을 기준으로 날짜(연, 주)를 넣습니다.
       
       time -> 사용자 지역을 기준으로 시간(시, 분, 초, 분할 초)를 넣습니다.
       
       datetime-local -> 사용자가 있는 지역을 기준으로 날짜와 시간(연, 월, 일, 시, 분, 초, 분할 초)를 넣습니다.
       
       submit -> 전송버튼을 넣습니다.
       
       reset -> 리셋버튼을 넣습니다.
       
       image -> submit 버튼 대신 사용할 이미지를 넣습니다.
       
       button -> 일반 버튼을 넣습니다.
       
       file -> 파일을 첨부할 수 있는 버튼을 넣습니다.
       
       hidden -> 사용자에게는 보이지 않지만 서버로 넘겨주는 값이 있는 필드를 만듭니다.

텍스트와 비밀번호를 나타내는 type="text"와 type="password"
---

텍스트 필드는 폼에서 가장 많이 사용하는 요소입니다.

주로 아이디나 이름 주소 등 한 줄 짜리 일반 텍스트를 입력할 때 사용합니다.

비밀번호 필드는 입력하는 내용을 화면에 보여주지 않아야 하므로 '*'나 ●로 표시한다.

이 점을 제외하면 텍스트 필드와 똑같이 작동하고 같은 속성을 사용한다.

  <input type="text">
  <input type="password>

텍스트 필드와 비밀번호 필드 속성표
---

      size: 텍스트와 비밀번호 필드의 길이를 지정한다.
      
      화면에 몇 글자가 보이도록 할 것인지 지정한다.
      
      최대로 입력할 수 있는 글자 수가 10개인데 size 속성값을 5로 지정하면 필드크기는 5개 글자 크기에 맞추고 나머지 5개 글자는 화면에 보이지 않는다.
      
      value: 텍스트 필드 요소가 화면에 표시될 때 텍스트 필드 부분에 보여 주는 내용입니다.
      
      이 속성을 사용하지 않으면 빈 텍스트 필드가 표시됩니다.
      
      비밀번호 필드에서는 사용하지 않는 속성입니다.
      
      maxlength: 텍스트 필드와 비밀번호 필드에 입력할 수 있는 최대 문자 수를 지정합니다.

예
---

   <form>
    <fieldset>
     <label>아이디:<input type="text" id="user_id: size="10"></label>
     <label>비밀번호:<input type="password" id="user_pw" size="10"</label>
      <input type="submit" value="로그인">
    </fieldset>
   </form>

![image](https://github.com/user-attachments/assets/7a7fb93e-5612-4e95-a693-0de6af153eb2)

용도에 맞게 입력하는 search url email tel
---

텍스트 필드는 한 줄짜리 일반 텍스트를 입력할 수 있습니다.

폼을 만들다보면 텍스트 필드를 더 세분해야 할 때가 있습니다.

이 필드들은 텍스트 필드를 기본으로 한다.

text"search" 사용시 웹 브라우저 화면으로 볼때는 텍스트 필드와 같지만 웹 브라우저는 검색을 위한 텍스트 필드로 인식한다.

크롬 or 엣지 브라우저 모바일 기기 웹 브라우저에서는 검색어를 입력하면 오른쪽에 x가 표시되어 입력한 검색어를 손쉽게 지울 수 있다.

type="url" 웹 주소를 입력하는 필드이고 type="email"은 이메일 주소를 입력하는 필드입니다.

이전버전 HTML4에서는 입력한 값을 js로 이메일 주소인지, URL주소인지 확인해야 됐지만 이제는 type="email"처럼 이메일 주소 필드로 지정하기만 하면 

웹 브라우저가 알아서 확인합니다.

입력값이 지정한 형식에 맞지 않는다면 웹 브라우저에서 오류 메시지를 보여준다.

type="tel" 전화번호를 나타내는 필드이다.

전화번호는 지역마다 형식이 달라서 사용자가 입력한 값이 전화본호인지 아닌지 체크할 수 없다.

텍스트 필드에서 헤분화된 필드는 pc용 웹 브라우저 에서는 큰 변화가 없는 것처럼 보이지만, 모바일 기기에서는 이메일조수롤 입력하거나 전화번호를 입력할때

가상 키보드 배열이 바뀌는 것을 볼 수 있다.

예
---

        <ul>
         <li>
           <label for="user-name">이름</label>
           <input type="text" id="user-name">
         </li>
         <li>
           <label for="addr">배송 주소</label>
           <input type="text" id="addr">
         </li>
         <li>
           <label for="mail">이메일</label>
           <input type="email" id="mail">
         </li>
         <li>
           <label for="phone">연락처</label>
           <input type="tel" id="phone">
         </li>
        </ul>

![image](https://github.com/user-attachments/assets/6fc3a206-8c24-4736-b17f-b920c0798723)

checkbox, radio
---

체크 박스와 라디오 버튼은 여러 항목 중에서 원하는 항목을 선택할 때 사용하는 폼 요소

항목을 1개만 선택시 라디오 버튼을 사용 2개 이상 선택시 체크박스를 선택

라디오 버튼은 1개만 선택가능해서 1개를 선택한 상태에서 다른 1개를 선택시 기존 선택된 것이 취소된다.

체크박스는 2개이상 항목을 선택할 수 있다는 점 빼면 라디오와 동일하다.

예시1
---

  <input type="checkbox">
  <input type="radio">

속성
---

      value 선택한 체크 박스나 라디오 버튼을 서버에게 알려 줄 때 넘겨줄 값을 지정한다.
      
      값은 영문이나 숫자여야 한다.
      
      checked 체크 박스나 라디오 버튼의 항목은 처음에 아무것도 선택되지 않은 상태로 화면에 표시되는데,
      
      여러 항목 중에서 기본으로 선택해 놓고 싶은 항목에 사용한다.
      
      속성값은 따로 없다.
      
      name 라디오 버튼과 체크 박스는 하나의 그룹으로 동작하므로 name 속성에서 같은 이름을 사용해 묶습니다.



예2
---


![image](https://github.com/user-attachments/assets/6af22755-b874-4045-a395-87a8755e6d89)


회원 가입 신청 페이지
---

        <form>
          <fieldset>
            <legend>사용자 정보</legend>
            <ul>
              <li>
                <label for="uid">아이디</label>
                <input type="text" id="uid">
              </li>
              <li>
                <label for="umail">이메일</label>
                <input type="email" id="umail">
              </li>
              <li>
                <label for="pwd1">비밀번호</label>
                <input type="password" id="pw1">
              </li>
              <li>
                <label for="pw2">비밀번호 확인</label>
                <input type="password" id="pw2">
              </li>
            </ul>
          </fieldset>
          <fieldset>
            <legend>이벤트와 새로운 소식</legend>
            <input type="radio" name="mailing" id="mailing_y" value="mailing_yes">
            <label for="mailing_y">메일 수신</label>
            <input type="radio" name="mailing" id="mailing_n" value="mailing_no">
            <label for="mailing_n">메일 수신 안 함</label>
          </fieldset>
          <div>
            <input type="submit" value="가입하기">
            <input type="reset" value="취소">
          </div>
        </form>

![image](https://github.com/user-attachments/assets/82183935-229a-45cc-b154-54734b8af273)

숫자 필드를 나타내는 number, range
---

텍스트 필드에 사용자가 숫자를 직접 입력할수도 있다.

type="number"와 type="range"를 사용할 수도 있다.

type="number" 스핀박스를 사용해서 숫자를 입력한다.

type="range" 슬라이드 막대를 사용해서 범위를 입력한다.

상품 개수처럼 정확한 숫자가 필요시는 number

볼륨 조절 막대처럼 숫자가 필요없지만 값을 크거나 작게 변경할때는 range를 사용

  <input type ="number">
  <input type ="range">

number, range 속성
---

  min 필드에 입력할 수 있는 최소값을 지정합니다. 기본 최소값은 0
  
  max 필드에 입력할 수 있는 최대값을 지정합니다. 기본 최대값은 100
  
  step 숫자 간격을 지정할 수 있습니다. 기본은 1
  
  value 필드에 표시할 초기값

예시
---

         <ul>
          <li>
            <label><input type="checkbox" value="s_3">선물용 3kg</label>
            <input type="number" min="0" max="5">개
          </li>
          <li>
            <label><input type="checkbox" value="s_5">선물용 5kg</label>
            <input type="number" min="0" max="3" value="1">개
          </li>
         </ul>

2개의 스핀 박스 최소값으 0 최대값은 5와 3으로 지정

step 속성은 지정하지 않아서 화살표를 누를때마다 1씩 커지거나 작아진다.

두번째 박스는 value="1" 지정해서 초기값 1이 화면에 표시

![image](https://github.com/user-attachments/assets/a340beb6-2006-4536-8be2-2a7467beaeb6)


예시2 슬라이스막대를 사용해 값 조절
---

       <form>
        <input type="range" min="0" max="100" step="1" value="20">
       </form>

최소값과 최대값을 각각 0과 100으로 지정

step =1로 지정해서 슬라이드 막대를 움직일때 마다 1씩 커지거나 작아진다.

날짜 입력을 나타내는 date month week
---

웹 문서나 애플리케이션에 달력을 넣으려면 type="date", type="month", type="week" 와 같은 날짜 관련 속성을 이용한다.


기본 예시
---

         <input type ="date">
         <input type ="month">
         <input type ="week">

![image](https://github.com/user-attachments/assets/f47683f9-e305-4f6e-b10d-57c96e0ac3e8)

![image](https://github.com/user-attachments/assets/545497b4-f92c-4223-af36-eca30ef48c32)

![image](https://github.com/user-attachments/assets/a8d53c2a-f4c6-4ebc-9ccf-20e93ed38453)

시간 입력을 나타내는 time, datetime-local
----

시간을 지정할 때는 type="time"을 사용하고 날짜와 시간을 함께 지정하려면 type="datetime-local"을 사용합니다.

예시
---

      <input type ="time"><!-- 시간 입력 필드는 웹 브라우저마다 겉모습은 조금씩 차이가 있지만  '오전/오후/,'시','분' 으로 나타낸다.  -->
      <input type ="datetime-local"><!-- datetime-local 속성을 사용하면 사용자가 웹 문서를 보고 있는 지역에 맞는 날짜와 시간을 함께 입력할 수 있습니다.  -->


![image](https://github.com/user-attachments/assets/2f47bc4b-890d-4ab2-a3a2-c5d22a00f5ea)

![image](https://github.com/user-attachments/assets/1c6acecc-0a5e-4241-af15-630f84c6b70e)

날짜와 시간의 범위를 지정하는 속성
---

          min,max -> 날짜나 시간의 범위를 제한할 때 사용합니다.
          
          min 속성은 범위의 시작 날짜나 시간을, max 속성은 범위의 마지막 날짜나 시간을 지정합니다.
          
          step -> 스핀 박스의 화살표를 클릭했을 때 증감시킬 크기를 지정합니다.
          
          value 기본적으로 표시할 날짜나 시간을 지정합니다.

예시- 날짜의 범위를 제한하여 입력하기
----

   <input type="date" min="2025-06-27" max="2025-06-29">


![image](https://github.com/user-attachments/assets/4fed88b9-9697-48cb-b3ef-825e05e2741f)

전송 리셋 버튼을 나타내는 submit, reset
---

전송 버튼을 나타내는 submit는 폼에 입력한 정보를 서버로 전송합니다.

정보가 전달되는 곳은 form  태그의 action 속성에서 지정한 프로그램입니다.

반면에 리셋 버튼은 input요소에 입력한 내용을 모두 지우는 역할을 합니다.

그리고 value속성을 사용해서 버튼에 표시할 내용을 지정합니다.


예시 전송버튼 리셋버튼 추가
---

    <input type="submit" value="반품하기">
    <input type="reset" value="취소하기">

![image](https://github.com/user-attachments/assets/09cbd0de-6b27-426b-9690-8db21d7b1c15)

이미지 버튼을 나타내는 type="image"
------

   <input type="image" src="이미지 경로" alt="대체 텍스트">

![image](https://github.com/user-attachments/assets/893b767b-a2f7-4966-abed-9815b156dd13)

  <input type="image" src="images/login.png" alt="로그인">

기본 버튼을 나타내는 type="button"
---

input 태그에서 type="button"을 사용하면 기능이 없는 버튼 형태만 삽입합니다.

주로 버튼을 클릭해서 자바스크립트를 실행할 때 사용 합니다.

value 속성을 사용해 버튼에 표시할 내용을 지정한다.

예시 button을 삽입해 자바스크립트 실행하기
---

   <input type="button" value="공지 창 열기" onclick="window.open('notice.html','_blank', 'width=300,height=400')">

![image](https://github.com/user-attachments/assets/4f2256e6-4980-4b71-b266-b0d6a06ff895)

파일을 첨부할 때 사용하는 type="file"
---

사진이나 문서를 첨부해야 하는 경우가 있다.

type="file"로 지정하면 폼에 파일을 첨부할 수 있습니다.

type="file" 속성을 사용하면 웹 브라우저 화면에 파일선택이나 찾아보기 버튼 등이 표시되는데 이 버튼을 클릭하고 파일을 선택하면 파일이 첨부된다.

예시 파일 첨부 버튼 추가하기
---

![image](https://github.com/user-attachments/assets/c44e8c2c-fcfa-4b65-91df-c93a1d5ae536)


히든필드
---

type="hidden" 히든 필드는 화면의 폼에는 보이지 않지만 사용자가 입력한 정보를 서버로 보낼 때 함꼐 전송되는 요소이다.

사용자에게 굳이 보여 줄 필요는 없지만 관리자가 알아야 하는 정보는 히든 필드로 입력한다.

    <input type="hidden" name="이름" value="서버로 전송할 값">

히든필드는 예를 들면 사용자가 쇼핑몰 사이트에서 로그인하는 정보를 서버로 넘겨준다.

웹 브라우저에서는 히든 필드가 보이지 않으므로 사용자는 그 정보를 알 수 없다.

로그인 버튼을 클릭하면 입력한 정보와 함꼐 히든 필드의 내용이 서버로 함께 전송된다.


참고자료
---
Do it 한권으로 끝내는 웹 교과서 html css js 저자 고경희님

https://www.tcpschool.com/html-tags/input#google_vignette
