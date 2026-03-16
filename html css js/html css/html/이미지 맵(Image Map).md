이미지 맵(Image Map)
===

참조자료
---

https://velog.io/@seoyaon/HTML-%EC%9D%B4%EB%AF%B8%EC%A7%80%EB%A7%B5-%EB%A7%8C%EB%93%A4%EA%B8%B0-%EC%A2%8C%ED%91%9C%EA%B0%92-%EC%89%BD%EA%B2%8C-%EC%B0%BE%EA%B8%B0-mj7lfivg

https://www.inflearn.com/course/%ED%95%B5%EC%8B%AC%EB%A7%8C-%EB%B0%B0%EC%9A%B0%EB%8A%94-html5/dashboard?cid=336221


이미지 맵(Image Map)이란?
--

이미지맵이란 하나의 이미지 안에 여러 개의 링크를 지정할 수 있게 하는 HTML 기술


코드예시
---

        <img src="이미지경로" alt="대체텍스트" usemap="#맵이름">
        <map id="맵아이디값" name="맵이름">
        	<area shape="좌표모양" alt="대체텍스트" title="링크설명" coords="링크좌표(x,y,x,y)" href="링크경로" target="링크를 여는 형태"/>
        </map>

 usemap의 맵이름과 map 태그안의 id값과 name은 동일해야 한다.

 
shape 속성
---

어떤 모양의 링크를 만들지 결정하는 속성

react : 직사각형

circle : 원형

poly : 다각형



coords 속성
----

이미지 어디위에다가 링크를 만들지 좌표를 정하는 속성

사각형 모양일 때
---


      coords = "x1,y1,x2,y2" : 좌, 상, 우, 하        


원형 모양일 때
---

    coords = "x,y,radius" : 원형 중앙과 반지름의 좌표


다각형일 때
---

    coords = "x1,y1,x2,y2,...xn,yn" : 다각형 끝의 좌표

target속성 -> 링크를 여는 형태
---

        -blank : 새 창으로 열림
        
        _parent : 부모 창에 열림
        
        _self : 현재 페이지에서 열림
        
        _top : 전체 브라우저 창에서 열림
