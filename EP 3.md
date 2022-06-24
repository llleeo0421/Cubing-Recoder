# 🐧 **Ep 3. 프로그래밍 1**

## 🐧 **오늘 배울 부분**
- 종목 코드를 입력받고, 어떤 종목의 기록을 재는지 안내 하는 부분

## 🐧 **코드**
```py
record = []
event = ['33', '22', '44', '55', '66', '77', '3BLD', 'FMC', 'OH',
         'Clock', 'Mega', 'Pyra', 'Skewb', 'SQ-1', '4BLD', '5BLD', 'MBLD']
worst = 0.0001
best = 1000000.0

ev = int(input('종목 코드: '))
print('당신이 선택한 종목은', event[ev-1], '입니다.')
print('')
```

## 🐧 **코드해설**
- 기록 입력공간
```py
record = [] '''큐브 기록이 들어갈 공간. [] 안에는 아무 것도 들어가면 안됨.'''
```
- 종목
```py
event = ['33', '22', '44', '55', '66', '77', '3BLD', 'FMC', 'OH',
         'Clock', 'Mega', 'Pyra', 'Skewb', 'SQ-1', '4BLD', '5BLD', 'MBLD'] '''WCA 공인종목'''
```

- 기록
```py
worst = 0.0001 '''개인 최저기록(Ao 5)'''
best = 1000000.0 '''개인 최고기록(Ao 5)'''
```

- 종목 코드 입력부
```py
ev = int(input('종목 코드: ')) '''종목 코드 입력'''
print('당신이 선택한 종목은', event[ev-1], '입니다.') '''선택한 종목 안내'''
print('')
```



## 🐧 **Credit**
- Maker : Leo Kim([@llleeo0421](https://github.com/llleeo0421))
  - E-mail : dev.augustleo@gmail.com
  - GitHub : [@August-Leo-0805](https://github.com/August-Leo-0805)
  - Twitter : [@llleeo0421](https://www.twitter.com/llleeo0421)
  - Linkedin : [@augustleo](https://www.linkedin.com/in/augustleo)
  - Blog : [날 찾아온 낯선 여행자](https://llleeo0421.tistory.com)
