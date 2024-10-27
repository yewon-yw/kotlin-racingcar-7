# kotlin-racingcar-precourse

### ✅ 구현할 기능 목록
1. 자동차 이름 입력받기
   - [x] 쉼표를 기준으로 분리
   - [x] 이름이 5자 이상이면 IllegalArgumentException
   - [x] 자동차 이름이 중복되면 IllegalArgumentException
   - [x] 자동차 이름으로 빈 문자열 사용 불가능하게 처리
2. 시도할 횟수 입력받기
   - [x] 숫자로 변환이 불가능하면 IllegalArgumentException
   - [x] 0 이하의 숫자가 입력되면 IllegalArgumentException
3. 전진 여부 판단하는 함수 작성
   - [x] 무작위 값이 4 이상인 경우만 전진
4. 차수별 실행 결과 출력
5. 우승자 출력하기
   - [x] 사용자가 입력한 횟수만큼 반복
   - [x] 우승자 리스트를 쉼표로 구분해서 출력
   
<br>
   
### 💡 프로그래밍 요구 사항
1. indent depth가 3이 넘지 않도록 구현
2. 함수가 한 가지 일만 하도록 최대한 작게 만들기
3. JUnit5와 AssertJ를 이용하여 정리한 기능 목록이 정상적으로 작동하는지 테스트 코드로 확인