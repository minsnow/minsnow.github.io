# GitHub Pages 個人網站（Starter）

這是一個可直接部署的**純靜態**個人網站模板：首頁 / 作品集 / 關於我。

## 快速開始

1. 登入 GitHub，建立一個新的公開 repo，名字取：`yourusername.github.io`
2. 把本資料夾所有檔案上傳（或 `git push`）
3. 幾分鐘後，拜訪：`https://yourusername.github.io` 就能看到網站

> 如果你用的是「非 user site」的 repo（名字不是 `yourusername.github.io`），記得到 **Settings → Pages** 啟用，Source 選 main 分支。

## 自訂

- 站名 / 聯絡方式：修改 `index.html`、`about.html` 內文字與連結
- 作品內容：編輯 `projects.html` 內卡片；圖片放在 `assets/`
- 樣式：調整 `styles.css`
- 404 頁：修改 `404.html` 文字
- 關閉 Jekyll（可保留）：`.nojekyll`

## 綁定自有網域（選用）

1. 在 repo 根目錄建立 `CNAME` 檔，內容只有你的網域：例如 `portfolio.example.com`
2. 到網域註冊商新增 CNAME 記錄，指向 `yourusername.github.io`
3. 等待 DNS 生效後，進入 `Settings → Pages` 勾選 Enforce HTTPS

## 本地開發（選用）

- 直接打開 `index.html` 頁面即可預覽
- 或使用任何靜態伺服器（如 `python -m http.server 8000`）

---

MIT License。
