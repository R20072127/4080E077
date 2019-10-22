# 數值計算
```
底下程式執行後, z之值為何?
x = 3
y = 5
z = (x + y) / 2
```

```
底下程式執行後, 其值為何?
3 / 2
3 // 2
-1 // 2

51 + 122 - 33*42-(44*3)/5
3000000000*3.0
3000000000*3

int(200.2)
int(2e2)
float(200)

答案:200.0

```
### 複數運算
```
3 + 2j - (4 + 4j)
1j*1j
(1 + 2j) * (3 + 4j)

z = 3+5j
z.real
z.imag


import cmath
cmath.sqrt(-1)
答案 : 1j
```
### 字串
```
(D)1.print("3*2*(17-2)")會印出甚麼結果:
(A)0   (B)90  (C)出現錯誤,無法印出  (D)3*2*(17-2)

(B)2.print(3*2*(17-2))會印出甚麼結果:
(A)0   (B)90  (C)出現錯誤,無法印出  (D)3*2*(17-2)

(B)3.print("abc""+""def")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)abc+def  (C)abc""+""def  (D)abcdef

(D)4.print("abc"+"def")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)abc+def  (C)abc""+""def  (D)abcdef

(C)5.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z",3))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz

(D)6.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z"))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz

7.底下各行輸出為何?
sentence = 'To Be or NOT to Be: that is the question: '
print(sentence.upper())
print(sentence.lower())
print(sentence.capitalize())
print(sentence.count('o'))
答案:
TO BE OR NOT TO BE: THAT IS THE QUESTION: 
to be or not to be: that is the question: 
To be or not to be: that is the question: 
4
```
```
底下各行輸出為何?
x = "Hello"
x[0]       答案:'H'
x[5]       答案:不存在
x[-1]      答案:'o'
x[1:]      答案:'ello'
x[1:-1]    答案:'ell'
```
```
底下輸出為何?
x = "Goodbye\n"
x = x[:-1]
x
答案:'Goodbye'

```
### while loop

```
(B)(D)7根據底下程式,下列敘述何者為非?[複選題]

names = ['龍', '聖']
index = 0

while index < len(names):
    name = names[index]
    print(name)
    index = index + 1
    
(A)len(names)=2  
(B)names[1]是 龍 
(C)程式執行完後,index最後為2
(D)如果把條件改成 index > len(names),中index最後為2
```
