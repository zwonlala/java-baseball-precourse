## 구현해야 하는 기능<br>
1. main 함수 작성 & 상수, 변수 정의하기 <br>
2. 1~9 사이의 서로 다른 수로 이루어진 3자리 수를 만들어 리턴하는 함수<br>
3. 사용자의 입력(세 수) 받는 함수<br>
4. 사용자가 입력한 세 수 valid/ invalid 체크하는 함수<br>
   - 사용자가 숫자를 1자리나 2자리만 입력하는 경우
   - 사용자가 숫자 0을 입력하는 경우
   - 사용자가 숫자가 아닌 문자를 섞어서 입력하는 경우
    
5. 스트라이크/볼/낫싱 출력해주는 함수<br>
   - 스트라이크 체크해주는 함수
   - 볼 체크해주는 함수
   - 낫싱 체크해주는 함수
6. 맞췄는지 틀렸는지 true/false 리턴해주는 함수<br>
7. 게임 종료 & 반복해주는 함수<br>

### - 고민거리
사용자의 입력과 정답을 int answer = 123; 이렇게 int 형으로 저장 & 관리하는게 나을 것인가
아님 int[] answer = { 1, 2, 3}; 이와 같이 배열로 저장하는 것이 편할 것인가

-> 배열로 사용하면 확장성?이 떨어질 것 같다. 확장성의 이유로 static final int INPUT_SIZE = 3; 과 같이 정의를 하는데

