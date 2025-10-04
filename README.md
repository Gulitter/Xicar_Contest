# 자이트론 미션 수행
2022 5인 프로젝트(시뮬레이션_주차, 수직주차, 터널통과)

# AR태그 주차 시뮬레이터
자세정보를 활용하여 PID제어.

<img width="930" height="471" alt="image" src="https://github.com/user-attachments/assets/40ea1a42-5ab6-4d7a-9845-d1e3580ce478" />


# 수직주차
초음파 및 라이다 센서를 통해 벽면의 센서값의 변화를 이용해서 주차미션 플래그를 동작. 
하드코딩을 통해 장애물과 부딪칠 것 같을 경우 조정하며 주차를 수행.

<img width="573" height="868" alt="image" src="https://github.com/user-attachments/assets/b2b585db-7a5c-48fc-9ad8-d200713d2064" />

# 터널통과
라이다센서가 양쪽에 감지되면 터널플래그를 동작. 
정면에 해당하는 0도값에는 90cm 이상이 유지되고, 양 옆인 -90도와 90도에 해당하는 센서값은 각각 22.5cm 값을 유지하도록 pid제어를 통해 서보모터 조향.

<img width="1184" height="665" alt="image" src="https://github.com/user-attachments/assets/10047519-d5df-4275-b311-9367beebd06a" />

# 결과
ROS환경 및 PID제어에 익숙해질 수 있었고, 센서값 필터링에 대한 지식을 향상시킬 수 있었습니다. 
자율주행차가 고려해야할 여러상황에 대한 코드를 짜보면서 실제 자율주행에 필요한 기술들에 대해 고민해 볼 수 있었습니다. 
