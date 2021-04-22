---
# layout : rchive
title: "Dot Notation"
permalink: /p2k-string-console-output-09/
excerpt: "We learn Dot Notation."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

Dot Notation 을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 

### 9. Dot Notation    
<br>
여러분이 사용한 `len(string)`과 `str(object)` 이외에도 `"String".upper()`와 같은 dot notation 방법이 있다.    


```python
lion = "roar"
len(lion)
lion.upper()
```    
dot notation 메서드는 오직 문자열에서만 사용한다.   
`len()`과 `str()`은 다른 데이타 형태에서도 사용이 가능하다.    

**설명:**        
• Ch9. Dot Notation 에서는 메서드 접근법을 학습한다.    
• 문자열(대문자, 소문자)을 변환 할때는 ( . ) 을 사용한다.    
• 데이타 type 을 변환 할때는 함수 len() , str() 을 사용한다.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 라인 3에서, `len()` 메서드를 사용하며, 입려값은 변수 `ministry`를 이용후 결과값을 출력하라.    
* 라인 4에서, 변수 `ministry`의 `.upper()` 메서드를 활용하여, 결과 값을 출력하라. 

**설명:**      
• 라인 3에서는 함수 len() 를 사용하여 출력하라.    
• 라인 4에서는 함수 .upper() 를 사용하여 출력하라.
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* skip

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    

```python
ministry = "The Ministry of Silly Walks"

print len(ministry)
print ministry.upper()
```

**설명:**      
• 함수 len(ministry) 는 변수 ministry 의 길이를 반환한다.    
• ministry.upper() 는 변수 ministry 의 문자열을 대문자로 변환한다.    
• *주의)* 변수 ministry 의 저장되어 있는 내용은 변하지 않는다. 
{: .notice--info}



**결과**
```
27
THE MINISTRY OF SILLY WALKS
```    