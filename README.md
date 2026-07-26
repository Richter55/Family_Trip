# Family_Trip

## 旅遊行程規劃

本專案收集了家族旅遊的行程規劃文件（靜態 HTML 檔案）。

### 可用行程

| 行程 | 連結 | 說明 |
|------|------|------|
| 關西最終行程表 | [線上查看](https://richter55.github.io/Family_Trip/Kansai_Final_Itinerary.html) | 關西旅遊的完整行程規劃 |
| 南橫東部5日遊 | [線上查看](https://richter55.github.io/Family_Trip/%E5%8D%97%E6%A9%A5%E6%9D%B1%E9%83%A85%E6%97%A5%E9%81%8A.html) | 南橫東部地區的5天4夜行程 |

> ⚠️ 如果你在本地看到的檔名是中文，當轉成 GitHub Pages URL 時會被 URL 編碼（如上例）。為避免編碼混淆，建議未來檔名使用英文或在上傳後確認 Pages 頁面是否可以正確連到該檔案。

### 快速連結

- 📄 [Kansai_Final_Itinerary.html](./Kansai_Final_Itinerary.html)
- 📄 [南橫東部5日遊.html](./南橫東部5日遊.html)

---

## 如何將此專案公開成 GitHub Pages

1. 請先確認倉庫為公開 (Public)。
   - 到 GitHub → 設定 (Settings) → General → Repository visibility → 設為 Public。
2. 啟用 GitHub Pages：
   - 到 Settings → Pages。
   - 選擇 Source（來源）為你希望公開的分支（例如 `main` 或 `master`），資料夾選 `/(root)`，然後 Save。
3. 若你希望直接呈現目前的靜態 HTML 檔案，我已新增 `.nojekyll`（在 repository 根目錄）以避免 Jekyll 進行處理，確保所有靜態檔案都能直接被服務。
4. 等待幾分鐘，然後到 `https://<你的使用者名稱>.github.io/Family_Trip/`（本專案為 `https://richter55.github.io/Family_Trip/`）檢查頁面是否上線。

如果看到 404 或檔案找不到：
- 確認你啟用 Pages 的分支包含那些 HTML 檔案（例如 `Kansai_Final_Itinerary.html` 與 `南橫東部5日遊.html`）。
- 若檔名含有非 ASCII 字元（例如中文），URL 會被編碼，請使用 repo 的檔案列表複製檔案連結或改成英文字檔名以避免問題。


---

*最後更新：2026年7月26日*
