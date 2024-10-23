# kotlin-racingcar-precourse

**자동차 이름을 입력받는 기능**
 - 자동차 이름을 입력받아 ','으로 구분한다
 - 입력받은 이름이 비어있거나 길이가 5보다 크면 IllegalArgumentException를 발생시킨다
 - 문제가 없다면 이름을 List<Pair<>>에 저장한다

**시도 할 횟수를 입력받는 기능**
 - 시도할 횟수를 입력 받는다
 - 숫자가 아니면 IllegalArgumentException를 발생시킨다

**차의 위치를 조절하는 기능**
 - 무작위 값이 4 이상일 경우 인덱스의 second에  1을 더해준다

**차의 위치와 이름을 출력하는 기능**
 - 차의 이름을 출력하고 second의 크기만큼 '-'를 출력한다

**우승자를 출력하는 기능**
 - 차의 이름과 위치가 저장된 리스트에서 가장 max의 second의 값을 찾아 maxSecond 변수에 저장한다
 - 리스트에서 maxSecond와 같은 값을 가진 값들을 우승자로 출력한다.
