# Python 基本程式概念
<p>快捷鍵</p>
1.增加縮排 : tab鍵<br>
2.減少縮排 : shift+tab鍵<br>

<p>什麼是self ? 什麼是__init__ ? </p>
類(Class)物件化object而self就是自己，當在類(Class)宣告變數時(class變數)使用self.變數<br>
<b>範例:</b>
class Hello:
    def __init__(self): #最初(初始化)
        self.color = 'Red'
        self.legs = 'Long'
    def run():
        print('Python 很棒!!')

Hello.run() # Python 很棒!!

nask = Hello() # 先創具體化物件
print(nask.color) #這個類的變數
print(nask.legs)

