# ⚾ 숫자 야구 게임

## 구현 기능 목록
### 1. 게임 넘버 생성
- 1에서 9까지 서로 다른 임의의 수 3개 생성
- RandomUtils 이용

### 2. 플레이어 넘버 입력
- IllegalArgumentException 발생
  - 0이 포함된 경우
  - 중복되는 수가 있는 경우
  - 3자리 수가 아닌 경우

### 3. 힌트 생성
- 게임 넘버와 플레이어 넘버 비교하여 스트라이크/볼 개수 카운트
  - 스트라이크 : 같은 자리에 같은 숫자 있는 경우
  - 볼 : 다른 자리에 같은 숫자 있는 경우
- 힌트 출력
  - 볼과 스트라이크 개수 출력
  - 하나도 없는 경우 "낫싱" 출력
  
### 4. 게임 진행
- 정답이 아닐 경우 2번으로 돌아감
- 정답일 경우 재시작(1) 혹은 완전종료(2) 입력
  - 재시작의 경우 1번으로 돌아감
