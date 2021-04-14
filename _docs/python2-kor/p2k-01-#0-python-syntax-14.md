---
# layout : rchive
title: "Review"
permalink: /p2k-python-syntax-14/
excerpt: "We review about Python Syntax."
redirect_from:
  - /theme-setup/
#toc: true
#toc_sticky: true
#toc_sticky:
#toc_label: 목차
---

  
   
<hr style="border: solid 1px #dddddd ;">    
LESSON    

이 장에서는 Python Syntax 전체에 대하여 정리한다.   

<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">PYTHON SYNTAX</font> 
### 14. Review    

훌륭합니다. 지금까지 공부한 것을 살펴 보겠습니다.   

* Print 사용법        
* 변수 생성, 수정, 변수 사용방법    
* 사칙연산     
* 주석처리 방법     
* 데이터 종류(strings, ints, floats, and booleans)    
* 데이터 형(type) 변환 


<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* Let's apply all of the concepts you have learned one more time!    
* 지금까지 배운 모든것을 한번에 적용해 보자.    

* 변수 `skill_completed` 를 생성하고, 문자열 "Python Syntax" 를 대입하라.    

* 변수 `exercises_completed` 를 생성하고, 정수 `13`을 대입하라.    
  변수 `points_per_exercise`를 생성하고, 정수 `5`를 대입하라.    

* 변수 `point_total` 을 생성하고, 정수 `100`을 대입하라.   

* 생성된 변수 `point_total` 에 변수 `exercises_completed` 와 `points_per_exercise` 곱한 값으로 변경하라.    

* 변수 `points_per_exercise` 위헤 다음과 같이 주석처리 하라.    
```
The amount of points for each exercise may change, because points don't exist yet    
```    
     
* 화면에 다음과 같이 출력하라. (X 자리에 변수 `point_total` 값이 위치)
```    
I got X points!
```    

**설명:** [ 요약 ]     
• 변수 skill_completed 에 문자열 *Python Syntax* 를 대입하라.     
• 변수 exercises_completed 에 13 을 대입하라.        
• 변수 points_per_exercise 에 5 를 대입하라.      
• 변수 point_total 에  100 을 대입하라.    
• 변수 point_total 에 기존 결과값 변수 point_total 값에 변수 exercises_completed * points_per_exercise 곱한 결과 값을 더하라.     
• *The amount* 부터 *yet* 까지의 문자열을 주석 처리하라.     
• *I got X points!* 를 콘솔창에 출력하라.    
• 변수 X 위치에, 변수 point_total 값이다.
{: .notice--info}



<p style="page-break-before: always;"></p>     
<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    

* 연산자 `+=` 를 활용하라.   
```python
total += number_to_add
```

* `+=`는 아래 예와 같이 단축 방법이다. 

```python
[new value of] total = [old value of] total + number_to_add
```
* 정수값을 `str()`을 사용하여 문자열화 하고, 나머지 문자열을 붙여라.    

```python
print "This is " + str(1) + " long string!"
>>> "This is 1 long string!"
```    

**설명:** [ Hint ]    
• += 기법을 사용하라. 
• 함수 str() 사용하여, 숫자를 문자열로 바꾸어 출력한다. 
{: .notice--info}


<p style="page-break-before: always;"></p>     
<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
skill_completed = "Python Syntax"
exercises_completed = 13
#The amount of points for each exercise may change, because points don't exist yet
points_per_exercise = 5
point_total = 100
point_total += exercises_completed * points_per_exercise

print "I got "+str(point_total)+" points!"
```

**설명:** [ Solution ]    
• 문자열, 정수형, 주석, += 연산, 사칙연산, 문자형 변환을 참조 하세요. 
{: .notice--info}

**결과**
```
I got 165 points!
```    
