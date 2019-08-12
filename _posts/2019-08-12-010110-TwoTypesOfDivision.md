---
layout: single
title: "10.Two Types of Division"
---
[#Python #Codecademy #코드카데미 #한글 #설명 #정답 # solves # 목록]     
<br>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/line.png)    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 10. Two Types of Division     

In Python 2, when we divide two integers, we get an integer as a result. When the quotient is a whole number, this works fine:

```python
quotient = 6/2
# the value of quotient is now 3, which makes sense
```

However, if the numbers do not divide evenly, the result of the division is truncated into an integer. In other words, the quotient is rounded down to a whole number. This can be surprising when you expect to receive a decimal and you receive a rounded-down integer:

```python
quotient = 7/2
''' the value of quotient is 3, even though the result
  of the division here is 3.5 '''
```

To yield a float as the result instead, programmers often change either the numerator or the denominator (or both) to be a float:

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

**설명:** [ Learn ]       
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

* You have come home from the grocery store with `100` cucumbers to split amongst yourself and your `5` roommates (`6` people total).

* Create a variable `cucumbers` that holds `100` and `num_people` that holds `6`.

* Create a variable called `whole_cucumbers_per_person` that is the integer result of dividing `cucumbers` by `num_people`.

* Print `whole_cucumbers_per_person` to the console.

* You realize that the numbers don't divide evenly and you don't want to throw out the remaining cucumbers.     
* Create a variable called `float_cucumbers_per_person` that holds the float result of dividing `cucumbers` by `num_people`.

* Print `float_cucumbers_per_person` to the console.

**설명:** [ Instruction ]     
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
* You can do float division by casting either the numerator or denominator as a float:

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


<p style="page-break-before: always;"></p>     
<br>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/line.png)  