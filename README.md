# Gintone Website

Gintone 底片相機 app 的官方介紹頁,部署於 [gintone.app](https://gintone.app)。

純靜態網站:`index.html`(另有 `en/`、`ja/` 多語系頁)+ `uploads/` 圖片資產,無建置流程。

- `blog/`:部落格列表與文章(`blog/<slug>/index.html`),圖片沿用 `slides/assets/`。
- `slides/`:設計理念簡報(HTML 版),`slides/assets/` 為壓縮後的 WebP 與影片。動畫使用 GSAP ScrollTrigger(CDN),字體來自 Google Fonts。

## 部署

推上 `main` 後由 GitHub Pages 自動發佈(Settings → Pages → Deploy from branch → `main` / root)。自訂網域由 `CNAME` 檔指定。

## 待辦

- [ ] App Store 上架後,把 `index.html` 裡「於 App Store 下載」按鈕的 `href="#"` 換成實際連結。
