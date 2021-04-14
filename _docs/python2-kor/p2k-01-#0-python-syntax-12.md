---
# layout : rchive
title: "Booleans"
permalink: /p2k-python-syntax-12/
excerpt: "We learn about Booleans of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 논리 연산자(Booleans) 에 대하여 배울 것이다.  

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 12. Booleans    

가끔씩, 우리는 값이 참 or 거짓인 변수가 필요하다.    
이 논리 연산자는 참 or 거짓 중 하나의 값만 가질수 있습니다.    
이런 테이타 형태를 논리 연산자(boolean)라고 한다.    
Python 에서는, 참과, 거짓 키워드로 `True` , `False` 를 사용합니다.     

```python
a = True
b = False
```

논리연산자는 정수의 특수한 예이며,        
`True` 값은 정수값 1과 일치하며, 1로 사용할수 있다.    
`False` 값은 정수값 0과 일치하며, 0으로 사용할수 있다.     


**설명:** [ 요약 ]       
• Ch12. Booleans 에서는 boolean 연산자를 학습한다.    
• Python에서 참, 거짓을 표현해야 할 때가 있다.     
• 참 은 문자열로 *True* 로 표현한다.    
• 거짓 은 문자열로 *False* 로 표현한다.     
• 참  의 값은 숫자 *1* 이다.    
• 거짓 의 값은 숫자 *0* 이다. 
{: .notice--info}

![codecademy]({{ site.baseurl }}/assets/images/codecademy/03-boolean-00.svg){: width="70%" height="70%"}    

<br>

<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    
* script.py 프로그램 안에서 주석 처리로 무언가를 설명하고 있다.     

* 주석을 읽고, 변수 `age_is_12`를 생성하고, 주석을 읽은 내용에서 사람의 나이가 12살이면 변수에 `True`를 대입하고, 아니면 `False`를 대입하라.   

* 변수 `name_is_maria`를 생성하고, 주석에서 설명한 사람의 이름이 Maria 이면 `True`를 대입하고, 아니면 `False`를 대입하라.    

**설명:** [ 요약 ]    
• 변수 age_is_12 를 만들어라.    
• 주석에서 설명하는 사람의 나이가 12 살이면 True 를 대입하라.    
• 12 살이 아니면, False 를 입력하라.     
• 변수 name_is_maria 를 만들어라.    
• 주석에서 설명하는 사람의 이름이 Maria 이면 True 를 대입하라.    
• Maria 가 아니면, False 를 입력하라. 
{: .notice--info}



<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 주석문을 읽고 적당한 `True` or `False` 를 입력하라. 

```python
some_variable = True
```

<p style="page-break-before: always;"></p>     
<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
# Hi! I'm Maria and I live in script.py.
# I'm an expert Python coder.
# I'm 21 years old and I plan to program cool stuff forever.

age_is_12 = False
name_is_maria = True
```

**설명:** [ Solution ]    
• 주석에서 Python coder 나이는 21 살, 이름은 Maria 이다.  
{: .notice--info}

