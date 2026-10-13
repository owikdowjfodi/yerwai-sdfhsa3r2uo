# M2 無限答題練習（完整版·單一檔案）

HKDSE 數學延伸單元二練習 App。整個介面、題庫（含教材題）、AI 出題模組與私隱政策
全部內嵌在 `index.html` 一個檔案裡 —— 沒有子資料夾、沒有外部 CDN，離線也能用。

## 上載到 GitHub Pages（3 步）

1. 在 GitHub 開一個 repo，把 `index.html` 上載到 **repo 根目錄**（檔名保持 `index.html`）。
2. repo → **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**。
3. 等 1–2 分鐘，開 `https://<你的帳號>.github.io/<專案>/`。

也可以直接在「檔案總管」雙擊 `index.html` 使用，或拖到任何靜態網頁主機。

## 說明

- 進度只存在瀏覽器 localStorage，不上傳、不收集任何資料。
- AI 出題（選用、預設關閉）：要自己填 API Key（DeepSeek／OpenAI 相容端點／本機 Ollama），
  Key 只存在你的瀏覽器，並直接送到你填的端點；本練習沒有後端。
- 重新產生這個檔案：`node tools/build-github.js`（或 `npm run github`）。

## 注意

放上 GitHub Pages 等於公開發佈，任何人只要有網址就能看到全部內容（包括教材原文題）。
不想公開請改用本機開啟，或有密碼保護的主機。
