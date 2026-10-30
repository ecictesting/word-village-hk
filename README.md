# 字字小村莊

香港幼兒繁體中文及廣東話學習平台。143 個學習項目，含認字、造句、送貨任務及收藏小屋。

## 發布

GitHub Settings → Pages → Source 選 Deploy from a branch，Branch 選 main、/(root)。推送至 main 後會自動發布網站。公開網站唔包含小朋友嘅錄音或學習紀錄。

## 更新

日後在原本聊天講「加中文字」→ 生成無字圖片 → 確認 → 更新本儲存庫。小朋友一直用同一條網址。改圖用新檔名，再更新 words.js 的 image，減少快取影響。

- 字詞：site/village/words.js
- 加入批次／學習功能：site/village/village.js
- 認字圖片：site/assets/
- 遊戲：site/village/adventure.js
- 插畫及動作分鏡：site/village/art/

圖片已另行輸出 WebP 網站版本；原始 PNG 保留在本機，網站版沒有創意改圖。圖片只在顯示時載入。

## iPad／手機

使用 Safari／Chrome 開啟網站。在 iPad 可用分享 → 加入主畫面。首次朗讀需點按；錄音需允許咪權限。粵語聲音取決於裝置，未有合適聲音會顯示家長陪讀。

進度及收藏留在同一瀏覽器，唔會自動跨裝置同步；轉裝置前可在家長頁匯出進度，再在另一裝置匯入。錄音不會上傳或永久儲存，離頁會清除；想保留請先下載。

## 更新前檢查

執行 node check-site.cjs。沒有 API 密鑰、後端、登入或資料庫。網站與程式碼為公開。


