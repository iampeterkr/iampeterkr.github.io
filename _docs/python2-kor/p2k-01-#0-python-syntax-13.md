---
# layout : rchive
title: "ValueError"
permalink: /p2k-python-syntax-13/
excerpt: "We learn about ValueError of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 값의 오류에 대하여 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 13. ValueError    


Python은 입력되는 값에 따라 변수 타입이 자동으로 정해진다.     
값 `7` 을 가지는 변수는 정수형 변수가 되고, 값 `7.` 을 가지는 변수는 실수형 변수가 되고, 값 `"7"` 을 가지는 변수는 문자열 변수가 된다.   
가끔식 여러분은 입력된 데이타 값의 종류를 바꾸는것이 필요할 때가 있다.    
예를 들면, 문자열의 일부로 정수를 출력하고 싶을때, 우리는 정수를 문자열로 먼저 바꾸어야 한다. 우리는 python 에서 제공하는 내장함수 `str()` 를 사용할 수 있다.    

```python
age = 13
print "I am " + str(age) + " years old!"
```   

다음과 같이 출력 될 것이다. :   

``` python
>>> "I am 13 years old!"
```

**설명:** [ 요약 ]       
• Ch13. ValueError 에서는 출력시 주의할 점을 학습한다.     
• 변수 age 는 정수 13 이 대입 되었기에 정수형 변수가 된다.     
• 정수형 변수 age 를 문자열로 출력 하기 위해선, 함수 str()를 사용한다.    
• 정수형 변수 age 를 str(age)로 바꾸면 변수 age 는 문자열 형태로 출력된다.    
• *주의)* 정수형 age 를 출력 할때 문자열 형태로 출력하는 것이지, age 가 문자열형 변수가 되는것은 아니다.  
{: .notice--info}


비슷한 예로, 여러분이 문자열 `"7"` 을 가지고, 계산을 하려면, 문자열 `"7"` 을 숫자로 변경해주어야 한다.    
이때, 여러분은 `int()` 함수를 이용할 수 있다.     


```python
number1 = "100"
number2 = "10"

string_addition = number1 + number2 
#string_addition now has a value of "10010"

int_addition = int(number1) + int(number2)
#int_addition has a value of 110
```
**설명:** [ Learn ]     
• 변수 number1 , number2 는 문자형 변수이다.     
• Python 에서는 문자형 데이타 이지만, 데이타가 숫자를 뜻하면 계산을 할수가 있다.     
• e.g. 문자열 "4", "5.0"    
• 단, 계산할때, 함수 int()를 사용하여 정수형으로 바꾸어 주어야 한다.     
• *주의)* 문자형 number1 , number2를 계산 목적으로 정수형으로 바꾸어 주는 것이지,변수 number1 , number2 에 들어있는 데이타가 정수형이 되는것은 아니다.  
{: .notice--info}

`int()` 함수에서 실수를 사용하면, 소수점 절삭이 된다.    
소수점을 보존하려면, `float()`를 사용해야 한다.    

```python
string_num = "7.5"
print int(string_num)
print float(string_num)
>>> 7
>>> 7.5
```

**설명:** [ Learn ]    
• 함수 int()를 사용하면 정수형 값으로 변경되어 반환된다.    
• 함수 float()를 사용하면 실수형 값으로 변경되어 반환된다.  
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 변수 `product`를 생성하고, 그 변수에 `float_1`과 `float_2`를 곱한 값을 대입하라.    

* 변수 `big_string` 생성하고, 아래와 같이 출력된다.         

```
The product was X
```
* X 의 위치에는 변수 `product` 값이 출력된다.        

**설명:** [ Instruction ]     
• 변수 product 를 만들어라.    
• 변수 product 에 변수 float_1 , float_2 곱한 값을 대입하라.  
• 변수 big_string 를 만들어라.    
• 변수 big_string 에 *The product was* + str(product) 를 대입하여 출력되게 하라.   
{: .notice--info}

<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* 여러분은 숫자값을 문자값으로 변환후, 문자열들을 `+` 연산자를 이용하여 연결할수 있다.    

```python
"I have " + str(18) + " dogs at home!"
```

**설명:** [ Hint ]    
• 변수 product 를 문자형으로 변환하라. 
{: .notice--info}


<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
float_1 = 0.25
float_2 = 40.0

product = float_1 * float_2
big_string = "The product was " + str(product)
```

**설명:** [ Solution ]     
• float 형(type) 변수 product 를 문자열 형(type) 으로 변환 해주고 대입한다. 
{: .notice--info}



**결과**     
```
#skip 
```   
