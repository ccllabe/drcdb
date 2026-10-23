Dr.C database homepage

首頁網址：https://ccllabe.github.io/drcdb/

此專案只託管原 `/P097v5/index.php` 首頁的靜態內容、首頁統計圖表與必要的 Chart.js 檔案。GitHub Pages 不執行 PHP；網站查詢、下載、教學、聯絡表單與管理功能均留在原伺服器。

功能頁面連結使用 `http://120.126.17.213:58038/P097v5/`。HOME 導向此 GitHub Pages 首頁。

首頁統計與圖表為 2026-10-23 擷取的快照，不會向後端發送跨站 API 請求。更新首頁數字時，需重新匯出首頁顯示的統計與圖表內容，再更新 `index.html`。

發布來源為此專案的 `main` 分支根目錄。專案不包含 PHP 原始碼、資料庫匯出、帳密或登入工作階段。
