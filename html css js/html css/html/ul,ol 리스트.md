HTML 정리4
===

목록 관련 태그

참고자료
---

[https://wikidocs.net/287992](https://wikidocs.net/287991)

https://www.youtube.com/watch?v=sp4ruWfpY2k&list=PLFeNz2ojQZjtQc7mt8E9fNzIh9or34A61&index=11

https://mundol-colynn.tistory.com/55#:~:text=%EB%AA%A9%EB%A1%9D%EA%B4%80%EB%A0%A8%20%ED%83%9C%EA%B7%B8%20:%20%EC%88%9C%EC%84%9C%EA%B0%80%20%EC%9E%88%EB%8A%94%20%EB%AA%A9%EB%A1%9D%ED%83%9C%EA%B7%B8%20%ED%83%9C%EA%B7%B8%EB%AA%85,:%20%EB%AA%A9%EB%A1%9D%EC%9D%98%20%EC%8B%9C%EC%9E%91%20%EC%88%AB%EC%9E%90%EC%A7%80%EC%A0%95%20*%20reserved%20%ED%95%AD%EB%AA%A9

https://www.inflearn.com/course/%ED%95%B5%EC%8B%AC%EB%A7%8C-%EB%B0%B0%EC%9A%B0%EB%8A%94-html5?cid=336221

목록
---

목록은 연관있는 항목(item)들을 나열한 것을 의미한다.

HTML 목록은 '순서 없는 목록(Unordered List)'과 '순서 있는 목록(Ordered List)'으로 구분한다.


순서 없는 목록 (Unordered List)
---

순서 없는 목록
----

            <ul></ul>

순서가 중요하지 않은 목록을 만들 때 사용

시장에서 물건을 사는 리스트처럼 사과 바나나 항목만 표시


예
---

                <ul>
                  <li>사과</li>
                  <li>바나나</li>
                  <li>복숭아</li>
                </ul>

순서 있는 목록
----

          <ol></ol>


순서가 중요한 목록

요리 레시피처럼 "1. 재료 준비, 2. 볶기, 3. 조리 완료 단계별 과정


            <ol>
             <li>첫 번째 </li>
             <li>두 번째 </li>
             <li>세 번째 </li>
            </ol>

ol 속성
---

                        예시 <ol type ="속성값"></ol>
                        
type :목록에 사용될 마커 지정

 -  1 숫자(default)
   
 -  a 소문자
   
 - A 대문자
  
 - i 로마숫자 소문자
   
 - I 로마숫자 대문자

start: 목록이 시작할 숫자의 위치를 지정 (예: <ol start="5">는 5부터 시작)

disc(기본값)/circle /square 

reserved 항목 역순표시


목록 항목 (List Item)
---

li 태그는 목록 하나하나를  표현할 때 사용하는 태그


              <ul>, <ol>, <li> 는 모두 블록 레벨 요소를 만드는 태그


            
