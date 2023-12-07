### 第一幕
#### [背景](https://images.unsplash.com/photo-1624953587687-daf255b6b80a?q=80&w=1000&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8cHl0aG9uJTIwY29kZXxlbnwwfHwwfHx8MA%3D%3D)   
# Python教學
作者:曾、林   


---

### 第二幕
#### [背景](https://github.com/iPigTW/school-project/blob/main/bg2.png?raw=true)
# 什麼是Python

「Python是一種廣泛使用的直譯式、進階和通用的程式語言。」 - 維基百科   
「Python是一種非常通用的程式語言，適合新手學習。」 - 曾

---

### 第三幕
#### [背景](https://devblogs.microsoft.com/python/wp-content/uploads/sites/12/2018/08/pythonfeature.png)
# 如何下載Python
1.到[python.org](https://python.org)   
2.點Downloads   
3.點Download for Windows底下的Python 3.12.0   -註:此處的3.12.0為Python版本，以後可能會改變   
4.打開下載好的檔案，點Install Now

---

### 第四幕
#### [背景](https://media.geeksforgeeks.org/wp-content/uploads/20191023173512/Python-data-structure.jpg)
# Python的資料型態
何為資料型態? 資料型態就是指，文字(str or string)、整數(int or integer)、浮點數(float)(小數)、布林值(boolean or bool)等  
什麼是布林值(boolean)? 布林值很簡單，其實就是"是否"，比如說一個布林值可以是true(是)或false(否)

---

### 第五幕
#### [背景](https://pimylifeup.com/wp-content/uploads/2019/11/variables-in-python-thumbnail-nowm.jpg)
# Python的變數
什麼是變數? 變數就是把一個資料存在一個指定的詞裡，例如我把1存到x裡，下次我要用到1的時候就可以打x   
如何定義變數? 要定義一個變數只需打 [名稱] = [資料] 如: `x = 1`     
如何定義文字變數? 同樣的，用 [名稱] = [資料]，但是資料一定要用""作為開頭、結尾 如: `x = "文字"`

---

### 第六幕
#### [背景](https://github.com/iPigTW/school-project/blob/main/bg3.png?raw=true)
# 如何輸出Hello World
每個程式設計師第一個程式都是Hello World，今天我們要在Python裡做出來。   
首先新創個檔案，後面要加.py。然後在裡面輸入`print("Hello World")`   
解釋: print這個函數(function)會在終端機裡顯示出你叫他說的東西

---

### 第七幕
#### [背景](https://miro.medium.com/v2/resize:fit:1400/1*MGV0wog7EzunCowymzE3Xg.png)
# If聲明
什麼是if聲明? if就是指"如果"，比如說，我想要讓程式確認x是不是1，我就可以寫   
```
if x == 1:
    print("x是1")
```
至於為什麼要用==而不是=呢? 是因為=是用來定義變數的，==是用來檢查條件是否成立的。   
而且有注意到嗎? 第二行我空了好幾格，這是因為Python規定在:後換行都要有空一格以上。   
我們還可以在後面加上else，也就是"不然"，例如   
```
if x == 1:
    print("x是1")
else:
    print("x不是1")
```
或是加上elif，也就是"不然如果是(else if)"的縮寫，例如   
```
if x == 1:
    print("x是1")
elif x == 2:
    print("x是2")
else:
    print("x不是1")
```

---
