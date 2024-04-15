ex-5題目:
編寫程式，生成一個包含50個隨機整數的清單，然後刪除其中所有奇數。（注意保證刪除操作的效率）

程式碼如下:
import random
x=[random.randint(0,100)for i in range(50)]
print(x)
i=len(x)-1
while i>=0:
    if x[i]%2==1:
        del x[i]
    i-=1
print(x)

程式截圖:
https://github.com/aY-Dling/midterm-exam/blob/main/ex5.python.png

