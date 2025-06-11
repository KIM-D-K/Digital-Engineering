### <디지털(Digital)과 아날로그(Analog)>
- - -
1. 아날로그 양과 디지털 양
   1) 아날로그 양
      - 연속적인 값을 가지는 양을 의미함
      - 시간에 따라 변화하는 값으로 표현함
      - ex) 온도 센서가 측정한 온도, 소리, 압력과 같은 물리적 양
      - ![image](https://github.com/user-attachments/assets/eb089d8b-81aa-4d9f-83a0-a062ca07daad)
   2) 디지털 양
      - 이산적인 값을 가지는 양을 의미함
      - 일정한 간격으로 샘플링된 특정 값들의 집합으로 표현함
      - ex) 디지털 사진에서 각 픽셀의 섹상(R, G, B)
      - ![image](https://github.com/user-attachments/assets/014a9d14-bed3-4da8-9985-2448f8c5c50a)
      - 점으로 표시된 값들을 디지털 코드로 변환시키면 디지털 양으로 표현됨
- - -
2. 아날로그 신호와 디지털 신호
   1) 아날로그 신호
      - 아날로그 양으로 표현되는 신호임
      - 시간에 따라 변화하는 연속적인 값을 가짐
      - ex) 오디오 신호나 온도 드으이 물리적인 양
   2) 디지털 신호
      - 디지털 양으로 표현되는 신호임
      - 이산적인 겂을 가지며, 주로 0과 1의 이진 형태로 표현함
      - 시간에 따른 신호 크기가 '1' 상태(HIGH)와 '0'상태(LOW)로 나타남
      - 컴퓨터 시스템에서 사용되며, 디지털 데이터 처리 및 적장에 적합함
      - ![image](https://github.com/user-attachments/assets/da09af4e-1c66-436d-bdd7-0e319192ccb0)
- - -
3. 디지털의 장점
   1) 아날로그 신호보다 잡음(Noise)에 강함
   2) 신호 저장 후 재생에 크게 유리함(디지털 메모리의 특성)
   3) 다양한 신호처리에 따른 다양한 응용이 가능함
   4) 데이터는 계산에 사용될 수 있음
   5) 디스플레이 기술들과 호환됨
   6) 컴퓨터 기술들과 호환됨
   7) 시스템들은 프로그램 될 수 있음
   8) 디지털 IC군 (Family)들은 보다 쉽게 설계할 수 있음
- - -
4. 아날로그를 사용하는 이유
   1) 대부분의 '현실세계' 사건들은 실제로 아날로그 특성을 가짐
   2) 아날로그 처리는 대체로 더 간단하고 빠름
   3) 기존의 전자시스템은 대부분 실제로 아날로그였음
