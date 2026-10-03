V19 GitHub Pages / iOS Offline

部署：
1. 將 ZIP 解壓後，把內容全部放到 GitHub repository 的 Pages 發佈根目錄。
2. GitHub Pages 必須使用 HTTPS（GitHub Pages 預設符合）。
3. iPhone 第一次請保持連線，以 Safari 開啟 GitHub Pages 網址。
4. 等頁面完整載入一次後，Safari 分享 > 加入主畫面。
5. 從主畫面開啟一次；之後可在無網路時使用。

重要：
- 圖片全部內嵌在 index.html，離線不需要另外抓圖片。
- Service Worker 會快取 index.html、manifest 與 icon。
- 若未先成功線上載入/安裝 Service Worker，無法保證第一次就離線。
