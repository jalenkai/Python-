# Python 基本程式概念

## Python簡介

Python 是一種易學、功能強大的程式語言。 它有高效能的高階資料結構，也有簡單但有效的方法去實現物件導向程式設計。 Python 優雅的語法和動態型別，結合其直譯特性，使它成為眾多領域和大多數平臺上，撰寫腳本和快速開發應用程式的理想語言

簡單的說，Python是一個`優雅`、`明確`、`簡單`的編程語言。
- 開發人員可以輕鬆閱讀和理解 Python 程式,代碼規範程度高，可讀性強。
- 代碼開源系統,活躍的 Python 社群包括全球數百萬支援開發人員。
- 直釋式語言，平臺可移植性。
- 好學習,提升了開發人員的工作效率。
- 能夠通過調用Java,C/C++代碼擴展功能。
- Python 具有大型標準程式庫，其中包含幾乎所有任務的可重複使用程式碼。
- Python 可以跨不同的電腦作業系統進行移植，例如 Windows、macOS、Linux 和 Unix。
  
Pyton目前使用上的領域
- 雲基礎設施 (google cloud,AWS...)
- 網絡爬蟲
- 數據分析挖掘
- 機器學習(Keras深度神經網路程式庫,PyTorch NLP、機器人和電腦視覺...)
- 網頁web開發(Django,Flask,TurboGears...)
- 影像處理(OpenCV-Python...)

## Python馬上就上手

>開發環境設定與安裝
* Spyder (新手)[spyder官方網址](https://www.spyder-ide.org/)
* Pycharm (推薦) 社區版[Pycharm官方網址](https://www.jetbrains.com/pycharm/)
* Jupyter Notebook[jupyter官方網址](https://jupyter.org/install)
  
>基本概念

>變數命名
* 數字、大小寫英文、底線(不建議中文及外文)
* 大小寫有區別
* 開頭第一個字不可以為數字
* 不可使用Python保留字
```
(Python3.7)
序號	保留字	說明
1	and	邏輯與操作，用於表示式運算
2	as	用於轉換資料型別
3	assert	用於判斷變數或條件表示式的結果
4	async	用於啟用非同步操作
5	await	用於非同步操作中等待協程返回
6	break	中斷迴圈語句的執行
7	class	定義類
8	continue	繼續執行下一次迴圈
9	def	定義函數或方法
10	del	刪除變數或序列的值
11	elif	條件語句，與 if、else 結合使用
12	else	條件語句，與 if、else 結合使用；也可用於異常或迴圈語句
13	except	包含捕獲異常後的處理程式碼塊，與 try、finally 結合使用
14	False	含義為“假”的邏輯值
15	finally	包含捕獲異常後的始終要呼叫的程式碼塊，與 try、except 結合使用
16	for	迴圈語句
17	from	用於匯入模組，與 import 結合使用
18	global	用於在函數或其他區域性作用域中使用全域性變數
19	if	條件語句，與 elif、else 結合使用
20	import	匯入模組，與 from 結合使用
21	in	判斷變數是否在序列中
22	is	判斷變數是否為某個類的範例
23	lambda	定義匿名函數
24	None	表示一個空物件或是一個特殊的空值
25	nonlocal	用於在函數或其他作用域中使用外層（非全域性）變數
26	not	邏輯非操作，用於表示式運算
27	or	邏輯或操作，用於表示式運算
28	pass	空的類、方法或函數的預留位置
29	raise	用於丟擲異常
30	return	從函數返回計算結果
31	True	含義為“真”的邏輯值
32	try	測試執行可能出現異常的程式碼，與 except, finally 結合使用
33	while	迴圈語句
34	with	簡化 Python 的語句
35	yield	從函數依次返回值
 
```

>變數使用

使用變數儲存並進行算術運算
```
  a = 321
  b = 123
  print(a + b)
  print(a - b)
  print(a * b)
  print(a / b) #除- x除以y
  print(a // b) #取整除- 返回商的整數部分
  print(a % b)  #返回除法的餘數
  print(a ** b) #平方
```