- - -
5. 아날로그 전자 시스템과 디지털 아날로그 방법을 이용한 시스템
   1) 아날로그 전자 시스템 - 소리 증폭기
      - 오디오 시스템에서 사용함
      - 소리 신호를 증폭하여 소리를 더 크게 만들어 주는 역할을 함
   2) 디지털 아날로그 방법을 이용한 시스템 - CD Player
      - 디지털 데이터를 아날로그 소리로 변환하여 음악을 재생함
      - 디지털 데이터의 정확성과 아날로그 소리의 자연스러움을 결합하여 음질을 향상시킴
   3) 아날로그 회로와 디지털 회로의 상호 연결
      - ![image](https://github.com/user-attachments/assets/351e3089-91c8-49ca-958f-86d03b41fb0f)
- - -
### <디지털 정보의 표현>
- - -
1. 2진 숫자
   1) 디지털 전자 공학에서는 두 가지의 상태만을 갖는 회로 및 시스템을 다룸
      - ![image](https://github.com/user-attachments/assets/16cbda1d-6e18-4319-89dc-93b3518c4457)
- - -
2. 논리레벨
   1) 1과 0을 표현하기 위하여 사용되는 전압
      - 디지털 정보를 표현하기 위해 2진수 체계(Binary System)를 사용함
      - 2종류 디지트(Digit)를 사용함("0"과 "1")
      - ![image](https://github.com/user-attachments/assets/f4422c76-42a8-4959-a443-650cd26f8d52)
- - -
3. 디지털 정보의 표현 단위
   1) 표현 단위
      - 1nubble = 4bit
      - 1byte = 8bit
      - 1byte = 1character
      - 영어는 1byte로 1문자를 표현하지만, 한글은 2byte가 필요함
      - 1word
      - 특정 CPU에서 취급하는 명령어나 데이터의 길이에 해당하는 비트 수
      - ![image](https://github.com/user-attachments/assets/cfa22422-8d95-43e9-8427-a562009255b9)
   2) SI단위와 IEC단위의 비교
      - ![image](https://github.com/user-attachments/assets/adb834f6-9e71-4728-bed0-88bbdabba0d1)
      - 국제단위계(International System of Units: SI)
      - 국제 전기 표준 회의(International Electrotechnical Commission: IEC)
      - ![image](https://github.com/user-attachments/assets/9558ccea-1de0-41bf-9e38-075ec04a68c3)
      - ![image](https://github.com/user-attachments/assets/5e2de28b-a95b-4c5b-97e7-e13b1a092447)
- - -
4. 디지털 파형
   1) 정논리와 부논리
      - 양논리 또는 정논리(Positive Logic)
      - 음논리 또는 부논리(Negative Logic)
      - 정논리와 부논리는 모두 디지털 논리 시스템에서 이용되며, 일반적으로 정논리를 많이 사용함
      - ![image](https://github.com/user-attachments/assets/00bb3b8c-5a08-4a9b-8113-d9e2c63ccedf)
   2) 펄(Pulse) 파형
      - Low상태와 High 상태를 반복하는 전압 레벨로 구성됨
      - ![image](https://github.com/user-attachments/assets/6be98d2b-9394-49f8-aa65-0a3b904ffdd9)
      - 이상적인 펄스 파형
        - 이상적인 주기 펄스는 두 개의 에지(Edge)로 구성됨
          - 리딩 에지(Leading Edge) = 상승 에지(Rising Edge)
          - 트레일링 에지(Trailing Edge) = 하강 에지(Falling Edge)
          - ![image](https://github.com/user-attachments/assets/11202ef9-a1cb-4dea-8613-0faf5be0660f)
        - 실제 펄스 파형
          - 상승 시간(Rising Time) : tr
          - 하강 시간(Falling Time) : tf
          - 펄스 폭(Pulse Width) : tw
          - ![image](https://github.com/user-attachments/assets/98a48dec-cf07-48a5-a30e-bcc9ea469a25)
          - ![image](https://github.com/user-attachments/assets/3310885f-69b0-44c6-ab42-fd22816d827f)
        - 주기, 주파수 및 듀티 사이클
          - 주기 : 주기적인 파형이 1회 반복하는 데 걸리는 시간을 의미함
          - ![image](https://github.com/user-attachments/assets/26696fde-ef25-4d8b-807f-52a9203456c3)
          - 주기적인 구형파와 비주기적인 구형파
          - ![image](https://github.com/user-attachments/assets/71a72427-234b-49e7-a5ae-10a0aa051f7a)
          - ![image](https://github.com/user-attachments/assets/0372e0e0-5dff-4549-a0ab-a1cb7c67fc73)
        - 주파수(Frequency)
          - 주기적인 파형이 1초 동안에 진동한 횟수를 의미함
          - 단위는 전파를 처음으로 발견한 독일의 헤르츠의 이름을 따서 헤르츠(Hz)를 사용함
        - 듀티 사이클(Duty cycle) = (tw / T)100%
          - 주기에 대한 펄스 폭(tw)의 비를 백분율로 나타냄
        - ![image](https://github.com/user-attachments/assets/4f89c6f0-76e0-45b5-bf01-b5f8671783c5)
        - ![image](https://github.com/user-attachments/assets/57bcf859-bc99-4c09-ac35-d31edf21ccb8)
        - ![image](https://github.com/user-attachments/assets/3341760e-81af-4c80-93e7-dbcf4cefb847)
        - ![image](https://github.com/user-attachments/assets/de1404ec-1cb0-48e5-b01a-c0f8fe96ff09)
        - ![image](https://github.com/user-attachments/assets/3fdddf5e-1831-4a19-b7ea-445507646b94)
        - ![image](https://github.com/user-attachments/assets/23b3d92f-4580-4d5a-9dbc-210b1be12ba5)
- - -
### <디지털 기본 논리회로>
- - -
1. 기본 논리 연산자
   1) ![image](https://github.com/user-attachments/assets/5177545d-e327-4078-999d-1bf03fdef807)
   2) AND
      - 모든 입력이 HIGH일 때만 출력은 HIGH
      - ![image](https://github.com/user-attachments/assets/7eaacc11-b5c5-4e94-b81f-7fd8d24808d9)
   3) OR
      - 입력들 중 어느 하나라도 HIGH이면 출력은 HIGH
      - ![image](https://github.com/user-attachments/assets/74e098cd-9e07-4799-9f93-efd46c0ff276)
   4) NOT
      - 입력의 반대
      - ![image](https://github.com/user-attachments/assets/2a3142c9-ce28-4360-b7ef-e95c8b683c51)
- - -
2. IC 패키지
   1) PCB(Printed Circuit Board)에 장착하는 방법에 따른 구분
      - 삽입 장착(Through-hole Mounted)형
      - 표면 실장(Surface-Mounted)형
      - ![image](https://github.com/user-attachments/assets/c94b4b8b-dedd-46f9-b98b-117f77e232f0)
      - SMD의 특징
        - DIP 형태의 논리회로의 크기를 70% 가량 줄이고, 무게를 90%만큼 감소시킴
        - PCB의 제조 가격을 크게 하락시킴
        - ![image](https://github.com/user-attachments/assets/8c7e0e91-52a9-488c-8231-cc8b2363f6b5)
        - ![image](https://github.com/user-attachments/assets/2f5017a0-282a-4013-80a8-9b5079e38408)
  2) 핀번호
      - ![image](https://github.com/user-attachments/assets/aa924ce4-3de2-4dac-853f-0ebc98cfaddb)
- - -
3. 고정기능 IC의 집적도 분류
   1) ![image](https://github.com/user-attachments/assets/03df23bb-34dd-40a5-8a76-93393a0d06cf)



