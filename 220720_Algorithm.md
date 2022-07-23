# 항해99 8기 2주차 <알고리즘> TIL_20220720 #
## 오늘의 알고리즘 문제는 4개! ##
> 프로그래머스 정수 제곱근 판별 문제.js
>   * **Math.sqrt()** 메소드는 함수 인자로 값을 넘겨주면 루트값을 반환. 매개변수가 음수이면 NaN을 반환.
>   * **Math.pow(base, exponent)** 메소드는 base 값에 exponent만큼 제곱한 값을 반환. 
>   * javascript 루트와 제곱 참고 : https://velog.io/@chayezo/%EB%A3%A8%ED%8A%B8%EC%99%80-%EC%A0%9C%EA%B3%B1-%EA%B5%AC%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95
![걷기25번문제](https://user-images.githubusercontent.com/109029407/179920296-c6d26dd9-bd84-4f40-b98c-09dab8e8dc19.png)   
----------------------------------------------------------------------------------------------------
> 프로그래머스 제일 작은 수 제거하기 문제.js
>   * **Math.max()와 Math.min()** 메소드는 파라미터로 입력받은 숫자들 중 최대값과 최소값을 구해서 리턴하는 함수.
>   * 배열에 담긴 여러 숫자 중 최소값을 구하려면 배열의 원소들을 하나씩 꺼내서 Math.min()에 전달.
>   * **Spread Operator(전개연산자/...[배열명])** 는 객체나 배열의 원소들을 하나씩 꺼내서 펼쳐서 리턴. 기존 배열에 영향을 주지 않음. 
>   * Spread Operator 참고 : https://learnjs.vlpt.us/useful/07-spread-and-rest.html
![걷기26번문제](https://user-images.githubusercontent.com/109029407/179920347-eb33819b-d0b0-4e40-bdfc-e4d59db305a0.png)  
----------------------------------------------------------------------------------------------------
> 프로그래머스 콜라츠 추측 문제.js
>   * **while(조건식){조건에 만족할 동안 실행할 명령문=증감식}** 문은 조건문이 참일 때 실행되는 반복문.
>     * 반복이 시작되기 전에 조건문은 참, 거짓을 판단. 
>     * 만약 조건문이 참이라면, while문 안의 문장들이 실행.
>     * 조건문이 거짓이라면, 문장은 그냥 while 반복문 후로 넘어감.
>     * while 문 내부에 표현식의 결과를 변경하는 실행문이 존재하지 않을 경우 무한루프에 빠질 수 있음.
>     * break 문은 루프 내에서 사용하여 해당 반복문을 종료시키고, 반복문 바로 다음에 위치한 실행문으로 프로그램의 흐름을 이동. 루프 내에서 표현식의 판단 결과에 상관없이 반복문을 완전히 빠져나가고 싶을 때 사용.
>     * 일반적으로 반복 횟수가 예측 가능할 때는 for 문을 사용하는 것이 가독성이 더 좋고, 반복 횟수를 예측할 수 없으면 while 문을 사용하는 것이 더 적합. 
![걷기27번문제](https://user-images.githubusercontent.com/109029407/179920372-b8249acc-ac61-4d0a-ba3d-b5004c9000e1.png)
----------------------------------------------------------------------------------------------------
> 프로그래머스 하샤드 수 문제.js
![걷기28번문제](https://user-images.githubusercontent.com/109029407/179920399-eed5ae1c-4832-45f0-acfe-be3d6a6e8214.png)   
----------------------------------------------------------------------------------------------------