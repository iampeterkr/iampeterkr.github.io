---
# layout : archive
title: "Getting the Current Date and Time"
permalink: /p2k-date-and-time-02/
excerpt: "We learn about Getting the Current Date and Time."
# last_modified_at: 2019-01-30T09:00:00-04:00
redirect_from:
  - /theme-setup/
toc: true
---
    
    
<hr style="border: solid 1px #dddddd ;">    

LESSON    

이 장에서는 현재 날짜와 시간을 가져오는 방법을 학습한다.     

     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">DATA AND TIME</font> 

### 2. Getting the Current Date and Time    
<p>    

여러분은 `datetime.now()` 함수를 사용하여, 현재 날짜와 시간을 추출할 수가 있습니다.    


```python
from datetime import datetime
print datetime.now()
```

첫번째 라인에서 `datetime` 라이브러리를 불러오고 사용할 것입니다.    
두번째 라인에서 현재 날짜와 시간을 출력할 것입니다.    


**설명:**
• datetime.now() 는 현재 날짜와 시간을 알려주는 함수이다.    
• datetime 을 사용하기 위해서는 클래스 datetime 기본제공 함수를 사용한다.    
{: .notice--info}



<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 변수 `now`를 생성하고, 이 변수에 `datetime.now()`의 결과값을 대입하라.     
* 그리고, `now`를 출력하라. 


<p style="page-break-before: always;"></p>
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 변수 `now`에 값을 대입하는 방법은 `=` 연산자를 활용하는것을 기억하세요.   
* 예를 들면, 값 4를 대입하는것은 아래와 같이 합니다.    

```python
now = 4
```

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
from datetime import datetime

now = datetime.now()
print now
```

**설명:**     
• 클래스 datetime 를 import 한다.     
• 변수 now 를 만들고, datetime.now() 를 저장한다.      
• datetime.now() 는 현재 일자와 날짜를 반환한다.    
• 변수 now 를 출력한다. 
{: .notice--info}


**결과**
```
2018-11-27 10:27:29.102097
```    