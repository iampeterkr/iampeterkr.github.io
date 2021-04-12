---
# layout : rchive
title: "Arithmetic"
permalink: /p2k-python-syntax-06/
excerpt: "We learn about Arithmetic of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 산술 연산자를 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 6. Arithmetic    

컴퓨터들이 예외적으로 잘할 수 있는 한가지는 계산하는 것이다.    
더하기, 빼기, 곱하기, 나누기, 등 다른 숫자 계산들은 모든 대부분 프로그래밍에서 수행할 수 있고, Python 도 예외는 아니다.     
아례 몇 가지 예를 보자...


```python
mirthful_addition = 12381 + 91817
amazing_subtraction = 981 - 312
trippy_multiplication = 38 * 902
happy_division = 540 / 45
sassy_combinations = 129 * 1345 + 120 / 6 - 12
```

상단을 보면, 산술 계산이 있고, 각 변수에 할당되어 있다.    
변수는 각 계산식의 결과 값을 저장하고 있을 것이다.   
산술식의 조합들은 연사자들의 일반적 처리 순서에 따라 동작된다.    

Python 은 모듈 연산자로 불리는 나눗셈과 비슷한 연산자를 제공합니다.    
모듈 연산자는 `%` 로 사용되며, 그 결과값은 나누기로 수행된후 남은 나머지를 반환 합니다.      

```python
is_this_number_odd = 15 % 2
is_this_number_divisible_by_seven = 133 % 7
```   

상단의 코드 예에서, 우리는 15 를 2로 나눈후 남은 나머지를 찾기 위하여 모듈 연산자를 사용한다.    
왜냐하면, 15는 홀수 이기에 계속 나누면 1 이 남게 된다.    

우리는 또한 133/7 의 나머지도 확인한다.    
왜냐하면, 133 을 7 로 나누면 나머지가 없다.     
133%7 의 계산값을 구하면 나머지는 0 이다. 


**설명:** [ 요약 ]     
• Ch6. Arithmetic 에서는 수식을 학습한다.     
• 컴퓨터의 많은 기능 중 하나는 계산하는 것이다.     
• Python도 사칙연산( + , − , × , ÷ )을 지원한다.    
• Python 에선 × → * , ÷ → / 로 표시한다.    
• 모듈(module)연산자도 지원한다.     
• 모듈 연산자 중 하나인 % 는 나머지를 계산 해준다.    
• e.g. 15 % 2 = 1, 만약 133 % 7 같이 딱 떨어지면 나머지는 0 이다.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 변수 `product` 를 만들고, 이 변수에 2개의 숫자를 곱하여 대입하라.    

* 1398 / 11 의 너머지 값은 무엇일까? 변수 `remainder`에 그 결과값을 저장하라.     

**설명:** [ 요약 ]    
• 변수 product 를 만들어라.    
• 변수 product 에 2개의 숫자를 곱하여 대입하라.  
• 1398 / 11  의 나머지는 무엇일까?     
• 변수 remainder 를 만들어라.    
• 변수 remainder 에 1397 / 11 의 나머지 값을 저장하라.  
{: .notice--info}

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 변수를 만드는것은 다른 뭔가를 = 시키는 것만큼 단순하다는 것을 기억하라. 변수 quotient`를 만들고, 아래와 같이 값을 정의 할수 있다.   

```python
quotient = 30 / 5
```

* 나머지를 찾는 모듈 연산자는 `%` 를 사용한다는 것을 기억하라.    

```python
1908 % 3
```

* 1908 을 3 으로 나누어 떨어지기에, 값은 0 일 것이다. 

**설명:** [ Hint ]    
• 상기 예는 변수 quotient 에 두 수를 나눗셈 한 것이다.    
• % 는 나머지를 구하는 모듈(module) 연산자 이다. 
{: .notice--info}

<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
product = 18 * 13
remainder = 1398 % 11
```

**설명:** [ Solution ]     
•  곱셈 연산자는 * 이다.     
•  나머지를 구하는 모듈(module) 연산자는 % 이다. 
{: .notice--info}    


**결과**     
``` 
#skip
```   
