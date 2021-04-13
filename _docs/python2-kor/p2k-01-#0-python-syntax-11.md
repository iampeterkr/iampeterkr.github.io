---
# layout : rchive
title: "Multi-line Strings"
permalink: /p2k-python-syntax-11/
excerpt: "We learn about Multi-line Strings of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 Multi-line 문자열에 대하여 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 11. Multi-line Strings     


우리는 문자열을 정의할때, 쌍따옴표, 홋따옴표로 정의하는 것을 해보았다.    
만일, 우리가 문자열을 여러줄에 걸쳐 만들기를 원한다면, 우리는 따옴표 3개를 이용하여 만들 수 있다.    

```python
address_string = """136 Whowho Rd
Apt 7
Whosville, WZ 44494"""
```

이 주소는 여러줄로 되어 있고, 이것은 변수 `address_string`에 저장되어 있다.    

다음과 같이 변수에 저장하는 것이 아니라, 주석처리를 여러라인에 걸쳐 할수도 있다.    
이 방식은 당신의 복잡한 코드를 좀더 편리하게 도와줄 것이다.   

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

* 변수 `haiku`를 만들고, 여러줄의 문자열을 저장하라.   
  - 저장할 문자열 :The old pond, A frog jumps in: Plop!     
    

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
*  `""" """` or ` ''' ''' ` 를 사용하라.  

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
