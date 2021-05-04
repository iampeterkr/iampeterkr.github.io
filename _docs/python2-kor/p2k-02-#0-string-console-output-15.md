---
# layout : rchive
title: "String Formatting with %, Part 2"
permalink: /p2k-string-console-output-15/
excerpt: "We learn about String Formatting with %."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

문자열 포맷을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 
<p>
### 15. String Formatting with %, Part 2    
<p>

`%s` 자리에는 `%`뒤의 괄호안 변수로 대체된다.     

```python
name = "Mike"
print "Hello %s" % (name)
```

괄호안의 변수의 갯수와 문자열 안의 `%s`의 수는 같아야 한다.    


```python
print "The %s who %s %s!" % ("Knights", "say", "Ni")
# This will print "The Knights who say Ni!"
```

<p style="page-break-before: always;"></p>
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* Now it's your turn! We have ___ in the code to show you what you need to change!    
* 코드상에서 여러분이 바꾸기를 원하는 부분을 보여줄 것입니다.    
  * 문자열속 ___ 자리에는 `%s` 를 넣으세요.        
  * 치환할 3개의 변수 앞에는 `%`를 넣으세요.    
  * Run 을 클릭하세요.     
  * 콘솔창에서 질문창이 뜰 것입니다.    
  * 질문에 대한 당신의 답을 입력하고 엔터를 치세요.    



<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 아래 문법을 잘 기억하세요.   

```python
print "%s" % (string_variable)
```
* 라인 5에서의 `\` 문자는 계속 연결된다는 의미이다.
* 파이썬은 라인 5와 6이 연결된다는것을 Python interpreter(해석기)에게 알려주는 것이다.   

<p style="page-break-before: always;"></p>
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
name = raw_input("What is your name? ")
quest = raw_input("What is your quest? ")
color = raw_input("What is your favorite color? ")

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)
```    

**설명:**     
• %s를 변수 치환 % 를 사용하여 치환한다.    
• Console 에서 질문에 답을 입력하고, Enter 키 를 누른다.    
• %s, %s, %s 에 %( name, quest, color) 값이 출력 된다.
{: .notice--info}


**결과**
```
What is your name? iampeter
What is your quest? earth
What is your favorite color? yellow
Ah, so your name is iampeter, your quest is earth, and your favorite color is yellow.
```     