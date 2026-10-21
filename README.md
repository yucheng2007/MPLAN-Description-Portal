# MPLAN Description Portal

MP Series MOCVD — Static Edition

獨立靜態介面，只有 HTML / CSS / JavaScript，不依賴 Sites。

## 使用方式
首次開啟請設定本機操作密碼，再上傳 CSV 或匯入本靜態版備份。初始機型為 M2P-R1、M2P-R2、MP803，沒有任何機台檔案。

支援機型下拉選單、CSV 上傳與下載、版本歷史、本機操作紀錄、資料備份與還原。

資料只儲存於目前瀏覽器的 IndexedDB，不會上傳 GitHub；不同裝置沒有共用資料。清除網站資料會刪除本機內容，請定期 Export Backup。

本機操作鎖不是伺服器安全認證，無法提供可信 IP、Email 通知或多人共享後台。

## 複製與部署
下載此儲存庫後執行 `python -m http.server 8080 --bind 127.0.0.1`，開啟 http://localhost:8080。
GitHub Pages 使用 main 分支根目錄；發布內容僅限靜態介面。請勿將 CSV、備份 JSON、密碼或正式操作紀錄提交此公開儲存庫。
