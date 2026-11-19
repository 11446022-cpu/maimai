# maimai 日本版樂曲資料庫

本網站採單檔式部署：**1,607 首歌曲的 JSON 資料已直接內嵌在 index.html**，開啟網站時不需要另外下載或放置 maimai_songs.json。

## 網站功能
- 案例背景、使用者與問題說明
- songs／charts 關聯式資料庫設計、ERD、欄位說明及樣本資料
- 可修改並執行的 SQLite SELECT／WITH 查詢，顯示結果或錯誤
- SQL 查詢結果比較
- 歌曲文字搜尋、分類／版本／難度／等級篩選
- CSV 匯出及手動匯入 JSON

## GitHub Pages
網站網址：https://11446022-cpu.github.io/maimai/

GitHub Actions 只需部署 index.html；歌曲 JSON 已包含在 HTML 內，不需要額外的 JSON 檔案。SQLite 函式庫仍透過 CDN 載入，因此 SQL 練習功能首次使用時需要網路連線。

## 資料來源與限制
資料快照來源為 SEGA 日本版官方資料及既有專案資料整理。現行資料快照不保證包含所有已刪除歌曲；來源未提供的譜面作者或有效日期不會自行補造。

本專案為社群資料整理與學習用途，非 SEGA 官方網站。
