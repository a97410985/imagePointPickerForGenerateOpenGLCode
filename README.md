# imagePointPickerForGenerateOpenGLCode
# 執行說明
要開本地伺服器傳送html，不然會有問題，可以使用python的模組來將一個目錄設為本地伺服器的目錄

安裝模組
> pip install httpserver

移動到要服務的目錄下執行下面指令
> python -m http.server

https://www.youtube.com/watch?v=jN9VTQf3n5M

### 目標 : 我覺得用opengl一個一個取點太累了，就寫了一個簡單的取點網頁程式
### 有四種模式 : 增加點、刪除點、取目前滑鼠位置落在圖片上的像素的顏色、選擇圖形類型以及幾個點將他們設為群組，之後會生成對應的opengl code
### 可以匯出目前點的位置、樣式與群組設定，然後可以用匯出的文字再去設定點的位置、樣式與群組設定
### 目前只能生成超智障的opengl程式碼，之後多加一些圖形(很簡單)，未來希望能有貝茲曲線(有點難)
