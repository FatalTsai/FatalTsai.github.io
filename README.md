# 個人作品集｜內容少改，設計保留

這份網站保留人物側欄、作品卡片、照片錯落排列、時間軸、手機版、圖片放大、章節高亮及列印。它們都已經做好，不是基礎作業。

## 先開哪裡
完整解壓縮。VS Code → File → Open Folder → 本資料夾；`index.html` 要直接位於根目錄。瀏覽器可直接開 `index.html`，無需 npm、安裝相依套件、後端或網路 CDN。

## 你只需要修改
`index.html` 裡的 EDIT 01–05 標記，以及 `images/` 的照片。

| 檔案 | 第一堂要改嗎？ | 用途 |
|---|---|---|
| index.html | 是，按指定 selector 改文字/屬性 | 真正的個人內容 |
| images/ | 放自己的圖 | 頭像1張＋生活2張＋專案1張 |
| styles.css | 不用 | 固定排版、手機版、圖片呈現 |
| theme.css | 不用；課後配色選填 | 少量外觀變數 |
| app.js | 不用 | 手機選單、照片放大、目前章節、列印 |
| .github/ | 不用 | 老師設定的檢查與發布 |

換照片只改該 `img` 的 `src`、`alt`。放大視窗會讀同一元素，不另填大圖路徑。基礎不修改 JS。
1–2個專案、2–3張生活照即可。未參加過的活動不要保留；刪整個 section 時同步清掉 side-nav 中對應 a。

## 檔案上限
網站：1 HTML、2 CSS、1 JS。上限為每種最多2個；不是要求把輔助程式刪短。

## 發布
老師 Template 已有 `.github/workflows/pages.yml`。在自己的副本選 `Settings → Pages → Source → GitHub Actions`。
上傳變更後的 `index.html` 與圖片，Commit 後查看最新 Actions，最後實際打開 Pages URL。
不要上傳 ZIP 本體、教師簡報、工作表或 `website/` 外層資料夾。

本版本有更新 `theme.css` 與對應 workflow。老師需要先把整個本版放進模板，不可只拿新 HTML 搭配旧樣式／舊 workflow。

## 實際示範內容
林予安及學校是虛構。攝影照片是素材，詳見 CREDITS.md，不代表學生本人。
