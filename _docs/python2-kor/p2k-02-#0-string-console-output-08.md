---
# layout : rchive
title: "str()"
permalink: /p2k-string-console-output-08/
excerpt: "We learn String methods, str()."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

String 메소드 str() 을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 


### 8. str()    
<br>
이제, `str()` 메소드를 살펴보자.    
`str()` 메소드는 문자열이 아닌 값을 문자열로 반환해 준다.  다음 예를 살펴보자.    

```python
str(2)
```    

숫자 `2` 를 문자열 `"2"`로 변환된다.    




**설명:**      
• Ch8. str() 에서는 메서드 str()를 학습한다.     
• 함수 str() 는 문자열이 아닌것을 문자열로 변환해 준다.    
• e.g. integer 2 를 string "2" 로 변환해 준다.     
• e.g. float 2.0 를 string "2.0" 로 변환해 준다.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 4라인에서, 변수 `pi`를 생성하고, 값 `3.14`를 대입하라.    
* 5라인에서, 메소드 `str(pi)` 호출하고, 그 결과를 출력하라.     


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* `str()` 메소드 문법은 `len()` 메소드 사용법과 같다.     

```python
str(pi)
```

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
"""Declare and assign your variable on line 4,
then call your method on line 5!"""

pi = 3.14
print str(pi)
```

**설명:**     
• float 변수 pi 에 실수 3.14 를 대입한다.    
• 변수 pi 를 출력 할때는 str() 을 사용하여 문자열로 변환하여 출력 해야한다.  
{: .notice--info}


**결과**
```
3.14
```    