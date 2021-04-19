---
# layout : rchive
title: "Access by Index"
permalink: /p2k-string-console-output-04/
excerpt: "We learn Access by Index."
redirect_from:
  - /theme-setup/
# toc: true
# toc_sticky: true # true : 고정
# toc_sticky: 
# toc_label: 목차
---
    
    
<hr style="border: solid 1px #dddddd ;">    
LESSON    

Index 에 접근하는 법을 연습한다.    
     
<hr style="border: solid 1px #dddddd ;">    
<br>
![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-learn-01.png)    
<font size="3"  face="돋움">STRING & CONSOLE OUTPUT</font> 
### 4. Access by Index    

Great work!

문자열에 있는 문자는 각각 번호가 매겨져 있다. 이 매겨진 번호가 Index 이다.   
Editor 에 있는 그림을 확인해 보자.    

```python
c = "cats"[0]
n = "Ryan"[3]
```
* 위, 예에서, 우리는 변수 `c` 를 만들고, 변수에 문자 `"c"`를 대입한다. 문자 `"c"`는 문자열 `"cats"`의 index 값은 0 이다.     

* 다음으로, 우리는 변수 `n`을 만들고, 변수에 문자 `"n"`을 대입한다. 문자 `"n"`은 문자열 `"Ryan"`의 index 값은 3 이다.    

주의 할점은, 첫번째 `"cats"` 에서, `"cats"`의 index 0의 문자열은 `"c"` 가 반환된다. 이유는 Python에서는 index 값을 0 부터 붙여준다.    
그러므로, 문자열 `"cats"` 에서 첫번째 문자는 `"c"`이며, index 값은 0이다. 그리고, 마지막 문자 `"s"`는 index 값이 3이다.     

```
+---+---+---+---+
| c | a | t | s |
+---+---+---+---+
  0   1   2   3  

+---+---+---+---+
| R | y | a | n |
+---+---+---+---+
  0   1   2   3  
```


**설명:**        
• Ch4. Access by Index 에서는 문자열 주소 접근법을 학습한다.    
• 문자열은 위와 같이 메모리에 저장된다.    
• 그 메모리에는 0 번 부터 주소(index)가 매겨진다.  
{: .notice--info}

```python
"""
The string "PYTHON" has six characters,
numbered 0 to 5, as shown below:

+---+---+---+---+---+---+
| P | Y | T | H | O | N |
+---+---+---+---+---+---+
  0   1   2   3   4   5

So if you wanted "Y", you could just type
"PYTHON"[1] (always start counting from 0!)
"""
```

<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-instruction-01.png)    

* 13 라인에서, 변수 `fifth_letter`에 문자열 `"MONTY"`의 5번째 문자를 대입하라.   
* 5번째 글자는 index 값 5가 아니다라는 것을 기억하라.    
* Index의 시작은 0 부터 시작한다.    


**설명:**     
• 변수 fifth_letter 에 *MONTY* 중 5 번째 글자만 대입하라.
{: .notice--info}


<br>
<hr/>


![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-hint-01.png)    
* 문자 `"Y"`가 당신이 찾고자 하는 글자이다.     


**설명:**     
• 문자열 *MONTY* 에서 *Y* 만 출력 할려면 변수에 *Y* 만 대입해야 한다.
{: .notice--info}

<p style="page-break-before: always;"></p>     
<br>
<hr/>

![codecademy]({{ site.baseurl }}/assets/images/codecademy/00-solution-03.png)    


```python
"""
The string "PYTHON" has six characters,
numbered 0 to 5, as shown below:

+---+---+---+---+---+---+
| P | Y | T | H | O | N |
+---+---+---+---+---+---+
  0   1   2   3   4   5

So if you wanted "Y", you could just type
"PYTHON"[1] (always start counting from 0!)
"""
fifth_letter = "MONTY"[4]

print fifth_letter
```    

**설명:**     
• 문자열 *MONTY* 에서 *Y* 만 출력 할려면 *Y*가 다섯번째에 있는 글자 이다.    
• 하지만, 실제 인덱스 주소에는 4 번에 저장되어 있다.    
• "MONTY"[4] 즉, 4 번째 주소에 있는 글자만 변수에 대입해야 한다. 
{: .notice--info}

**결과**
```
Y
```
