# TripRadar (GitHub Pages Demo)

行前 1 分鐘，一眼看出旅遊舒適度。  
結合 **氣象署 CWA** 與 **環境部 MoENV** 之 OpenData，自動計算 13 個國家風景區的「**建議旅遊分數**」。

- 手機版介面（App 感）
- 可切換「使用所在地加權」（同縣市 +5、鄰近 +2、遠距 −5、離島差異 −10）
- 連線失敗自動 fallback 為示意資料（適合現場展示）

---

## 🔧 一鍵部署到 GitHub Pages

1. 到你的 GitHub 帳號 [`IvanChenAW`](https://github.com/IvanChenAW) 建立新 repo（建議名稱：`TripRadar`）。
2. 上傳兩個檔案：`index.html` 與 `README.md`（放在 repo 根目錄）。
3. 進入 **Settings → Pages → Build and deployment**：
   - **Source**：`Deploy from a branch`
   - **Branch**：選 `main`，資料夾選 `/ (root)`
4. 儲存後等 1–2 分鐘，開啟：
