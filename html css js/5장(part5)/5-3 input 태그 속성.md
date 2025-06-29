input 태그의 속성
===

autofocus 속성
---

autofocus속성을 사용하면 페이지를 불러오자마자 폼에서 원하는 요소에 입력 커서를 놓을 수 있습니다.

예전에는 이 기능 이용시 js도 사용해야 됐었지만, 최신 HTML에서는 이 속성으로 해결가능


placeholder 속성
---

사용자가 텍스트를 입력할 때 입력란에 적당한 힌트 내용을 표시해 주고 그 필드를 클릭하면 내용이 사라지도록 만들 수 있다.

텍스트 필드 앞에 제목을 사용하지 않고도 사용자에게 해당 필드에 어떤 내용을 입력해야 할지 알려 줄 수 있어서 편리합니다.

![image](https://github.com/user-attachments/assets/8ba18b6e-d82e-43a7-b155-c63e991fa32d)

아이디와 비밀먼호 입력란에 써져있는 내용이 placeholder를 이용한 것이다.

예시
---

         <label for="user-name">이름</label>
         <input type="text" id="user-name" autofocus>

         <label for="phone">연락처</label>
         <input type="tel" id="phone" placeholder="하이픈 빼고 입력해 주세요.">


![image](https://github.com/user-attachments/assets/2e656411-3b65-4888-bda6-72c6c3b5671e)


readonly속성
---

readonly속성은 해당 필드를 읽기 전용으로 바꾼다.

텍스트 필드나 텍스트 영역에 내용이 표시되어 있어도 사용자는 그 내용을 볼 수만 있고 입력은 할 수 없습니다.

readonly="readonly" or readonly="true"로 지정합니다.


required 속성
===

폼에 내용을 입력한 후 submit 버튼을 클릭하면 서버로 폼을 전송하는데, 이때 필수 필드에 필요한 내용이 모두 채워졌느지 검사해야 합니다.

이렇게 반드시 입력해야되는 required 속성을 지정해 필수 필드로 만들 수 있다.

required="required"라고 지정하거나 required라고 해도 된다.

예 readonly, required 사용
---

                        <ul id="shipping">
                          <li>
                            <label for="prod">주문 상품</label>
                            <input type="text" id="prod" value="상품용 3KG" readonly><!-- readonly로 주문상품을읽기전용으로 변경 -->
                          </li>
                          <li>
                            <label for="user-name">이름 </label>
                            <input type="text" id="user-name" autofocus required><!-- required 속성으로 필수 입력란으로 변경 -->
                          </li>
                          <li>
                            <label for="addr">배송 주소</label> 
                            <input type="text" id="addr" required><!-- required 속성으로 필수 입력란으로 변경 -->
                          </li>
                          <li>
                            <label for="mail">이메일</label>
                            <input type="email" id="mail">
                          </li>        
                          <li>
                            <label for="phone">연락처</label>
                            <input type="tel" id="phone" placeholder="하이픈 빼고 입력해 주세요.(01012345678)" required>
                          </li>
                          <li>
                            <label for="d-day">배송 지정</label>
                            <input type="date" id="d-day"> <small>(주문일로부터 최소 3일 이후)</small>
                          </li>        
                        </ul>  



![image](https://github.com/user-attachments/assets/ea267f18-a965-4c18-b638-871157d2de83)


checked 속성
---

<input> 태그의 checked 속성은 페이지가 로드될 때 미리 선택될 <input> 요소를 명시합니다.

checked 속성은 페이지가 로드된 후에도 자바스크립트를 사용하여 설정할 수 있습니다.

checked 속성은 불리언(boolean) 속성입니다.

불리언 속성은 해당 속성을 명시하지 않으면 속성값이 자동으로 false 값을 가지게 되며, 명시하면 자동으로 true 값을 가지게 됩니다.

이 속성은 <input> 요소의 type 속성값이 “checkbox” 또는 “radio”인 경우에만 사용할 수 있습니다.






참고자료
---

https://www.tcpschool.com/html-tag-attrs/input-checked
