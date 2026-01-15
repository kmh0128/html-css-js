드롭다운(dropdown)
===

참고자료
---

https://codingeverybody.kr/html-select-%ED%83%9C%EA%B7%B8/

https://www.youtube.com/watch?v=phiSW6Pr-gg&t=3817s

https://wikidocs.net/287999

드롭다운(dropdown)이란?
----

사용자에게 여러 옵션중 하나를 드롭다운 선택할때 사용

평소에는 하나의 선택된 값만 보이다가, 클릭하면 여러 선택지가 펼쳐지는 방식

        HTML에서는 <select>와 <option> 태그의 조합으로 이를 구현할 수 있다.
        
                        <select> 태그는 드롭다운 상자 전체를 의미한다.
                        
                        <option> 태그는 각각의 선택 항목을 나타냅니다. 


두 대그의 관계는 설명서와 설명 항목의 관계나 메뉴판과 메뉴 항목 같은 관계이다.

예시
---

                                <select name="name_list">
                                        <option value="Mei">메이</option>
                                        <option value="Rio">리오</option>
                                </select>


                        
select 태그
---

옵션 메뉴를 제공하는 컨트롤을 나타냅니다.



option과 optgroup태그
---

select 태그의 각 옵션을 option과 optgroup으로 나타낸다.

option 태그들은 optgroup 태그로 그룹화할 수 있다.

option태그
---

select 태그 내의 option 태그들은 각각의 옵션을 나타냅니다.

사용자가 원하는 옵션을 나타낼 수 있습니다.

option 태그 내에는 텍스트나 이스케이프 문자(HTML 특수 문자를 의미함)만 유효합니다.

만약, HTML 태그가 포함된다면(예 <a>, <span> 등) 브라우저는 해당 태그가 가지는 고유한 기능과 스타일을 무시하고 태그 내의 텍스트나 이스케이프 문자을 유효한 콘텐츠로 사용합니다.

value 속성
--

각 <option>에는 해당 옵션이 선택될 때 서버에 제출할 데이터 값이 포함된 value 속성이 있어야 합니다. 

이 속성이 생략되면 값은 옵션 요소의 텍스트 내용에서 가져옵니다.

selected 속성
----

페이지가 처음 로드될 때 기본적으로 선택되도록 <option>에 selected 속성을 포함할 수 있다.

이 속성은 부울 속성(boolean attribute)입니다. 값을 별도로 작성하지 않고 속성만 작성다.

예시
---

                                        <label for="color">색상 선택</label>
                                        <select id="color">
                                            <option value="red">빨강</option>
                                            <option value="blue" selected>파랑</option>
                                            <option value="yellow">노랑</option>
                                            <option value="green">초록</option>
                                        </select>

disabled 속성
---

컨트롤 비활성 속성이라고도 부르며, 포커스도 가능하지 않고, 양식 제출 시 해당 값은 제출되지 않습니다.

select 태그 활성화 후 컨트롤에 드롭다운 목록이 표시되는 경우 대부분의 브라우저는 이 속성을 포함한 옵션을 회색처리합니다. 

그리고, 사용자도 이 옵션을 선택할 수 없다.

이 속성은 부울 속성(boolean attribute)입니다.

값을 별도로 작성하지 않고 속성만 작성합니다.

예시
---



optgroup 태그
----

optgroup 태그  select 태그 내에서 공통 레이블(이름)이 있는 <option> 태그의 그룹을 나타냅니다.

이 태그로 관련된 option 태그들을 묶어 그룹화하면, 사용자에게 더욱 체계적인 옵션 목록을 제공할 수 있다.
