---
# layout : rchive
title: "Arithmetic"
permalink: /p2k-python-syntax-06/
excerpt: "We learn about Updating Variables of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 변수의 값을 변경 시키는것을 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 7. Updating Variables    

변수의 내용들을 변경시키는 것은 필수적인 작업들중 하나이다.     
프로그램의 흐름이 진행됨에 따라, 변경되어진 데이타는 변수에 반영되어야 한다.    

```python
fish_in_clarks_pond = 50

print "Catching fish"

number_of_fish_caught = 10

fish_in_clarks_pond = 
fish_in_clarks_pond - 
number_of_fish_caught
```

위의 예에서, 연못에 50 마리가 있다.    
이후, 물고기 10 마리를 잡았고, 원래 연못에 있던 50 마리에서 10마리를 제외한 값으로 변경해주어야 한다.    
최종적으로 변수 `fish_in_clarks_pond` 에는 40 마리의 물고기가 들어가 있을 것이다.    

원래의 변수에 더하거나 빼거나하여 원래의 변수를 업데이트 하는것은 변수를 빠르고 쉽게 읽을수 있게 만든다.  

**설명:** [ Learn ]       
• Ch7. Updating Variables 에서는 변수 변경을 학습한다.    
• 변수 fish_in_clarks_pond 에 50 을 대입하라.    
• 변수 number_of_fish_caught 에 10 을 대입하라.    
• 변수 fish_in_clarks_pond = fish_in_clarks_pond - number_of_fish_caught 값을 저장한다.       
• 변수 fish_in_clarks_pond 에는 50 - 10 의 값이 계산된 40 이 저장된다. 
{: .notice--info}


```python
money_in_wallet = 40
sandwich_price = 7.50
sales_tax = .08 * sandwich_price

sandwich_price += sales_tax
money_in_wallet -= sandwich_price
```

위의 예에서, 우리는 판매세가 포함된 샌드위치 가격을 사용한다.    
판매세를 계산한후, 우리는 샌드위치의 전체 값에 포함 시킨다.    
마지막으로, 우리는 우리의 지갑 `money_in_wallet`에서 판매세가 포함된 샌드위치 값을 뺀다.    


**설명:** [ 요약 ]     
• 변수에 숫자를 곱하여도 계산 할 수 있음을 보여준다.     
• +=, -= 연산자를 활용하는 법을 보여준다.     
• a = a + 1, a += 1, 이 두 표현은 같은 표현이다.    
• a = a - 1, a -= 1, 이 두 표현은 같은 표현이다. 
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    
* 우리는 작년에 얼마나 비가 왔었는지를 파악하려고 한다.    
  9월부터 12월까지의 비의 양을 변수 `annual_rainfall` 에 누적하여 변경하여라.        

**설명:** [ Instruction ]    
• 작년에 얼마나 많은 비가 왔는지 계산 하는 문제이다.    
• 변수 annual_rainfall 에, 9월 부터 12월 까지의 비의 양을 누적하여 값을 더하라. 
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* Use the `+=` syntax to add a value to an existing variable:
* `+=` 구문을 사용하여 기존 변수에 값을 더하라.       

```python
annual_rainfall += september_rainfall
```

* 나머지 달들도 모두 더하라.    

**설명:** [ Hint ]    
• += 연산자를 사용하라. 
• A += B 는 A = A + B 이다.
{: .notice--info}

<p style="page-break-before: always;"></p>     
<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    

```python
january_to_june_rainfall = 1.93 + 0.71 + 3.53 + 3.41 + 3.69 + 4.50
annual_rainfall = january_to_june_rainfall

july_rainfall = 1.05
annual_rainfall += july_rainfall

august_rainfall = 4.91
annual_rainfall += august_rainfall

september_rainfall = 5.16
annual_rainfall += september_rainfall

october_rainfall = 7.20
annual_rainfall += october_rainfall

november_rainfall = 5.06
annual_rainfall += november_rainfall

december_rainfall = 4.06
annual_rainfall += december_rainfall
print annual_rainfall
```

**설명:** [ Solution ]    
• += 연산자를 사용하여 매월 비의 양을 추가 한다.     
• 변수 annual_rainfall 의 마지막 값을 출력 한다. 
{: .notice--info}


**결과**     
``` 
45.21
```   
