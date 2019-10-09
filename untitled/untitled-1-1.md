---
description: 不可勝者，守也；可勝者，攻也。【軍形篇】
---

# 2.3 If - Else

### 如果這樣就那樣，否則如果那樣就這樣，否則就那樣

```python
score = 59
if score >= 60 :
    print("Good!")
elif score >= 40 :
    print("You need more practice.")
else :
    print("QQ...")
```

還可以這樣

```python
score = 59
if score >= 60 :
    print("Good!")
else :
    if score >= 40 :
        print("You need more practice.")
    else :
        print("QQ...")
```

對就是這麼簡單，可是非常重要，來練習看看吧

## 小練習

> 實作一個判斷一元二次方程式解的情形的程式，輸入 a, b, c 三個數字，若此方程式 ax^2 + bx + c 有解，則輸出其解，若是無解則輸出 "error"

> 實作一個輸入年分，判斷該年分是否為閏年的程式 \(閏年：年分被4整除，不被100整除或是被400整除，即稱為閏年\)



