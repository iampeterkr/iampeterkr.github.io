---
# layout : rchive
title: "String methods"
permalink: /p2k-string-console-output-05/
excerpt: "We learn String methods."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

String 메소드를 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 
### 5. String methods    

훌륭합니다!.    
현재, 우리는 문자열을 어떻게 저장하는지 알고 있습니다.   
지금부터 문자열 메소드를 사용하여 문자열을 어떻게 변경하는지를 배워봅시다.     
문자열 메소드를 사용하면, 여러분은 문자열의 특별한 작업들을 수행할 수 있습니다.   

우리는 4개의 문자열 메소드를 관심을 가질 것입니다.    

*  `len()`    
*  `lower()`    
*  `upper()`    
*  `str()`    


`len()` 메소드는 문자열의 길이를 알려주는 메소드입니다.    


<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 라인 1번에서, 변수 `parrot`를 만들고, 그 변수에 `"Norwegian Blue"`를 대입하라.     
* 라인 1번에서, `len(parrot)` 를 치고, 그 결과를 출력하라. 아래 예를 참조...

```python
 print len(parrot)
```
* 입력 문자열 "Norwegian Blue"의 문자 갯수가 출력될 것이다. 

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* `len()` 메소드를 사용하라.     


**설명:**     
• 함수 len() 에 변수를 삽입하여 해당 변수에 들어 있는 문자의 갯수를 셀 수 있다.
{: .notice--info}

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
parrot = "Norwegian Blue"
print len(parrot)
```

**설명:**     
• 함수 len()의 Parameter로 parrot 변수를 넣었다.    
• print 문으로 len(parrot) 를 출력하였다.    
• 변수 parrot 에 들어있는 문자열 *Norwegian Blue* 의 문자 갯수가 출력된다.    
• 그런데, 예상된 문자 갯수가 13개가 아니라, 14개가 출력 된다.    
• 이유는 공백(space)도 하나의 문자로 계산한다.    
• 중간에 공백을 몇개 넣고 RUN 해보면 바로 알수 있다.
{: .notice--info}


**결과**
```
14
```
