# 항해99 8기 2주차 <알고리즘> TIL_20220715 #
* 정신없이 **항해99 부트캠프 1주차(7.11.~7.14.)** 가 지나갔다. 
  * 배운 것도 많고, 트러블슈팅도 많았던 나의 첫 프로젝트 <챌린지픽>. 
  * 화장실 가는 것도 꾹 참을만큼 긴박하게 진행됐던만큼 TIL은 남기지 못해 아쉬웠다.
  * 사실 GIT 사용법도 잘 몰랐다. 지금 쓰는 README 파일도 오늘 처음 알았다!
  * 아무 기록이 없기 때문에 프로젝트 참고는 https://github.com/My-Challengeeeee/My-Challenge
----------------------------------------------------------------------------------------------------
* **2주차 알고리즘 스터디(7.15.7.21.)** 가 시작됐다.
  * 생각보다 알고리즘 문제 푸는 건 재밌다. 시간이 너무 빨리 흐른다. 
  * 숨통이 트였기 떄문에 오늘부터는 짬을 내서 TIL 한 단어라도 남기기로 다짐했다. 
  * 첫날이니까 조금 정성스럽게 오늘 공부한 것을 남겨보겠다!

![변수 위 가로줄 문제](https://user-images.githubusercontent.com/109029407/179265085-7349b69c-3b91-444c-8357-f8e4cced87bd.png)
> 함수에 들어가는 ~~변수명~~ 에 왜 줄이 그어졌을까? (구글링 실패)

![걷기1번문제](https://user-images.githubusercontent.com/109029407/179265170-0ac2e355-3248-43da-aab7-c09737b5059d.png)
> 프로그래머스 직사각형 별찍기 문제.js

![걷기3번문제](https://user-images.githubusercontent.com/109029407/179265178-ddc69d3e-46ac-4444-96de-a84a4a1433f7.png)
> 프로그래머스 가운데 글자 가져오기 문제.js
* =과 ==과 ===의 차이점을 알게 되었다. 파이썬에서는 구분 없이 다 =을 썼던 것 같은데,,, 정답을 찾아내는 데 한시간이나 걸렸다!
* =은 대입연산자로 변수에 값을 할당할 때, ==과 ===은 비교연산자로 조건문에서 많이 사용되고 결과값은 TRUE와 FALSE로 나온다.
* 코드 세 번째 줄은 단어s 나머지연산의 결과가 0과 같은지 다른지를 비교하는 부분이므로 =이 아니라 ==을 사용해야한다. 
* 그렇다면 ==과 ===의 차이점은? ==은 자료형을 자동변환하여 비교해주고 ===은 자료형까지도 동일해야 TRUE가 도출된다.
* "5"==5 (TRUE) / "5"===5(FALSE) 좀 더 엄격한 === 연산자를 사용하는 것을 추천!
* Math.floor()는 소수점 아래 버림!

![걷기6번문제](https://user-images.githubusercontent.com/109029407/179265184-b8dc7fe5-14a8-425d-a131-0dc5ee3b4ead.png)
> 프로그래머스 없는 숫자 더하기 문제.js
* !은 NOT연산자. TRUE나 FALSE를 반대로 뒤집는다.
* 배열.includes()는 배열이 특정요소()를 포함하고 있는지 판별!