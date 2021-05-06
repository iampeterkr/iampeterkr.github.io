---
# layout : rchive
title: "And Now, For Something Completely Familiar"
permalink: /p2k-string-console-output-16/
excerpt: "We review about String & Console Output"
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

지금까지 배운 문자열 전체 복습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 
<br>

### 16. And Now, For Something Completely Familiar
<br>

여러분은 문자열을 활용하는 여러가지 방법들을 배웠습니다.    
문자열을 만드는 3가지 방법은 아래와 같습니다.    

```python
'Alpha'
"Bravo"
str(3)
```   

문자열 메소드들    

```python
len("Charlie")
"Delta".upper()
"Echo".lower()
```    

문자열 출력    

```python
print "Foxtrot"
```


개선된 출력방식들...    

```python
g = "Golf"
h = "Hotel"
print "%s, %s" % (g, h)
```

<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 한방에 진행해 봅시다.    
  * 라인 3에서, 변수 `my_string`를 만들고, 어떤 문자열을 대입하세요.    
  * 라인 4에서, `len()` 메서드를 사용하여, 변수 `my_string`에 저장된 값의 길이를 출력하세요.     
  * 라인 5에서, `.upper()`메서드를 사용하여, 변수 `my_string`에 저장된 문자열을 모두 대문자로 변환후 출력하세요.   



<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 여러분은 아래와 같이 `print` 출력시, 한줄에 표현할수 있다.     

``` python
print my_variable.upper()
```
<p style="page-break-before: always;"></p>
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    
```python
# Write your code below, starting on line 3!

my_string = "hey"
print len(my_string)
print my_string.upper()
```

**설명:**     
• 변수 my_string 의 길이를 함수 len()를 사용하여 출력한다.    
• 변수 my_string 의 문자열을 함수 .upper() 를 사용하여 대문자로 출력한다. 
{: .notice--info}


**결과**
```
3
HEY
```