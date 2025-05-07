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



