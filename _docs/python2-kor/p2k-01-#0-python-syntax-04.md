---
# layout : rchive
title: "Handling Errors"
permalink: /p2k-python-syntax-04/
excerpt: "We learn about Errors of Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 Error 를 관리하는 방법을 배울 것이다.    

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    

<font size="3"  face="돋움">PYTHON SYNTAX</font> 
## 4. Handling Errors    

여러분은 Python 프로그래밍을 하다보면, errors 와 예외처리를 만나게 될 것이다.     
이것들이 발생하는 이유는 Python 입장에선 당신이 무엇을 시키는지를 이해할수 없을때 나타나는 불만들이다.    
모두들 프로그래밍 과정에서 이러한 문제들에 부딪히게 되므로, error 와 예외처리들을 읽고 이해할수 있어야 합니다.    
여기에 문자열을 출력할때 여러분이 겪을 몇가지 공통된 error 들이 있습니다. 


```python
print "Mismatched quotes will cause a SyntaxError'
print Without quotes will cause a NameError
```

`print` 문에서 따옴표가 일치하지 않으면, Python은 당신의 코드에 문법적 error 가 발생했다고 알려줄 것이다.    
왜냐하면, 문장의 끝인 마무리 전에 쌍 따옴표가 올것이라고 예상했는데, 홋 따옴표가 왔기때문이다. 프로그램은 아래와 같이 메시지를 화면에 출력하고, 즉각 동작을 멈출 것이다.    

```bash
SyntaxError: EOL while scanning a string literal
This means that a string wasn't closed, or wasn't closed 
with the same quote-character that started it.
```

다른예로, 여러분이 `print` 문을 작성할때, 문장의 양 끝에 따옴표가 없이 만들수도 있다.      
Python은 `print` 문과 같이 문자열에 따옴표가 없으면 명령어로 인식을 하고 처리를 한다.     
먼저, 명령어 목록중 해당 명령어가 있는지 찾아보고, 없으면 python은 `NameError` 를 발생시킨다.    
이것은 python 이 명령어로 인식하고, 명렁어 목록에서 찾았지만, 정의된 어느 곳에서도 찾을수 없기에 더이상 무슨 뜻인지 모르겠다고 대답하는 것이다.    


**설명:** [ 요약 ]        
• Ch4. Handling Errors 에서는 Error에 대하여 학습한다.     
• 쿼트(quotes)가 시작과 끝이 같지 않으면, Python은 *EOL Error*를 발생시킨다.   
• e.g. SyntaxError: EOL while scanning string literal    
• *EOL : End Of Line*  
• *EOL Error*는 Python이 문자열을 만드는 과정에서 문법적 Error가 발생했다는 뜻이다.    
• 시작이 (') 이면 끝도 (') 이어야 한다.    
• 시작이 (") 이면 끝도 (") 이어야 한다.     
• 문자열의 양 끝에 쿼트(quotes)가 없으면 Python은 해당 문자열을 print 와 같은 명령문(or 변수)으로 인식한다.    
• 이런 경우 Python 은 해당 문자열을 명령어(or 변수) 리스트에서 찾는다.    
• 만약, 해당 리스트에서 찾을수 없으면 *NameError* 를 발생시킨다.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 우리는 error 가 발생되는 2개의 `print` 을 작성했다.       
* 하나는 따옴표가 일치 하지 않고, 다른 하나는 따옴표가 없다.   
* 2개의 잘못된 `print` 문을 바르게 수정하라.     

**설명:** [ Instruction ]    
• 쿼트(quotes)를 잘못 사용하면 Error 가 발생한다.    
• 잘못된 Python 프로그램을 수정하라.  
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* `print` 문 뒤에는 반드시 동일한 따옴표가 오고, 그 따옴표 속에는 문자열이 있어야 한다.   

```python
print 'This is a good print statement'
```   

* 쌍 따옴표를 사용해도 된다.    

```python
print "This is also a good print statement"
```

<p style="page-break-before: always;"></p>     
<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
print "How do you make a hot dog stand?"
print "You take away its chair!"
```


**설명:** [ Solution ]     
• 문자열을 표현할때는 처음과 끝의 따옴표 모양이 같아야 한다.
{: .notice--info}


**결과**     
``` 
How do you make a hot dog stand?
You take away its chair!
```   
