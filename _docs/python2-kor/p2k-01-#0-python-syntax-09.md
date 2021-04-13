---
# layout : rchive
title: "Numbers"
permalink: /p2k-python-syntax-09/
excerpt: "We learn about Numbers of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 숫자 변수에 대하여 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 9. Numbers    

변수들은 숫자 값들을 담을수 있다.    
Python 에서 가장 간단한 숫자는 **정수(integer)** 이다.   
정수는 소수점이 없는 숫자이다. 

```python
int1 = 1
int2 = 10
int3 = -5
```

A number with a decimal point is called a **float**. You can define **floats** with numbers after the decimal point or by just including a decimal point at the end:
소수점이 있는 숫자를 **실수(float)** 라고 부른다.    


```python
float1 = 1.0
float2 = 10.
float3 = -5.5
```

You can also define a **float** using scientific notation, with `e` indicating the power of `10`:
실수(float)형 변수는 과학적 표기에도 사용할수 있습니다.     
10의 거듭제곱으로 `e`를 사용할수 있습니다.     

```python
# this evaluates to 150:
float4 = 1.5e2
```
<br>

**설명:** [ 요약 ]      
• Ch9. Numbers 에서는 숫자를 학습한다.     
• Python 에서는 숫자 관련 변수는 정수(integer)와 실수(float) 2 종류가 있다.    
• 정수는 소숫점 이하를 표현할수 없다.    
• 실수는 소수점을 표현할 수 있다.     
• 생성되는 변수가 정수형인지, 실수형인지는 해당 값을 대입 할때 정해진다.    
• 즉, 변수에 정수를 넣으면 정수형 변수가 되고, 실수를 넣으면 실수형 변수가 된다.   
• 과학적 표기법인(scientific notation) `e` 도 실수(float)형으로 표현한다. 
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 당신은 쇼핑을 할 예정이다.    
  당신이 가진 예산 안에서 구매할 식료품 목록을 만들어 보자.    
  변수 `cucumbers`에 당신이 구매하고자 하는 오이의 갯수를 저장하자.    
  적어도 1 개 이상은 구매해야 하며, 적당한 데이터 타입(정수, 실수)로 만들자.   
  가게에서는 오이들을 잘라서 팔지는 않는다.    

* 오이 1개의 가격은 `3.25` 더블론즈 입니다.    
  오이 한개당 가격을 변수 `price_per_cucumber`에 저장하세요.    

* 변수 `total_cost`를 새로 만들고, 구매할 전체 오이수와 오이 1개의 값을 곱하여 저장한다.    

* 변수 `total_cost`의 값을 출력하라.    

* 출력된 값은 어떤 데이터 형태인가?


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* 곱하기 연산자는 `*` 를 사용하라. 

<p style="page-break-before: always;"></p>     
<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
cucumbers = 3
price_per_cucumber = 3.25

total_cost = cucumbers * price_per_cucumber
print total_cost
```

**설명:** [ Solution ]    
• 오이가 3개, 개당 가격이 3.25 이다.    
• 전체 오이의 가격은 cucumbers * price_per_cucumber 이다.    
• 변수 total_cost 에 계산한 결과 값을 저장한다.    
• 정수 3과 실수 3.25의 계산값은 실수로 자동 계산된다.    
• 입력 된 두 값( 3 , 3.25 ) 중 하나 ( 3.25 )가 실수 값 이다.    
• Python은 내부적으로 실수로 계산되어지고, total_cost 는 실수형 변수가 된다.
{: .notice--info}


**결과**     
``` 
9.75
```   
