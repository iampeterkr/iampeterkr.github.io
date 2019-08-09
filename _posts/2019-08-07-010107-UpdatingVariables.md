---
layout: single
title: "07.Updating Variables"
---
[#Python #Codecademy #코드카데미 #한글 #설명 #정답 # solves # 목록]     

<br>
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 7. Updating Variables    

Changing the contents of a variable is one of the essential operations. As the flow of a program progresses, data should be updated to reflect changes that have happened.

```python
fish_in_clarks_pond = 50

print "Catching fish"

number_of_fish_caught = 10

fish_in_clarks_pond = 
fish_in_clarks_pond - 
number_of_fish_caught
```

In the above example, we start with `50` fish in a local pond. After catching `10` fish, we update the number of fish in the pond to be the original number of fish in the pond minus the number of fish caught. At the end of this code block, the variable `fish_in_clarks_pond` is equal to `40`.

Updating a variable by adding or subtracting a number to the original contents of the variable has its own shorthand to make it faster and easier to read.

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

In the above example, we use the price of a sandwich to calculate sales tax. After calculating the tax we add it to the total price of the sandwich. Finally, we complete the transaction by reducing our `money_in_wallet` by the cost of the sandwich (with tax).


**설명:** [ Learn ]     
• 변수에 숫자를 곱하여도 계산 할 수 있음을 보여준다.     
• +=, -= 연산자를 활용하는 법을 보여준다.     
• a = a + 1, a += 1, 이 두 표현은 같은 표현이다.    
• a = a - 1, a -= 1, 이 두 표현은 같은 표현이다. 
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    
* We're trying to figure out how much it rained in the past year! Update the `annual_rainfall` variable to include the values from September to December.

**설명:** [ Instruction ]    
• 작년에 얼마나 많은 비가 왔는지 계산 하는 문제이다.    
• 변수 annual_rainfall 에, 9월 부터 12월 까지의 비의 양을 누적하여 값을 더하라. 
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* Use the `+=` syntax to add a value to an existing variable:

```python
annual_rainfall += september_rainfall
```

* Add all of the remaining months to


**설명:** [ Hint ]    
• += 연산자를 사용하라.  
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

<br>
<br>    
<br>    
<p style="page-break-before: always;"></p>     
<br>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/line.png)  