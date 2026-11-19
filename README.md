# maimai 日本版樂曲資料庫

網站包含案例背景、ERD／欄位設計、可編輯並執行的 SQLite SELECT／WITH 查詢、SQL 結果比較及歌曲搜尋篩選。

GitHub Actions 在部署時會下載 SEGA 日本版官方現行資料 https://maimai.sega.jp/data/maimai_songs.json，再部署到 GitHub Pages。現行資料快照不保證包含已刪除歌曲；來源未提供的譜面作者及日期不會自行補造。

## 啟用 Pages
進入 Settings → Pages，將 Build and deployment 的 Source 設為 GitHub Actions。推送 main 後，Actions 自動部署。網址：https://11446022-cpu.github.io/maimai/

本專案為學習用途，非 SEGA 官方網站。
