# Visual Design Portfolio

北歐編輯式視覺作品集網站（GitHub Pages 靜態網站）。

## 檔案
- `index.html`：公開作品集首頁，含作品分類、輪播、作品詳情與聯絡資訊。
- `admin.html`：中文作品編輯器（本機瀏覽器操作，無需寫程式）。
- `projects.json`：網站內容資料（初始沒有作品圖片，請自行新增）。

## 第一次發布
1. 開啟 Repository → **Settings** → **Pages**。
2. 在 **Build and deployment** 設定 Source 為 **Deploy from a branch**。
3. 選擇 `main` 分支和 `/(root)` 目錄，按 **Save**。
4. 公開網址預計為 https://vvv900610-cloud.github.io/portfolio/
5. 編輯器網址預計為 https://vvv900610-cloud.github.io/portfolio/admin.html

## 更新作品
1. 開啟 `admin.html`，新增作品或修改網站資料。
2. 選擇圖片，或填入上傳至 GitHub `assets/` 資料夾中的檔名。
3. 點選 **儲存作品**、**匯出網站資料**，下載新的 `projects.json`。
4. 在 GitHub 儲存庫點進 `projects.json`，按右上角鉛筆編輯：複製匯出 JSON 的完整內容，貼上取代並 Commit changes。也可以用 GitHub 網頁的 Upload files 更新同名檔案。
5. 等待 GitHub Pages 部署完成後重新整理公開網站。

### 注意事項
- 編輯器的內容會暫存在當前瀏覽器；換裝置或清除瀏覽器資料可能遺失。請保留匯出的 JSON 備份。
- 編輯器不會自動寫入 GitHub，因此**一定要完成第 4 步**才算更新公開網站。
- 不要把私人資料、密碼或存取權杖放進公開檔案。
- 選擇圖片上傳的模式會將圖片壓縮內嵌於 JSON；圖片多時建議改用 `assets/` 對應路徑，以降低檔案大小。
