2일차 실습예제 및 예시답안
-------------

### 1. 밑줄 친 부분에 알맞은 대입문을 사용하여 width(너비) 변수에는 30,height(높이) 변수에는 60 값이 출력되도록 하시오.
'''  
  
\>>>  
\>>>    
\>>> print(width)  
30  
\>>> print(height)  
60  
  
'''  
```
#-----<예시 답안>------

  width = 30
  height = 60

  print(width)
  print(height)
  
 ```
 #

### 2. width와 height라는 변수에 각각 30,60 값을 할당한 후 이 두 변수를 이용하여 다음과 같이 사각형의 면적(area)을 구하는 프로그램을 작성하시오.

'''  
  
사각형의 면적 1800  
  
'''

 ```
#-----<예시 답안>------

  width = 30

  height = 60

  area = width * height

  print("사각형의 면적",area)
 ```
 #
 
 
### 3. width와 height라는 두 변수에 각각 40, 20 값을 할당한 후 이 두 변수를 이용하여  다음과 같이 삼각형의 면적(area)을 구하는 프로그램을 작성하시오.

```  
#-----<예시 답안>------

  width=40
  height = 20

  area = width *height

  print("삼각형의 넓이:",area)
  ```
 #   
 

### 4. 정사각형의 면적을 구하기 위하여 사용자로부터 밑변의 길이를 정수로 입력받아서 다음과 같이 출력하시오.
### (힌트: int(input('정사각형의 밑변을 입력하시오:'))를 사용함.)

'''  
  
정사각형의 밑변을 입력하시오 : 40  
정사각형의 면적: 1600
  
'''  
  ```
#-----<예시 답안>------

  width = int(input("정사각형의 밑변을 입력하시오 : "))
  print("정사각형의 면적:",width*width)
  ```
 #     
 

### 5. print() 함수와 + 연산을 9개 사용하여 1에서 10까지 정수의 합을 다음과 같이 화면에 출력해보자.

'''  
  
\>>>________________________  
1에서 10까지의 합: 55  
  
'''  

  ```
#-----<예시 답안>------
  
  width = 30

  height = 60

  area = width * height

  print("사각형의 면적",area)
```
 #  
 

### 6. width와 height라는 변수에 각각 30,60 값을 할당한 후 이 두 변수를 이용하여 print() 함수와 * 연산을 9개 사용하여 10!을 다음과 같이 화면에 출력해보자.

'''  
  
\>>> ____________  
10! = 3628800  
  
'''  
  ```
#-----<예시 답안>------
  
res = 1
operand = 10

for i in range(10):
    res *= operand
    operand -= 1

print("10! =", res)
  ```
 # 
    
 

### 7. width와 height라는 변수에 각각 30,60 값을 할당한 후 이 두 변수를 이용하여 다음과 같이 2에서 6까지의 제곱 값을 표로 출력하는 프로그램 squar_table.py를 작성하시오. 아래 결과와 같이 a는 2에서 6까지 증가되는 수가 있으며, n은 2의 값을 가진다. 그리고 a n에 해당하는 부분은 실제 값을 넣어서 2 2와 같은 수식의 결과가 출력되도록 하시오.

'''  
  
a    &nbsp;   n   &nbsp;    a**n  
2    &nbsp;   2   &nbsp;     4  
3    &nbsp;   2   &nbsp;    9  
4    &nbsp;   2   &nbsp;    16  
5    &nbsp;   2   &nbsp;    25  
6    &nbsp;   2   &nbsp;    36  
  
'''  
 ```
 

#-----<예시 답안>------
a=2
n=2
print('a\t n\t a**n')
for i in range(5):
    print(a,'\t',n,'\t',a**n)
    a+=1
 ```
 #
  
  
### 8. 반지름 값 11을 변수 radius에 대입하고, 이 반지름을 가진 원의 둘레와 면적을 다음과 같이 출력하라. 이 값을 구하기 위하여 PI=3.141592라는 변수를 사용하시오.

'''  

원의 반지름 = 11, 원의 둘레 =69.115024, 원의 면적 = 380.13263200000006  

'''  

 ```
 
#-----<예시 답안>------
radius = 11
PI=3.141592

print("원의 반지름 =",radius,", 원의 둘레=",2*PI*radius,", 원의 면적=", float(PI*radius**2))
 ```
 #

 
### 9. 사용자로부터 반지름 값을 입력받아서, 이 반지름을 가진 원의 둘레와 면적을 다음과 같이 출력하라. 이 값을 구하기 위하여 PI=3.141592라는 변수를 사용하시오.

'''  
원의 반지름을 입력하세요 : 11  
원의 둘레 = 69.115024, 원의 면적 = 380.13263200000006  
'''  

 ```
 
#-----<예시 답안>------

PI=3.141592
radius = int(input('원의 반지름을 입력하세요: '))
print("원의 둘레 =",2*PI*radius,"원의 면적",PI*radius**2)
  ```
 #
### 10. 거듭제곱 연산자(**)을 이용하여 어떤 수의 제곱근()을 구할 수 있다. 1부터 10까지의 수의 제곱근을 구해서 다음과 같이 출력하는 sqrt_table.py라는 프로그램을 작성하시오.

