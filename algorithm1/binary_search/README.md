### 704 Binary Search
오름차순으로 정렬된 정수 정렬 nums가 주어진다. <br>
nums 안에서 주어진 target 정수를 찾는 함수를 만들어라. <br>
만약, target이 존재한다면 해당 인덱스를 반환한다. <br>
그런데 taget이 존재하지 않는다면 -1을 반환한다. 


### 278. 첫번째 나쁜 버전
각 버전은 이전 버전을 기반으로 개발된다. <br>
나쁜 버전 이후의 버전은 마찬가지로 좋지 않게 된다. <br>
n개의 버전을 받게 되는데, 가장 첫번째로 나쁜 버전을 찾고자 한다.<br>
왜냐하면 뒤따라오는 모든 버전도 함께 좋지 않아지기 때문이다. <br>

bool isBadVersion(version) 이라는 API를 받게 될 건데 이 함수는 나쁜 version을 반환한다. <br>
당신은 나쁜 버전을 찾는 함수를 만들어야하고, API 를 호출하는 횟수를 최소한으로 해야한다. 


### 35. 삽입 위치 찾기
중복되지 않은 정렬된 정수 배열과 target 값이 주어진다. <br>
target 값을 찾으면 해당 인덱스를 반환하라. <br>
만약 없다면 해당 값이 들어갈 인덱스를 반환하라. 


### 374. 가장 높은 숫자와 낮은 숫자 예상하기
1에서 n까지의 숫자 중 하나를 뽑는다. <br>
그 중 하나를 예상해본다. <br>
예상한게 틀릴 때 마다 옛아한 숫자가 현재 뽑은 숫자보다 높은지 낮은지 알려준다. <br>
3가지 결과를 반환해주는 pre-defined API ```int guess(int num)```를 호출한다. <br>
- -1 : 당신의 예상이 내가 뽑은 숫자보다 높을 경우 <br>
- 1 : 당신의 예상이 내가 뽑은 숫자보다 낮을 경우<br>
- 0 : 당신의 예상이 내가 뽑은 숫자와 같을 경우 <br>

내가 선택한 숫자를 리턴한다. 