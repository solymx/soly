# cybersecurity-portfolio
Record
## malware.html

這檔案不用動，會去抓 malware-data.json ，所以要添加資料只需動這個 Json

直接開會遇到 cors 問題，所以:
1. 用 VS Code 開啟你 HTML 檔所在資料夾。
2. 安裝並啟用 Live Server 插件。
3. 右鍵點 malware.html → 選「Open with Live Server」。
4. 頁面會在 http://127.0.0.1:5500/malware.html 形式開啟，問題解決！


## certs.html

tag 上顏色，需要改兩個地方，首先是定義顏色
```
.tag.red {
  background-color: #ff4d4d;
}
.tag.blue {
  background-color: #4d94ff;
}
.tag.purple {
  background-color: #b266ff;
}
```

接下來是設定哪個字對應哪個顏色
```
    const tagColorMap = {
      "紅隊": "red", "Red Team": "red",
      "藍隊": "blue", "Blue Team": "blue",
      "雲端": "purple", "Cloud": "purple"
    };
```
