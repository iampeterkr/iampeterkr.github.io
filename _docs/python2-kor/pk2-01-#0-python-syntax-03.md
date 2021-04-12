---
# layout : rchive
title: "String"
permalink: /p2k-python-syntax-03/
excerpt: "We learn about String of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 문자열에 관하여 설명할 것이다.    
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    

<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 3. String    

Python 에서 무언가를 출력할때, 우리는 문자 형태로 출력할 것이다.    
Python 에서 문자는 `string` 이라고 불리는 특정한 데이타 형태로 여겨진다.    
이름이 문자열, 이렇게 붙여진 이유는 일련의 문자, 숫자, 기호의 연결로 되어 있기 때문이며, 이것은 마치 문자열로 서로 연결되 있습니다.   
문자열은 다른 방법들로 정의 될 수도 있다.    



```python
print "This is a good string"
print 'You can use single quotes or double quotes for a string'
```    

상단은, 우리가 두가지 방법으로 문자열을 출력한 것입니다.    
하나는 쌍 따옴표를 이용하여 문자열을 출력하였고, 다른 하나는 홋 따옴표를 이용하여 문자열을 출력하였습니다.    
이 두가지 방법은 모두 사용이 가능합니다.    
다만, 시작이 쌍따옴표면 끝도 쌍따옴표가 되어야 합니다. 

We can combine multiple strings using +, like so:   
우리는 `+` 기호를 사용하여, 아래의 예와 문자열을 연결도 할수 있습니다.     

```python
print "This is " + "a good string"
```   

이 코드는 "This is a good string" 이라고 출력 될 것이다.    


**설명:** [ Learn ]      
• Ch3. String 에서는 문자열을 학습한다.     
• 문자열을 Python 에서는 String 이라고 부른다.     
• String은 작은 따옴표(' ') 또는 큰 따옴표(" ") 사이에 문자를 넣는다.    
• 이후 부터는 우리는 따옴표를 쿼터(quotes)라고 부른다.     
• 문자열은 여러 문자열을 예제와 같이 ( + ) 기호를 사용하여 붙일 수 있다. 
{: .notice--info}

<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 여러분의 이름을 `+` 기호를 사용하여, 다음과 같이 출력되도록 Python 프로그램을 하시오. "Hello [your_name]"   



**설명:** [ Instruction ]     
• 두개의 문자열 사이에 ( + ) 기호를 사용하여 두 문자열을 연결하라.    
• e.g.  *Hello Hongkildong* 을 출력하라. 
{: .notice--info}


<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

```python
print "Hello " + "Nicole"
```

**설명:** [ Hint ]     
• 우리는 두개의 문자열을 ( + ) 기호를 사용하여, 문장을 연결할 수 있다.    
• hello 다음 공백을 주의하라.    
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
print "Hello " + "Peter Lee"
```

**설명:** [ Solution ]     
• 두 개의 스트링을 연결 할때는 ( + ) 기호를 사용한다.
{: .notice--info}


**결과**     
``` 
Hello Peter Lee
```   
