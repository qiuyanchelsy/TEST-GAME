# AI 四格漫畫產生機

學生網址：https://qiuyanchelsy.github.io/TEST-GAME/four-panel-comic/

## 目前狀態
- GitHub Pages 靜態網頁，學生免登入。
- 可選主題、參考照片、風格、自編四格與下載文字劇本。
- 示範插圖為預先生成的 AI 圖片。
- **即時 AI 繪圖尚未啟用**：來源程式的兩處 API 金鑰都是空字串，目前按鈕已停用。

## 啟用 AI 的必要條件
GitHub Pages 不執行後端程式。需另設伺服器端 API，使用老師端有效 Gemini API 金鑰及額度，前端只連接此 API。不可將金鑰填入公開 HTML、GitHub 儲存庫，或透過 Actions 將秘密寫入瀏覽器程式。
目前保留的原始繪圖函式使用舊預覽模型；啟用時須改接後端、更新模型、驗證實際生成及下載，再移除停用提示與提前返回。
