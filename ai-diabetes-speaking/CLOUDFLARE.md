# Cloudflare Pages 部署

網站為純靜態 HTML/CSS/JavaScript，不需要 API key 或付費語音服務。GitHub 程式碼頁本身不會執行播放器。

## 從 GitHub 連接

1. 登入 Cloudflare，選 Workers & Pages，建立 Pages 專案並連接 GitHub。
2. 選擇 `zinojeng/aislide`。
3. Production branch：`main`。
4. Root directory：`ai-diabetes-speaking`。
5. Framework preset：None。
6. Build command：`exit 0`。
7. Build output directory：`dist`。
8. 建立專案後，Cloudflare 會提供實際的 `pages.dev` 網址。以平台回傳值為準，請勿假定某個網域已建立。

後續 main 分支此目錄的變更可由 Git 整合自動部署。不要改動此 repository 其他既有專案的部署設定。

## 直接上傳

也可以建立獨立 Pages 專案，將 dist 內檔案作為靜態網站上傳。此方式後續不會自動追蹤 GitHub 更新。

## 語音與使用

- 開啟頁面後由使用者點擊播放，避免自動播放限制。
- 需裝置提供英文語音；Safari/Mac 可以選裝置上的英文聲音。不同瀏覽器提供的名稱與品質不完全相同。
- 選擇 0.75×，逐句重複 2 次，間隔 4 秒，即可跟讀。
- 語音為合成語音，不是 MP3。部分聲音可能使用供應商的網路服務，是否離線取決於聲音。
- 網站不使用後端，也不儲存使用者錄音。練習進度存在瀏覽器 localStorage。
- 網頁提供講稿與發音提示；原投影片圖片未打包。

## 參考

- https://developers.cloudflare.com/pages/framework-guides/deploy-anything/
- https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis
- https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesisUtterance/rate
