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





