---
# layout : rchive
title: "Explicit String Conversion"
permalink: /p2k-string-console-output-13/
excerpt: "We learn about String Conversion."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

문자열 변환을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 

### 13. Explicit String Conversion    
<br>
간혹, 문자열이 아닌 값들을 문자열과 연결해야할 때가 있습니다.    
이런 경우에, 여러분은 문자열이 아닌 값을 문자열로 변환할수 있습니다.    

```python
print "I have " + str(2) + " coconuts!"
This will print I have 2 coconuts!.
```

`str()` 메소드는 문자열이 아닌 값을 문자열로 변환해 줍니다.    
상단의 예에서, 여러분은 앞에서 연습해본바와 같이, 숫자 `2` 를 문자열 `"2"`로 변환해 주고, 문자열을 서로 연결 해줍니다. 
지금부터, 연습을 해봅시다.    



**설명:**        
• Ch13. Explicit String Conversion 에서는 출력시 문자열 변환을 학습한다.     
• 문자열과 숫자를 concatenation 시킬때는 숫자를 문자열 형태로 바꿔 줘야한다.    
• 바꿔주지 않으면 Python 해석기(interpreter)는 Error를 발생시킨다. 
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 변환을 해주지 않고, 실행을 시키면, Error 가 발생할 것이다.   
* `str()` 메서드를 사용하여, `3.14`를 문자열로 바꿔주고 다시 동작시켜라.     


**설명:**     
• Editor 화면의 소스를 Run 시키면 Error 가 발생한다.    
• 실수 3.14 를 함수 str() 를 사용하여 문자열 형태로 바꾸어라.    
• Run  시켜라.   
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* `str(2)` 을 활용하여 숫자 2를 문자열로 변환시켜라.    
* 여러분은 숫자 3.14를 문자로 변환 할수 있는가?      

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
# Turn 3.14 into a string on line 3!

print "The value of pi is around " + str(3.14)
```

**설명:**    
• 실수 3.14 를 문자열로 바꿔주고, str() 를 사용한다.    
• e.g. str(3.14) 로 변경 해야한다. 
{: .notice--info}



**결과**
```
The value of pi is around 3.14
```    