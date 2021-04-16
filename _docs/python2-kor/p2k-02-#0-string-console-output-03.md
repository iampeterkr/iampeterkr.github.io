---
# layout : rchive
title: "Escaping characters"
permalink: /p2k-string-console-output-03/
excerpt: "We learn Escaping characters."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이스케이프 문자열을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 
### 3. Escaping characters     

아래와 같이, 몇가지 문자들은 문제들을 일으킨다.    

```python
'There's a snake in my boot!'
```

이 코드는 문제점이 있다.    
왜냐하면, Python은 `'There'` 의 문자열이 끝났다고 생각한다.    
우리는 역 슬래쉬를 사용하여, 아래와 같이 이 문제를 해결할 수 있다.    

```python
'There\'s a snake in my boot!'
```


**설명:** [ 요약 ]       
• Ch3. Escaping characters 에서는 `\` 사용법을 학습한다.    
• 우리는 문자열을 만들때, 따옴표( ' ' )를 사용해야 한다고 앞에서 배웠다.    
• 가령 'There's' 라는 문자열을 만들때 Python은 따옴표 ( ' )를 쿼터로 인식한다.     
• 이런 경우는 ( ' ) 가 쿼터가 아님을 표시해주는 `\` 를 앞에 둔다.    
• Python 은 `\` 이면 다음 문자를 단순 문자로 인식한다.   
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    
* Edit 창에 있는 문자열을 수정하라!    

```python
# The string below is broken. Fix it using the escape backslash!

'This isn't flying, this is falling with style!'
```

**설명:**      
• 문자열 *ist't* 를 수정하여 정상적인 문자열로 만들어라.  
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 여러분은 이스케이프 문자(`\`)를 `'` 이전에 추가하면 된다.    
* 이문제를 해결할 다른 방법이 있다. 생각해본적이 있는가?
* 여러분은 이 문제를 다른 방법으로 해결해선 안됩니다.        

**설명:**     
• 반드시 `\` 를 사용하여 해결 해야 한다.  
{: .notice--info}


<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
# The string below is broken. Fix it using the escape backslash!

'This isn\'t flying, this is falling with style!'
```

**설명:**     
• 문자열 *isn't'* 를 *isn\'t* 로 수정 한다.     
• 또다른 방법은 가장 바깥쪽 문자열 쿼터 ( ' ' ) 를 ( " " ) 로 바꾸어 준다.   
{: .notice--info}

```python
# The string below is broken. Fix it using the escape backslash!

a = 'This isn\'t flying, this is falling with style!'

b = "This isn\'t flying, this is falling with style!"

print (a)
print (b)

```

**결과**
```
This isn't flying, this is falling with style!
This isn't flying, this is falling with style!
```    

