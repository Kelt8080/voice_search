

<img src="https://kelt8080.github.io/public//image/app/everything.png">　&nbsp;　<img src="https://kelt8080.github.io/public//image/app/chrome.png">


# Voice Search

即說即搜，用講的就能"立即"搜尋你的個人電腦檔案。   
效果展示:[**https://www.youtube.com/watch?v=aEkXDkTxUiE ▸**](https://www.youtube.com/watch?v=aEkXDkTxUiE)   

## Function API Overview

採用以下__API__製作完成    
`everything search engine` &ndash; 建構本機檔案index，並在本機發布成網頁   
`ChromewebkitSpeechRecognition()` &ndash; Chrome內建的語音輸入API，將語音辨識結果傳送到網頁   

## Getting Started

1. 請先安裝[everything search engine](https://www.voidtools.com/)
1. 設定你要搜尋的檔案索引磁碟與目錄，[https://www.voidtools.com/support/everything/indexes/](https://www.voidtools.com/support/everything/indexes/)
1. 設定本機everything http server，位址為127.0.0.1，[https://www.voidtools.com/support/everything/http/](https://www.voidtools.com/support/everything/http/)
1. everything search engine會自動在背景建構本機的檔案索引，時間視你的電腦效與資料量能而定，大概10min~2hours
1. 用Chrome開啟本專案網頁就可以在你的電腦上即說即搜[https://kelt8080.github.io/voice_search/](https://kelt8080.github.io/voice_search/)
1. Chrome無法同時有多個網頁進行語音辨識，一次只能一個網頁

### vision.3
* 增加後端spreadsheet紀錄搜尋紀錄
* 輸出10項最新搜尋與5項最常搜尋

### vision.2
* 加入語系切換
* 讓iframe自動調整高度

### vision.1
* 新建