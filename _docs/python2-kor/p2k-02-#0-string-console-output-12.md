---
# layout : rchive
title: "String Concatenation"
permalink: /p2k-string-console-output-12/
excerpt: "We learn about String Concatenation."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

문자열 연결을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 
<br>

### 12. String Concatenation    
<br>
여러분은 문자열과, 수의 연산자에 대하여 배웠다.    
지금부터 문자를 연결해 보자.   

```python
print "Life " + "of " + "Brian"
# This will print out the phrase Life of Brian.
```

`+` 연산자는 문자열의 앞뒤를 서로 연결해 준다.   
주의할 점은, 3개의 문자열을 연결할때, "Life ", "of " 다음에 공백을 꼭 따옴표 안에 넣어 주어야 한다.   

문자열을 서로 연결하는것을 `concatenation` 이라고 부른다.    
지금부터 여러 문자열을 연결해 보도록 하자.   


**설명:**       
• Ch12. String Concatenation 에서는 문자열 연결을 학습한다.     
• 문자열은 ( + ) 연산자를 사용하여 연결할수 있다.   
• 문자열 사이의 공백을 주의하자. 
• 문자열을 ( + ) 연산자를 사용하여 연결하는것을 concatenations 이라고 한다.  
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 라인 3에서, `"Spam "`, `"and "`, `"eggs"`를 연결하여 출력하라.    
* 주의할점은, `"Spam "`과 `"and "` 다음에 공백이 있어야 한다. 
* 상단 설명에서 공부한 내용을 자세히 보아라.    


**설명:**     
• 라인 3 에서, "Spam ", "and ", "eggs"를 연결하라.        
• 주의할 점은 "Spam" 과 "and" 문자뒤에 공백이 있어야 한다.    
• e.g. "Spam ",   "and "
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 공백과 대/소문자를 사용하는것을 주의하라. 

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
# Print the concatenation of "Spam and eggs" on line 3!

print "Spam " + "and " + "eggs"
```

**설명:**     
• Concatenation( + ) 는 문자 그대로 연결시켜 준다.    
• 임의로 공백을 주지 않으면 "Spamandeggs" 로 출력된다.    
• 문자열 (" ") 사이에 공백을 적절히 넣어줘야 한다. 
{: .notice--info}


**결과**
```
Spam and eggs
```    