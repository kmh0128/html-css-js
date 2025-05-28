HTMl의 구조 파악
===


    <!DOCTYPE html>
    <html lang="ko">
    <head>
      <meta charset="UTF-8">
      <title>HTML 기본 문서</title>
    </head>
    <body>
      <h1>웹 문서 만들기</h1>
      <hr>
      <p>HTML</p>
      <p>CSS</p>
      <p>자바스크립트</p>
    </body>
    </html>

html 문서구조
---

<!DOCTYPE html> -> 현재 문서가 HTML 언어로 작성한 웹 문서라는 뜻

<html>~</html> -> 웹문서의 시작과 끝을 나타내는 태그 시작과 끝 사이에 있는 코드를 읽어 화면에 표시

<head>~</head> -> 웹 브라우저가 웹 문서를 해석하는데 필요한 정보를 입력하는 부분

<body>~</body> -> 실제로 웹 브라우저 화면에 나타내는 내용입니다.

웹 문서의 유형을 지정하는 <!DOCTYPE html> 태그
---

웹 문서의 첫 부분은 문서 유형(document type)을 지정하는 <!DOCTYPE html>로 시작한다.

웹 브라우저에게 현재 문서가 HTML  문서라고 알려주는 것이다.

html 태그
---

    <html lang="ko">
    .....
    </html>

HTML태그는 HTML파일의 시작을 표시합니다.

<html> -> 태그의 시작을 표시
    
</html> -> 웹 문서가 끝났다고 표시할때는 /태그 표시사용 그리고 이 뒤에는 아무내용도 없어야한다.

위 태그에서는 lang 속성으로 문서에서 사용할 언어를 지정할 수 있다.

한국어라면 korean의 줄임말인 ko를 사용합니다.

<html lang="ko"> => 한국어로 된 문서로 범위를 제한한것


head 태그
---

<head>~</head> -> head 태그 사이에 작성한 내용은 웹 브라우저 화면에는 보이지 않는다.

웹 브라우저가 알아야 할 정보를 입력하는곳

문서에서 사용할 스타일 시트 파일도 이곳에서 연결해준다.

head영역에서 사용하는 태그
===

<meta>태그
----

메타 정보라고 하는것은 데이터에 관한 데이터를 말한다.

ex)
--

책의 메타정보는 가격 쪽수 지은이 등이 있는것처럼 웹문서의 <meta>태그는 웹 브라우저에는 보이지 않지만 웹 문서와 관련된 정보를 지정할때 사용

<meta> 태그의 가장 중요한 역할은 화면에 글자를 표시할 때 어떤 인코딩을 사용할지 지정하는것이다.

웹서버는 영어를 기본으로 하므로 화면에 한글로 된 내용을 표시할 때에는 UTF-8이라는 문자 세트를 사용한다.


예시
--

<meta charset='UTF-8'>


meta 태그에서 인코딩을 명시하지 않으면 웹 브라우저에서 자동으로 인코딩을 처리하기 때문에 한글이 깨질수도 있다.

위의 코드는 한글 인코딩을 명시하는 코드여서 꼭 적어주는것이 좋다.

이외에도 웹 사이트의 키워드나 간단한 설명, 제작자 등의 정보를 지정할 때에도 meta 태그를 사용할 수 있다.

검색 엔진에 따라 참고하는 정보가 달라질 수 있다.

<meta name="keywords" content="html의 구조"> -> 웹문서의 키워드
<meta name="description" content="html의 구조를 알아 봅시다"> -> 웹 문서의 설명
<meta name="author" content="Myungho Kang'> -> 웹문서의 소유자 or 제작자


문서 제목을 나타내는 <title> 태그
---

<head>-> 태그 안에서 가장 중요한 태그는 <title> 태그

예시

        <title>HTML의 기본문서</title>

tile 태그에서 지정하는 내용은 웹 브라우저의 제목 표시줄의 표시

해당 페이지의 방문자나 검색 엔진은 제목 표시줄의 제목을 보고 페이지 전체 내용을 추측할 수 있어야 된다.

웹 사이트 즐겨찾기 사용시 웹 문서의 제목으로 표시

![title 태그](https://github.com/user-attachments/assets/7c76467b-9a66-404d-9965-a849906300e3)



웹문서의 내용을 표시하는 <body>태그
---

예시
--

        <body>
            <h1>웹 문서 만들기</h1>
            <p>HTML</p>
            <p>CSS</p>
            <p>Javascript</p>
        </body>
        
![바디태그](https://github.com/user-attachments/assets/f174faa7-7956-4eb2-9334-5c01833f1471)

bodu 태그는 웹 브라우저에 표시되는 내용이다.


참고자료
---

Do it 한권으로 끝내는 웹 교과서 html css js 저자 고경희님