'''  
  
2의 제곱근 =   
3의 제곱근 =  
4의 제곱근 =   
5의 제곱근 =   
6의 제곱근 =   
7의 제곱근 =  
8의 제곱근 =   
9의 제곱근 =  
10의 제곱근 =   
  
'''  
 ```
#-----<예시 답안>------

for i in range(1,11):
    print(i,"의 제곱근 =", i**(1/2))
 ```
 #
 
 
 
 
### 11. 피타고라스 정리는 어떠한 직각삼각형에서든 빗변 c의 제곱은 밑변 a의 제곱과 높이 b의 제곱을 더한 값과 같다는 것이다.

'''  
  
c**2 = a**2 + b**2  
  
'''  

### 밑변과 높이를 정수로 입력받아 빗변의 길이를 계산하는 코드를 작성하라.

'''
  
밑변을 입력하시오 : 5  
높이를 입력하시오 : 12  
빗변 : 13.0 
  
'''  
```
#-----<예시 답안>------

width = int(input('밑변을 입력하시오 :'))
height = int (input('높이를 입력하시오 :'))

res = (width**2 + height**2)**(1/2)

print("빗변 :",res)
```
 #
 
 
 
### 12. 비트 이동 연산자를 이용하여 다음과 같이 2의 거듭제곱 수 10개를 다음과 같이 표시하라.

'''  
  
2   4   8   16  32  64  128 256 512 1024  
  
힌트 아래 결과를 참고할 것  
2<<0 = 2  
2<<1 = 4  
2<<2 = 8  
  
'''  
 ```
#-----<예시 답안>------

for i in range(0,10):
    print(2<<i,end='')
  ```
 #
 
 
 
### 13. 사용자의 키보드 입력을 통해 n값을 입력받아, 주어진 정수 n이 짝수이면 True, 홀수이면 False를 출력하는 코드를 작성해 보라. m가 20,21인 경우에 대하여 다음과 같이 출력하여라.

'''  
  
정수를 입력하세요: 20  
이 수가 짝수인가요? True  
  
정수를 입력하시요: 21  
이 수가 짝수 인가요? False  
  
'''
 ```
 
#-----<예시 답안>------

num1 = int(input('정수를 입력하세오: '))
print('이 수가 짝수인가요? ',(num1%2==0))

print('')

num2 = int(input('정수를 입력하세오: '))
print('이 수가 짝수인가요? ',(num2%2==0))

print(5>10)
  ```
 #
 
 
 
### 14. 사용자로부터 입력받은 정수 값 n이 0에서 100의 범위 안에 있는 짝수인지 그렇지 않은지를 판단하는 코드를 작성하여 다음과 같은 결과가 나타나도록 하여라.

'''  
  
정수를 입력하세요 : 120  
입력된 정수는 0에서 100의 범위 안에 있는 짝수인가요? False  
  
정수를 입력하세요 : 88  
입력된 정수는 0에서 100의 범위 안에 있는 짝수인가요? True  
  
'''  
 ```
 
#-----<예시 답안>------

num1 = int(input("정수를 입력하세요 :"))
print("입력된 정수는 0에서 100의 범위 안에 있는 짝수인가요?",(0<num1 and num1<100 and num1%2==0))

print(' ')

num2 = int(input("정수를 입력하세요 :"))
print("입력된 정수는 0에서 100의 범위 안에 있는 짝수인가요?",(0<num2<100 and num2%2==0))
 ```
 #
 
 
 
### 15. 사용자로 부터 2개의 정수 a와 b를 입력으로 받은 다음 a를 b로 나눈 몫과 나머지를 다음과 같이 출력하시오.

'''  
  
정수 a를 입력하세요: 202  
정수 b를 입력하세요: 50  
a/b의 몫 : 4  
a/b의 나머지 : 2  
  
'''  
 ```
 
#-----<예시 답안>------
su1 = int(input("정수 a를 입력하세요: "))
su2 = int(input("정수 b를 입력하세요: "))

print("a/b의 몫 :",su1//su2)
print("a/b의 나머지:",su1%su2)
 ```
 #
 
 
 
 
### 16. 사용자로부터 세자리 정수를 입력으로 받으시오. 이때 입력받은 정수 n에 대한 백의 자리, 십의 자리, 일의 자리 십진수 값을 다음과 같이 출력하시오.
### ( 힌트: //연산자와 %연산자를 사용하시오. 예를 들어 백의 자리는 n//100을 통해서 구할 수 있다.)

'''  
  
세자리 정수를 입력하시오 : 348  
백의 자리: 3  
십의 자리: 4  
일의 자리: 8  
  
'''  
 ```
#-----<예시 답안>------

num = int(input("세자리 정수를 입력하시오 :"))
print("백의 자리: ", num//100)
print("십의 자리: ",(num//10)%10)
print("일의 자리: ",num%10)
 ```
 #
 
 
 
 
### 17. 사용자로부터 세자리 정수를 입력으로 받으시오. 이때 입력받은 정수를 다음과 같이 역순으로 출력하시오
### (힌트: // 연산자와 % 연산자를 사용하시오.)

'''  
  
세 자리 정수를 입력하시오 : 349  
9  
4  
3  
  
'''  
 ```
 
#-----<예시 답안>------

num = int(input("세자리 정수를 입력하시오 :"))

for i in range(3):
    print(num%10)
    num = num //10
 ```
 #
