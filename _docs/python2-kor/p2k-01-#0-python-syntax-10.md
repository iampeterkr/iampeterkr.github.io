---
# layout : rchive
title: "Two Types of Division"
permalink: /p2k-python-syntax-10/
excerpt: "We learn about Two Type of Division of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 2가지 형태의 나눗셈에 대하여 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 10. Two Types of Division     

In Python 2, when we divide two integers, we get an integer as a result. When the quotient is a whole number, this works fine:
Python2 에서, 우리는 정수 2개를 나누기하면, 정수값을 몫으로 가진다.    
몫이 정수이면, 문제가 없다.    

```python
quotient = 6/2
# the value of quotient is now 3, which makes sense
```

하지만, 숫자가 2로 나누어지지 않는 경우라면, 그 결과 값은 정수에서 소수점이 잘라진 값을 얻게 된다.    
다르게 이야기하면, 몫의 소수점 이하 값이 버려진다.    
여러분은 소수점이 있는 값을 받을것을 기대했지만, 반내림 한 정수값을 받으면 당황하게 될 겁니다.     

```python
quotient = 7/2
''' the value of quotient is 3, even though the result
  of the division here is 3.5 '''
```

실수(float)로 그 결과값을 받을려면, 프로그래머는 분자값 또는 분모값을 실수로 변형해 주어야 한다.    

```python
quotient1 = 7./2
# the value of quotient1 is 3.5
quotient2 = 7/2.
# the value of quotient2 is 3.5
quotient3 = 7./2.
""" the value of quotient3 is 3.5
 An alternative way is to use the float() method: """

quotient1 = float(7)/2 
# the value of quotient1 is 3.5
```

**설명:** [ 요약 ]       
• Ch10. Two Types of Division 에서는 나눗셈 계산에서 주의할점을 학습한다.    
• 두수를 나누어 정수로 딱 떨어지면, 해당 변수를 정수형 변수로 인식한다.    
• 정수 ( 7/2 ) 를 계산하면 3.5 이다. 3.5는 실수이다.    
• 하지만, Python2 에서는 정수( 3 )만 남고, 나머지 0.5는 버린다.    
• 이런 실수를 방지하기 위하여 값을 대입 할때 주의 해야한다.    
• 항상, 계산한 결과값이 실수일 것을 대비하여야 한다.     
• 입력값을 실수형으로 넣어 준다. ( e.g. 7.0 / 3)    
• 입력값을 float(7) 실수형 값으로 변경 후 계산 되도록 한다.
{: .notice--info}    

**설명:** [ Python3 ]    
• python3 에서는 이 문제를 해결 하였다.    
• 정수 ( 7/2 ) 을 계산하면 3.5 로 자동 계산된다.
{: .notice--info}



<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 당신은 식료품 가게에서 구매한 100 개의 오이를 집으로 들고 왔다. 그리고 당신은 룸메이트 5명과 오이를 나누어 가지려고 한다. (본인 포함 6명)    

* 변수 `cucumbers`를 만들고, 여기에 값 `100` 을 저장하고, 변수 `num_people`를 만들고, 여기에 값 `6`을 할당하라.    

* Create a variable called `whole_cucumbers_per_person` that is the integer result of dividing `cucumbers` by `num_people`.
* 변수 `whole_cucumbers_per_person`을 만들고, 변수 `cucumbers`를 변수 `num_people`로 나눈 정수값을 할당하라.    

* 변수 `whole_cucumbers_per_person`을 출력하라.    

* 당신은 숫자가 딱 떨어지지 않고, 나누지 못한 남은 오이를 버리고 싶지 않을 것이다.    

* 변수 `float_cucumbers_per_person` 을 생성하고, 여기에, 변수 `cucumbers`를 변수 `num_people`로 나눈 실수값을 할당하라.     

* 변수 `float_cucumbers_per_person` 를 출력하라.    

**설명:** [ 요약 ]     
• 100 개의 오이를 룸메이트 6 명과 나눠 가지는 프로그램을 만든다.     
• 변수 cucumbers 에  100 을 대입하라.    
• 변수 num_people 에 6 을 대입하라.     
• 변수 whole_cucumbers_per_person 에 (cucumbers / num_people)을 대입하라.    
• 변수 whole_cucumbers_per_person 를 출력하라.    
• 16 이 출력되어 놀라운가?     
• 예상한 바로는 100/6 은 16.66...으로 출력을 예상했는가?     
• 변수 float_cucumbers_per_person 를 만들고, 실수 값이 출력 되도록 고쳐라.    
• 변수 float_cucumbers_per_person 를 출력하라.
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* 당신은 분자 또는 분모값을 실수로 변환하여 사용할 수 있다.    

```python
quotient_with_decimals = float(5)/2
#yields 2.5
```

**설명:** [ Hint ]    
• float() 함수를 사용하라. 
{: .notice--info}


<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
cucumbers = 100
num_people = 6

whole_cucumbers_per_person = cucumbers/num_people
print whole_cucumbers_per_person

float_cucumbers_per_person = float(cucumbers)/num_people
print float_cucumbers_per_person
```

**설명:** [ Solution ]    
• float_cucumbers_per_person 변수를 계산할때, float() 함수를 사용한다.    
• float(cucumbers) 를 실수로 변경하여 계산한다.
{: .notice--info}

**결과**
```
16
16.6666666667
```
