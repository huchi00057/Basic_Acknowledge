## 命令提示字元切至 D槽
由於預設開啟為 C槽，假若直接 cd 非C槽路徑根本沒辦法，此時就需要先切到 D槽，才能任意遊走。

    cd /d d:
    
## / \ 分不清
在撰寫程式中，由於 \為特殊符號，時常發生語法錯誤，此時就要"多"打 \來解決此問題。

另外
  
    /   #是 Linux   系統路徑用的符號
    \   #是 Windows 系統路徑用的符號
    
![image](https://user-images.githubusercontent.com/46515944/190129060-24813e19-2de0-4b5f-a1ff-7e4f11dbcb87.png)

## 常用快捷鍵
    Win + M                #回桌面
    Win + E                #檔案總管/開資料夾
    Win + Tab              #切換視窗
    Win + Shift + S        #截圖
    Tab                    #右縮排
    Tab + Shift            #左縮排
    Ctrl + R               #執行視窗 (輸入cmd 開啟命令提示字元)
    Ctrl + Shift + Ese     #工作管理者
    
## 開機時固定開啟某些軟體(新增.bat檔)
先創建一個記事本.txt，儲存時再將副檔名改成.bat即可!!

    start 網址             #start www.google.com
    start 路徑\軟體名稱     #start D:/User/AppData/line.exe
    
