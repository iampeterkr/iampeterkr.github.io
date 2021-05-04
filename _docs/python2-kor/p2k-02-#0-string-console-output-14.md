---
# layout : rchive
title: "String Formatting with %, Part 1"
permalink: /p2k-string-console-output-14/
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

문자열 치환을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 

### 14. String Formatting with %, Part 1  
<br>   
여러분이 문자열 변수를 출력할때, 문자열을 연결하는것보다 효율적인 방법이 있다.      

```python
name = "Mike"
print "Hello %s" % (name)
```

문자열 뒤에 `%` 연산자는 문자열 변수와 같이 사용되기도 한다.   
`%`연산자는 문자열 속에서 `%s` 뒤에 오는 문자열 변수로 대체 될것이다.  

여러분이 정수 변수를 출력하기를 원할때는 `%02d` 같이 0을 추가할 수 있다.     
숫자 `0`의 의미는 0으로 채우라는 의미이며, 숫자 `2`의 의미는 2자릿수라는 의미이며, `d`는 양수 or 음수의 숫자라는 의미이다.    

```python
day = 6
print "03 - %s - 2019" %  (day)
# 03 - 6 - 2019
print "03 - %02d - 2019" % (day)
# 03 - 06 - 2019
```

**설명:**        
• Ch14. String Formatting with %, Part 1 에서는 문자열 치환을 학습한다.    
• 문자열을 출력 할때, % 옵션을 사용하여 해당 변수를 치환한다.     
• %s 는 문자 변수를 치환한다.    
• %d 는 정수 변수를 치환한다.    
• %d 는 옵션을 추가하면, 숫자 앞 부분을 0 으로 채운다.
{: .notice--info}    

**설명:** [ Python3 ]     
• python3 에서는 문자열 메서드 format() 을 사용한다.    
• %s 대신에, {0}, {1}, {2}, {3} 등 인자의 위치를 알려준다.    
• 사용은 다음과 같이 한다.    
• 'I am {0}, and i love {1}'.format('Peter', 'Python')    
• 출력은 다음과 같이 된다.    
• 'I am Peter, and i love Python
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 에디터속의 코드를 살펴 보세요.     
* 어떤 일이 발생할까요? Run 버턴을 클릭하여 예상한대로 출력 되는지 살펴보세요. 




<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* `%` 와  `%()` 를 어떻게 사용하는지를 생각하라.


<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    

```python
string_1 = "Camelot"
string_2 = "place"

print "Let's not go to %s. 'Tis a silly %s." % (string_1, string_2)
```    

**설명:**     
• 1 번째 %s 에는 변수 string_1 이 할당되어 출력된다.    
• 2 번째 %s 에는 변수 string_2 가 할당되어 출력된다.
{: .notice--info}


**결과**
```
Let's not go to Camelot. 'Tis a silly place.
```    