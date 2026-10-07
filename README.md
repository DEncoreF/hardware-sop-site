# 硬體請採購及庫存作業流程（對外檢視版）

純靜態網站，沒有建置步驟。共三頁：

- `index.html`：硬體請採購及庫存作業流程
- `shipping.html`：AISO 一體機出貨流程
- `route-guide.html`：庫存作業路線導覽

- 本機預覽：`python3 -m http.server 8080`，然後開 http://localhost:8080
- 部署：推到 GitHub 的 `main` 分支，GitHub Pages 設定為「Deploy from a branch → main → / (root)」
- 更新內容：以新版 `index.html` 覆蓋後 commit、push，約一分鐘後生效

內容來源為 Claude 上的 SOP 頁面；此版本已移除頁面內編輯與儲存功能，僅供檢視。
`index.html` 內含 `noindex`，不會被搜尋引擎收錄，但知道網址的人都能開啟。
