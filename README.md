# 🐢 Catch Turtle
오픈소스 강의에서 구현한 파이썬 기반 게임입니다.

## 제품 설명 및 목표 
### Catch Turtle Game
![image](https://github.com/user-attachments/assets/6f548874-b437-4560-819c-a5246e1991cb)
- Python Graphic module 'Turtle'을 사용한 게임 구현
- 4가지 모양이 오른쪽, 왼쪽, 아래쪽 위쪽에서 등장
- 사용자의 키보드 방향키 입력을 통해 캐릭터를 잡는 게임
- 제한 시간 30초 내에 진행
- 게임 진행 시 10개의 목숨이 존재
  
### 1. 2차원 좌표의 캔버스에서 게임 구현
- Turtle 모듈 내의 screen 그래픽 창을 정의
- 모듈의 움직임 명령어를 사용하여 커서 표시
- Screen 이벤트 함수를 이용하여 User interface 구현

### 2. 간편한 Game User Interface
- 간단한 조작 방법으로 즐기기 쉬운 게임 환경 구현
- 게임 시작 전 사용 방법을 GUI 화면으로 구현
- 추가적인 옵션으로 게임의 재미를 더함
  
## 추가 기능 설명
### 1. 게임 시작 전 화면
- Space 누를 시 게임 시작
### 2. Game Over 
![image](https://github.com/user-attachments/assets/e5a79930-b22a-459e-903a-d126b3e0659c)
- 게임 시간(30초) 또는 목숨이 0밑으로 내려 갔을 시 팝업
### 3. Life 기능
![image](https://github.com/user-attachments/assets/9c2a0e5c-ecd8-468a-a0e9-a04a44e3d8ec)
- 0 밑으로 내려갈 시 GameOver
### 4. Shape Tilt 기능
![image](https://github.com/user-attachments/assets/078ea2c2-6311-48c2-8028-9ec97aceee75)
- 거북이 모양 방향 랜덤 출몰
### 5. Shape Appear 기능
![image](https://github.com/user-attachments/assets/f48c6e07-a253-4598-a806-a4e870f74ecb)
- Circle, Triangle, Square와 거북이가 랜덤으로 출몰하게끔 개발
## 협업 프로세스 
- 협업 도구<br><br>
![image](https://github.com/user-attachments/assets/9fe0ef34-33cf-4e7c-be37-2123c5682ac3)

- 협업 과정 : 기본 기능과 추가 기능<br><br>
![image](https://github.com/user-attachments/assets/2538fe61-45c9-43b7-86dc-1a0a12281db8) <br>

![image](https://github.com/user-attachments/assets/d6b014c6-1067-432f-b510-4fe51646bfc1)<br>

- 구현한 기능
  - show_message()
  - game_play()
  - turn_right()
  - Turtle tilt func
  - circle appear func<br>
    
## 적용한 프로세스의 장단점
### 적용 프로세스 : Integration-manager workflow<br>
  - 장점 : 팀 프로젝트에서 팀원들이 하나의 소스 코드를 사용해 작업하면서, GitHub와 Git을 활용하여 충돌을 방지하고 해결 가능<br>
  - 단점 : 2~3명에서 각자 맡은 함수를 구현하는 과정이기에 maintainer+contributor 보다centralized workflow가 효율적
