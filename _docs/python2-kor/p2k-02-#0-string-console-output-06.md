---
# layout : rchive
title: "lower()"
permalink: /p2k-string-console-output-06/
excerpt: "We learn String methods, lower()."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

String 메소드 lower() 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 

### 6. lower()     

여러분은 `lower()` 메소드를 사용하여, 문자열에 있는 대문자를 모두 소문자로 만들수 있다.    
사용법은 아래와 같다.    


```python
"Ryan".lower()
```    
결과 값은 "ryan" 이 반환될 것이다.    



**설명:**      
• Ch6. lower() 에서는 메서드 lower()를 학습한다.    
• 함수 lower() 는 대문자를 모두 소문자로 변경하여 반환한다.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 3 라인에서, 변수 `parrot`에 담긴 문자열을 `lower()` 메소를 사용하여 그 결과값을 출력하라.    



<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 여러분의 코드는 다음 예처럼 보여야 한다.    

```python
print parrot.lower()
```    


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
parrot = "Norwegian Blue"

print parrot.lower()
```     

**설명:**     
• 문자열에 ( . ) 을 붙이고 lower() 를 사용할 수 있다.    
• 변수에도 동일하게 ( . ) 을 붙이고 함수 lower() 를 사용할 수 있다.
• [참고] Command 창에서, dir(parrot)를 입력하면, 사용할수 있는 메소드 리스트가 출력된다. 
{: .notice--info}


**결과**
```
norwegian blue
```    