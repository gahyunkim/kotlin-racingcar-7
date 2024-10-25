# kotlin-racingcar-precourse

## 자동차 경주
여러 대의 자동차가 주어진 횟수 동안 무작위 값을 통해 전진하거나 멈추며, 게임이 종료된 후 가장 멀리 이동한 자동차를 우승자로 결정하는 문제

## 구현할 기능 목록
### 1) 경주할 자동차 이름 입력 받기
- 입력 조건
- [x] 자동차 이름은 5자 이하로만 입력받는다
- [x] 자동차 이름은 쉼표로 구분한다
- 예외 처리
- [x] 공백이 포함된 이름, 중복된 이름은 허용하지 않고 에외처리
- [x] 쉼표가 아닌 다른 구분자를 사용하는 경우 예외처리
- [x] 이름이 공백인 경우 예외처리

### 2) 이동 횟수 입력 구현하기
- 입력 조건
- [ ] 사용자로부터 입력 횟수를 입력받기
- 예외 처리
- [ ] 공백이거나 음수 혹은 0이하인 경우 예외처리
- [ ] 숫자가 아닌 값(문자)가 포함된 경우

### 3) 경주 실행하기
- 실행 조건
- [ ] 각 차수에서 0-9 사이의 무작위 값을 생성하기
- [ ] 무작위 값이 4 이상일 경우에만 자동차가 전진하도록 구현
- [ ] 각 차수별로 자동차의 이름과 전진 상태를 출력

### 4) 우승자 결정하기
- 우승자 결정 조건
- [ ] 주어진 횟수동안 가장 멀리 전진한 자동차를 우승자로 결정
- [ ] 공동 우승자가 있는 경우 쉼표로 구분하여 출력하기
- [ ] 결정된 우승자 출력하기

## 요구사항 확인하기
- [ ] `camp.nextstep.edu.missionutils.Randoms`의 `pickNumberInRange()` 메소드를 사용하여 0에서 9 사이의 무작위 값을 생성
- [ ] 사용자가 입력하는 값은 `camp.nextstep.edu.missionutils.Console의 readLine()`을 활용
- [ ] 테스트 도구를 활용하여 기능이 정상적으로 작동하는 지 테스트 코드로 확인하기
- [ ] indent depth가 3을 넘지 않도록 구현한다. 2까지만 허용함
- [ ] 함수가 한가지 일만 하도록 최대한 작게 만들기