n8n 個人自動化服務網站（繁體中文）
================================
檔案：
- index.html：公開首頁（含服務說明、隱私權政策連結）
- privacy.html：隱私權政策
- style.css：版面設計

發布前必做：
1. 在 privacy.html 將【請替換為可公開的聯絡電子郵件】改為可公開的信箱。
2. 仔細確認資料存取、執行紀錄保存、雲端平台、第三方 AI 等段落符合實際 n8n 設定；不符合則修改後再發布。
3. 將三個檔案上傳至 GitHub 公開 repository 的根目錄，Settings > Pages > Deploy from a branch > main / (root) > Save。
4. GitHub Pages 網址格式通常為 https://<使用者名稱>.github.io/<repository>/；
   首頁為該網址，隱私權政策為該網址後加 privacy.html。
5. Google Cloud > Google Auth Platform > 品牌：將首頁、隱私權政策改成同一網域的公開網址；依介面要求設定授權網域。
6. 若要送 Google OAuth 正式驗證，Google 對首頁、隱私權政策、網域所有權、資料用途有額外要求；GitHub Pages 網址可公開，不代表必然符合網域所有權驗證條件。最好使用自己持有並可驗證的自訂網域。
7. Railway n8n 的 Google OAuth redirect URI 須保持 Railway 現行回呼網址，與公開政策頁網址不同。

注意：本檔案為可編修的政策草稿，不代表已經架設上線、已通過 Google 驗證或已審核法律合規。
