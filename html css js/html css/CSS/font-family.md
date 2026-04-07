font-family
===

참고자료
---

https://inpa.tistory.com/entry/CSS-%F0%9F%93%9A-%EA%B0%92%EC%9D%98-%EB%8B%A8%EC%9C%84-px-em-rgb-viewport

https://www.inflearn.com/course/%ED%95%B5%EC%8B%AC%EB%A7%8C-%EB%B0%B0%EC%9A%B0%EB%8A%94-css3?cid=336232

https://wikidocs.net/191780

https://happylucky-lucky.tistory.com/5 

https://coding-factory.tistory.com/906

font-family
---

font-family 속성은 선택된 요소에 포함된 글자의 글꼴을 정의할 때 사용하는 속성으로, 텍스트를 포함하는 대부분의 요소에 지정할 수 있다.

시스템 내에 존재하는 기본폰트와 따로 제작된 폰트로 나누어진다.

https://coding-factory.tistory.com/906

시스템 폰트란?
---

운영체제(윈도우, OS 등)에 내장되어 있는 기본 폰트를 의미합니다. 

기본적으로 운영체제에 내장되어 있기 때문에 별도의 설치 없이 폰트를 사용할 수 있고, 그렇기 때문에 다운로드 과정이 필요 없어 속도가 빠릅니다.

폰트 종류 : serif, sans-serif, Arial, 돋움, 굴림, 궁서, 맑은고딕 등


그외의 폰트는 폰트를 직접 업로드하거나 웹폰트를 이용하는 방법이 있다.

웹폰트 적용방법
---

구글 웹폰트(https://fonts.google.com/) 접속

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c5fc9659-5f5a-408c-83df-0f8534ff3185" />

원하는 폰트 검색

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a511f3b6-b7fb-4530-a155-61d3cb7310e2" />

원하는 스타일 체크하고 Get font 클릭

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48eadff2-6cc5-486b-88f1-9ed21b687c42" />

원하는 폰트 클릭

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f4109ad4-c8d3-41ed-8628-167bff875e5a" />

get front 클릭후

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/68d91e2c-c43b-4fca-a7e6-865120b81927" />

get embed 클릭

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1a25aa43-3897-4eec-9a1b-051617f8205b" />

link하고 import 방식 둘중 하나를 선xor


link
---

html 파일

          <!DOCTYPE html>
          <html lang=ko>
          <head>
              <meta charset="UTF-8">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <meta http-equiv="X-UA-Compatible" content="ie=edge">
              <title>사인연습</title>
              <link rel="preconnect" href="https://fonts.googleapis.com">
              <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
              <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&family=Satisfy&display=swap" rel="stylesheet">
              <link rel="stylesheet" href="Sign_practice.css">
          </head>



처음 두 줄(rel="preconnect")은 브라우저에 글꼴 파일이 있는 서버에 미리 연결하라고 알려 로딩 속도를 높입니다.

세번째 줄(rel="stylesheet")은 실제 Google Fonts 스타일시트를 웹페이지에 적용합니다.

css파일 코드

        .k1_sign{
            font-family: "Caveat", cursive; 
            font-size: 100px;
        }

import 방식
---

              <head>
                  <meta charset="UTF-8">
                  <meta name="viewport" content="width=device-width, initial-scale=1.0">
                  <meta http-equiv="X-UA-Compatible" content="ie=edge">
                  <title>나만의 싸인</title>
                  <link rel="stylesheet" href="../css/Sign_style.css">
              </head>
              
css

          .Sign{
              font-family: "Satisfy", cursive;
              font-weight: 400;
              font-style: normal;   
          }

import 방식보다 link 방식이 성능측면에서 더 좋다고 한다.
