# 程式閱讀題
```
考卷:
1.print("3*2*(17-9)")會印出甚麼結果:
(A)ant   (B)abcdef  (C)出現錯誤,無法印出  (D)3*2*(17-9)

2.print(3*2*(18-5))會印出甚麼結果:
(A)0   (B)78  (C)出現錯誤,無法印出  (D)3*2*(17-2)

3.print("bbb"+"ttt")會印出甚麼結果:
(A)tttbbb   (B)bbbttt  (C)bbb"+"ttt  (D)出現錯誤,無法印出

4.print("bbb""+""ttt")會印出甚麼結果:
(A)bbb+ttt   (B)bbbttt  (C)出現錯誤,無法印出  (D)bbb""+""ttt

5.底下程式執行後結果為何?
word = "art"
print(word.replace("r", "nnnnnnnn"))
(A)annnnnnnnt   (B)出現錯誤,無法印出  (C)arrrrrrrrt  (D)ant

6.底下程式執行後結果為何?
word = "bosslslzzzsisss"
print(word.replace("s", "d",5))
(A)boddldlzzzdidss   (B)bosslslzzzsisss  (C)boddldlzzzdiddd  (D)出現錯誤,無法印出

7根據底下程式,下列敘述何者為非?[複選題]

names = ['y', 'z']
index = 0

while index < len(names):
    name = names[index]
    print(name)
    index = index + 1
    
(A)len(names)=2  ✓
(B)names[1]是 y 
(C)程式執行完後,index最後為2 ✓
(D)如果把條件改成 index > len(names),中index最後為2

```
# 程式設計題
```
for 迴圈(loop)的技巧
1.使用for 迴圈(loop)計算1+2+3+.....100
答案:4950
2.使用for 迴圈(loop)計算1+3+5+7.....+99
答案:2402
3.使用for 迴圈(loop)計算1*3*5*7.....*99
答案:27529213532835651545259729751524430639300973035816196098326553772152587890625

while 迴圈(loop)的技巧
4.使用while 迴圈(loop)計算1+2+3+.....100
5.使用while 迴圈(loop)計算1+3+5+7.....+99
6.使用while 迴圈(loop計算1*3*5*7.....*99
```
# 程式設計題解答(有各種寫法,找寫最快的分數最高)

### 使用for 迴圈(loop)計算1+2+3+.....100
```
sum=0

for x in range(1,101):
  sum +=x
  
print(sum)
答案:4950
```
### 使用for 迴圈(loop)計算1+3+5+7.....+99
```
sum=0

for x in range(1,99,2):
  sum +=x
  
print(sum)
答案:2402
```
### 使用for 迴圈(loop)計算
```
1*3*5*7.....*99
```
```
total=1

for x in range(1,101,2):
  total *=x
  
print(total)
答案:27529213532835651545259729751524430639300973035816196098326553772152587890625
```

### 使用while 迴圈(loop)計算1+2+3+.....100
```
sum = 0
x=1

while x < 101:
  sum +=x
  x = x+1
  # x += 1
  
print(sum)
```
### 使用while 迴圈(loop)計算1+3+5+7.....+99
```
sum = 0
x=1

while x < 101:
  sum +=x
  x = x+2
  # x += 1
  
print(sum)
```

### 使用while 迴圈(loop)計算
```
1*3*5*7.....*99
```
```
total = 1
x=1

while x < 101:
  total *=x
  x = x+2     # x += 2
  
print(total)
```
