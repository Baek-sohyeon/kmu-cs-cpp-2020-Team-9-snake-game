# kmu-cs-cpp-2020-Team-9-snake-game
C++을 이용한 Snake game 제작

## pseudo-code
```
int main(void){
  while(게임 종료 안되면){
      키보드 입력 감지(); 
      뱀 위치 업데이트(); 
      Growth 아이템 업데이트(); 
      Position 아이템 업데이트(); // Growth, Position 아이템 펄스 정해야함
      게이트 업데이트(); //Immune wall은 게이트로 변할 수 없음, 게이트 출현 방법 정하기
      스코어 업데이트(); 
      뱀이 움직일 수 있는 지 체크(); // 벽 만남, 키보드 방향(꼬리 방향으로 키보드 입력), 자기 몸 통과->게임종료조건 체크
      뱀 이동();
      뱀이 Growth 아이템 먹음(); // 꼬리 부분 위치 유지 Growth 아이템 놓인 부분이 뱀 머리?됨
      뱀이 Position 아이템 먹음(); // 꼬리 감소
      뱀이 게이트 진입함();
      스코어 계산 및 점수판 출력(); // 움직일 때마다 스코어 업데이트한 거 + 게임시간으로 계산
      }
```

## conference 01
```
```
