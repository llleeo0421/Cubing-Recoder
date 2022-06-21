# 🐧 **Ep 1. 파이썬과 기본 문법**

## 🐧 **What is a Python?**
- 네덜란드의 귀도 반 로섬 창시하고, 1991년에 발표된 인터프리터 방식의 프로그래밍 언어
- 영어와 비슷해 읽고 쓰기 쉬운 특유의 문법
- 전 세계의 개발자들로부터 만들어진 수많은 패키지들 덕분에 사용할 수 있는 용도가 무궁무진해짐
  - 2010년대 중반부터는 주류 프로그래밍 언어로 당당히 올라서게 되었음
  
## 🐧 **변수**
- 변수명 만들기
	1. 시작은 문자(English),  _(밑줄)
	2. 공백, -(대시)사용불가
	3. 대소문자 구분
	4. 예약어(if, else, while...) ❌
  
- 변수형
```python
int a=7 '''정수'''
float b=4.21 '''실수''' 
list birth=[19940728, 19950501, 19950917, 19960126, 19970404, 19970909, 19990618] '''배열'''
str h='HyoJeong'  '''문자 1'''
str omg="OH MY GIRL"  '''문자 2'''
bool t=true  '''참'''
bool f=false '''거짓'''
```

## 🐧 **출력**
``` python
print ('이름') '''문자'''
print (a) '''변수 1개'''
print (a, b)  '''변수 여러개'''
print ('이름은', a) '''변수, 문자 동시 출력'''
```

## 🐧 **입력**
```python
a=input('안내 문구') '''문자형 변수 입력'''
a=변수형(input()) '''원하는 형태(정수, 실수등등)의 변수 입력'''
```

## 🐧 **연산자**
- 산술연산
```python
a+b '''덧셈'''
a-b '''뻴셈'''
a*b '''곱셈'''
a/b '''나눗셈'''
a%b '''나머지'''
```
- 비교 연산
```python
a<b '''a는 b보다 작음'''
a<=b '''a는 b보다 작거나 같음'''
a>b '''a는 b보다 큶'''
a>=b '''a는 b보다 크거나 같음'''
a==b '''a는 b와 같음'''
```
- 논리연산
```python
a and b '''둘다 만족'''
a or b '''하나만 만족'''
```
- 대입연산
```python
i=i+1
```

## 🐧 **조건문**
- if 문
```python
if '조건식' : 
elif '조건식' :
else : 
```
```python
n=int(input())
if n%4==0:
  print('나머지 : 없음')
elif n%4==1:
  print('나머지 : 1')
elif n%4==2:
  print('나머지 : 2')
else :
	print('나머지 : 3')
```
- for 문
```python
for i in range () :
```
```python
sum=0
for i in range(101)
	sum=sum+i
print(sum)
```
- while 문
```python
while 조건식 :
```
```python
i=0
while i<10 :
  print(i+1)
  i+=1
```
```python
i=0
sum=0
while i<11 :
  sum=sum+i
  i+=1
	print(sum)
```

## 🐧 **Credit**
- Maker : Leo Kim([@llleeo0421](https://github.com/llleeo0421))
  - E-mail : dev.augustleo@gmail.com
  - GitHub : [@August-Leo-0805](https://github.com/August-Leo-0805)
  - Twitter : [@llleeo0421](https://www.twitter.com/llleeo0421)
  - Linkedin : [@augustleo](https://www.linkedin.com/in/augustleo)
  - Blog : [날 찾아온 낯선 여행자](https://llleeo0421.tistory.com)
