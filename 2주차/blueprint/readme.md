### 1. 정해진 포인트에서 적이 배회 
![BP_Enemy1](https://github.com/user-attachments/assets/024853ae-c4f8-4d1f-9183-19c5ac222f34)
![BP_Enemy1_UpdatePatrolPointBB](https://github.com/user-attachments/assets/0abb71f8-2c0d-4e5a-b3bb-e7f441808116)
<br>
### 2. AI 컨트롤러, 플레이어 인식
![AC_EnemyController1](https://github.com/user-attachments/assets/6d8c41af-451d-4c9d-92e0-0fd6f50f4b52)
![AC_EnemyController1_CheckPlayer](https://github.com/user-attachments/assets/dcb18c7b-85f0-405a-9aeb-5475edc6d2cd)
![BTS_PlayerLocation1](https://github.com/user-attachments/assets/202fb2bb-91a2-416f-a0b6-d68ba0304b0a)
<br>
### 3. 플레이어를 발견하면 달리면서 쫓아오기
![BTS_SetSpeed1](https://github.com/user-attachments/assets/e0cd8331-04f1-4689-a459-f160eb853f06)
<br>
### 4. 비헤이비어 트리
![BT1](https://github.com/user-attachments/assets/0c738c17-084f-4902-96e1-d7f01d540e6d)
<br>
### 5. 플레이어 달리기
![BP_Player1_Sprint](https://github.com/user-attachments/assets/6f4767d2-fbf9-403e-ad91-1e7bde28cafc)
<br>
### 6. 달리기 스테미너 소모, 회복
문제점
---
1. 스테미너가 0이 되어도 계속 달려진다.
2. 게임 시작시 달리지 않아도 스테미너가 0으로 줄어들고 달리기 키를 한번 눌러야 스테미너가 최대가 된다.
![BP_Player1_SM](https://github.com/user-attachments/assets/06a5cff6-78dd-44ce-8b61-b30388fe4a88)

