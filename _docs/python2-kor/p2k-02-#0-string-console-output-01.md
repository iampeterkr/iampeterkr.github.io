---
# layout : rchive
title: "Strings"
permalink: /p2k-string-console-output-01/
excerpt: "We learn about Strings."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    

LESSON    

이 장에서는 `print` 키워드를 사용하여, 다양한 문자열 함수를 호출하여 문자열 리터럴을 생성하며, python의 문자열들을 화면에 출력하는것을 소개할 것이다.    

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 

### 1. Strings      


또다른 유용한 데이타 타입은 `string` 타입이다. `string` 은 문자, 숫자, 기호도 포함한다.    

```python
name = "Ryan"
age = "19"
food = "cheese"
```   

상단의 예에서, 우리는 변수 `name`을 만들고, 값으로 `"Ryan"`을 대입한다.    
우리는 또한 변수 `age` 에 `"19"` 를 대입하고, 변수 `food` 에 `"cheese" ` 를 대입한다.    
문자열을 대입할때는 쌍 따옴표가 필요하다.    


**설명:** [ 요약 ]      
• 문자열(string)은 문자와, 숫자와, 기호도 사용할 수 있다.     
• 19는 정수이지만, "" 를 사용했기에, 문자로 인식된다.
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 변수 `brian` 을 만들고, 문자열 `"Hello life!"` 를 대입하라.    

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* 앞 장에서 배운, 변수를 만들고 값을 대입하는것을 기억하는가?    
  만일, 기억나지 않는다면, 앞장을 다시 한번 확인하다.    


**설명:** [ Hint ]     
• 문자열을 대입할때, 문자열의 양끝을 따옴표 ( " " ) or ( ' ' ) 를 사용한다.     
{: .notice--info}

```python
brian = "Hello life!"
brian1 = 'The man screamed "I love Python!" so that everyone could hear.'
brian2 = "The man screamed 'I love Python!' so that everyone could hear."

print (brian)
print (brian1)
print (brian2)
```

**결과**
```
Hello life!
The man screamed "I love Python!" so that everyone could hear.
The man screamed 'I love Python!' so that everyone could hear.
```


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
brian = "Hello life!"
```

**설명:** [ Solution ]    
• 문자열을 대입할때, 문자열 양 끝에 따옴표 ( " " ) or ( ' ' )를 사용한다. 
{: .notice--info}

**결과**
```
 #skip
```
