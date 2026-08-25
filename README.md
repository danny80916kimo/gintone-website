# Gintone Website

Gintone 底片相機 app 的官方介紹頁,部署於 [gintone.app](https://gintone.app)。

純靜態網站:單一 `index.html` + `uploads/` 圖片資產,無建置流程。動畫使用 GSAP ScrollTrigger(CDN),字體來自 Google Fonts。

## 部署

推上 `main` 後由 GitHub Pages 自動發佈(Settings → Pages → Deploy from branch → `main` / root)。自訂網域由 `CNAME` 檔指定。

## 待辦

- [ ] App Store 上架後,把 `index.html` 裡「於 App Store 下載」按鈕的 `href="#"` 換成實際連結。
