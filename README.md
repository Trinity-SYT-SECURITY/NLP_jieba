

將你要做關鍵字搜索的txt文件，丟到目錄下，請自行更改目錄路徑，user在輸入要查詢的關鍵字時，就會得到是在哪個文件名稱底下找到的，這部分可以根據自身需求做修改，我是因為已經把所有的txt文件名稱改成了我要的結果樣子。

比如說你要搜尋某CVE底下的某個產品名稱跟他的漏洞版本，這裡先將txt檔案各自根據CVE編號下去命名，txt的內容是對應CVE漏洞資料，當然，因為幾百份檔案不可能一一慢慢下去處理，所以這裡我另外寫了一個爬蟲程式去抓，我會丟到github上~

假設現在目錄下有CVE-2022-1111.txt、CVE-2021-2233.txt...這類檔案，那麼程式在讀取過後，會先將讀到的內容給print出來，最後問使用者想要搜索甚麼關鍵字，使用者可以依照自身想搜尋的內容，比如想查某產品編號是否有漏洞之類的...，就把它當作Google的搜尋引擎那樣玩就對了~不過是低配版搜索引擎ㄌ，最後我會嘗試用spacy去做高配版的，敬請期待><


![image](https://user-images.githubusercontent.com/96654161/219575481-1c221a83-6222-47b7-a470-86c8afb58715.png)
