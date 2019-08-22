---
layout: single
title: "11.Multi Line Strings"
---
[#Python #Codecademy #코드카데미 #한글 #설명 #정답 # solves # 목록]     
<br>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/line.png)    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 11. Multi-line Strings     


We have seen how to define a string with single quotes and with double quotes. If we want a string to span multiple lines, we can also use triple quotes:

```python
address_string = """136 Whowho Rd
Apt 7
Whosville, WZ 44494"""
```

This address spans multiple lines, and is still contained in one variable, `address_string`.

When a string like this is not assigned to a variable, it works as a multi-line comment. This can be helpful as your code gets more complex:

```python
""" The following piece of code does the following steps:
takes in some input
does An Important Calculation
returns the modified input and a string that says "Success!" or "Failure..."
"""
... a complicated piece of code here...
```




**설명:** [ Learn ]      
• Ch11. Multi-line Strings 에서는 다중 주석을 학습한다.     
• """ """  or ''' ''' 를 이용하여 여러줄의 문자열을 만들수 있다.    
• 문자열도 만들수 있지만, 한 줄 주석(#) 외에 여러줄의 주석을 만들때도 사용한다.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* Create a variable called `haiku` and store this haiku as a multi-line string: The old pond, A frog jumps in: Plop!

**설명:** [ Instruction ]    
• 변수 haiku 를 만들어라.    
• 변수 haiku 에 다음 여러줄의 문자열을 저장하라.     
• e.g. 문자열 : *The old pond, A frog jumps in: Plop!* 
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* Use the """ """ or ''' '''


**설명:** [ Hint ]    
• """ """ or ''' ''' 를 사용하라. 
{: .notice--info}

<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
haiku = """The old pond,
A frog jumps in:
Plop!"""

print haiku
```

**설명:** [ Solution ]    
• """ """ 사용하여 여러줄의 문자열을 변수에 대입한다.  
{: .notice--info}

**결과** 
```
The old pond,
A frog jumps in:
Plop!
```


<br>
<br>    
<br>    
<p style="page-break-before: always;"></p>     
<br>
