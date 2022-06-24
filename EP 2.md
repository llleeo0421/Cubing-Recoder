# 🐧 **Ep 2. 알고리즘 설계**

## 🐧 **이 과정이 필요한 이유**
- 어떻게 프로그램이 작동하는지 밑그림을 그리는 과정
  - 어떤 함수를 이용해 이 프로그램이 동작하는지 알 수 있음.
- 큐빙에서 15초 미리보기와 비슷한 과정.

## 🐧 **설계**
![실행](https://user-images.githubusercontent.com/101883868/175221064-822ae6ad-c9c7-49f5-a0db-1b4270570010.png)
- 실행결과 확인
  - 종목을 입력받아, 종목에 맡는 기록을 측정 방식이 나옴.
  - 측정 방식으로는 Ao 5, Mo 3 그리고 기타 방식이 있음.
  - 우리가 추가로 찾아야 할 정보 : WCA 공인종목 종류, 기록 측정방식

- 정보 탐색
  - [WCA 홈페이지](https://www.worldcubeassociation.org/results/records)에서 정보탐색.
    - Ao 5 : 10종목, Mo 3 : 6종목, 기타 : 1종목. 이렇게 총 17종목임.
  - 계산 
    - Ao 5 : {(기록 합)-(최고+최저)}/3
    - M0 3 : (기록 합)/3
    - 멀블 : (성공한 큐브 갯수)-(실패한 큐브갯수)

- 알고리즘 설계
  - '종목 입력 → 기록 측정 → 기록계산' 이 순서로 프로그램 작동함.

## 🐧 **Credit**
- Maker : Leo Kim([@llleeo0421](https://github.com/llleeo0421))
  - E-mail : dev.augustleo@gmail.com
  - GitHub : [@August-Leo-0805](https://github.com/August-Leo-0805)
  - Twitter : [@llleeo0421](https://www.twitter.com/llleeo0421)
  - Linkedin : [@augustleo](https://www.linkedin.com/in/augustleo)
  - Blog : [날 찾아온 낯선 여행자](https://llleeo0421.tistory.com)
