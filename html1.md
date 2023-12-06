html이란?
====

HTML 은 Hyper Text Markup Language 줄임말로 간단하게 말하면 웹 페이지를 만드는 마크업 언어라고 할 수 있다. 

HyperText는 기본적으로 웹 페이지에서 다른 페이지로 이동할 수 있는 HyperLink를 지원하도록 설계 되었고 

이 덕분에 페이지 안에서 클릭만으로 다른 페이지로의 이동이 가능하게 된다.

html
====

메모장을 a.html이란 파일로 다른이름으로 저장하기전에 파일형식을 모든 파일로 설정 인코딩은 utr-8로 설정하고 저장을 하면,

a는 파일이름 html은 확장자 -> 웹브라우저로 실행 될것이다. html이란 확장자는 어떤 프로그램으로 열어아 할것이란걸 알것이다.

html태그
====

html 이란?
====

HTML은 웹 페이지에 콘텐츠를 표시하기 위해 사용하는 언어입니다. 

어느 부분에 텍스트가 있어야 할지, 어느 부분에 이미지가 있어야 할지 등을 나타내는 것이 HTML의 역할입니다. 

이러한 역할을 수행하기 위해 HTML은 '태그(tag)'라는 표기법을 사용합니다.

사용방법의 예
===

<태그의이름>콘텐츠</태그의이름>  

<시작 태그>내용</ 닫히는 태그> 이사이에 있던 내용이 태그 명렁어에 의해 나타나게된다.

예시:

![태그의 예시1](https://github.com/kmh0128/html-/assets/100178951/871c9479-92e1-4689-b78a-09c8875a3412)

기본 태그 구조
===
HTML은 머리(head)와 몸(body)로 이루어져있다고 생각하면 편하다.

head는 HTML의 전반적인 특성을 설정하는 곳이다.

body는 화면에 그려질(render) 내용들을 넣는 곳이다.

내용
===

<!DOCTYPE html>   웹 문서의 유형을 html로 지정

<html>	모든 html 태그들의 최상위 태그

<head>	문서의 공통적인 특성들을 넣는 곳, 전역(전체적인) 특성

<meta>	메타 데이터 입력

<title>	문서의 제목

<body>	문서의 본문, 여기에 내용을 나타낸다.


예
===

    <!DOCTYPE html>
    <html lang="ko">
    <head>
        <meta charset="UTF-8">
        <title>Document</title>
    </head>
    <body>
      <h1>여기는 문서 본문입니다.</h1>
    </body>
    </html>

<html lang="ko">
언어를 한국어로 보일수 있게 지정해주는 언어입니다.

HTML Basic Tags
====




<html>

웹페이지의 시작과 끝을 나타낸다.

<head>

웹 페이지의 정보, 문서에서 사용할 외부 파일들을 링크할 때 사용한다.

<body>

브라우저에 실제 표시되는 내용을 담고있다.

<title>

문서의 제목을 나타낸다. 웹브라우저의 제목 표시줄에 표시된다.

보통 제목표시줄이 더 많이 노출되기 때문에 잘 쓰면 좋다.


내용 입력
===
제목

h1, h2, …, h6 (heading)

예
==

    <h1>h1입니다.</h1>                       

    <h2>h2입니다.</h2>                       

    <h3>h3입니다.</h3>       
                           =>              1일때 가장 크고 숫자가 커질수록 글자 크기가 작아진다.
    <h4>h4입니다.</h4>

    <h5>h5입니다.</h5>

    <h6>h6입니다.</h6>




html속성
====












참고자료
====
https://velog.io/@ljinsk3/HTML-%EA%B8%B0%EC%B4%88-%EB%82%B4%EC%9A%A9-%EC%A0%95%EB%A6%AC

https://yunbinni.tistory.com/63

https://velog.io/@ansalstmd/HTML-1

https://velog.io/@ansalstmd/HTML-1

https://www.youtube.com/watch?v=JiuYfoSEac4&list=PLuHgQVnccGMDUzDDCKW-pCZQY-MMCX5yB&index=7

https://wikidocs.net/160445
