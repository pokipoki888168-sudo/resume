# 袁郡竑 (Yuan, Jun-Hong) - 個人履歷網站

這是一份專為 **袁郡竑** 量身打造的個人履歷網頁，採用 **簡約現代（Clean & Modern）** 風格設計，具備良好的響應式版面（支援手機、平板與電腦），並針對列印/另存 PDF 進行了格式優化。

---

## 🌟 網站特色
- **現代簡約排版**：白底清爽設計搭配專業墨綠/藍綠強調色。
- **行動裝置友善 (RWD)**：不管是手機、平板或電腦都能完美瀏覽。
- **企管與門市營運結合**：將萬能科大企業管理系學歷與 7-11 第一線服務實務完美包裝。
- **互動功能**：一鍵複製 Email、直接郵件發送、平滑錨點跳轉、列印友善按鈕。
- **完全純靜態**：無需安裝任何後端或伺服器，直接支援 GitHub Pages 免費託管。

---

## 🚀 部署到 GitHub Pages 教學（網頁直接上傳，免安裝任何軟體）

### 步驟 1：登入 GitHub 並新增儲存庫 (Repository)
1. 前往 [GitHub 官網](https://github.com/) 並登入您的帳號。
2. 點擊右上角的 **「+」** 號，選擇 **「New repository」**。
3. 設定儲存庫：
   - **Repository name**（建議命名）：`resume` 或是 `<您的帳號名稱>.github.io`
   - **Visibility**：選擇 **Public**（公開，GitHub Pages 免費用戶需為 Public）
   - 其他選項保持預設即可，點擊最下方的 **「Create repository」**。

---

### 步驟 2：上傳履歷檔案
1. 建立完成後，在頁面中間找到 **「uploading an existing file」** 連結。
2. 將本專案資料夾內的 `index.html` 直接**拖曳進網頁**中。
3. 頁面下方點擊綠色的 **「Commit changes」** 按鈕儲存。

---

### 步驟 3：啟用 GitHub Pages 免費網站託管
1. 在該儲存庫上方點選 **「Settings」**（設定）。
2. 在左側選單找到 **「Pages」**。
3. 在 **Build and deployment** 下方的 **Branch**：
   - 將 `None` 切換選擇為 **`main`**（或 `master`）。
   - 資料夾保持為 `/ (root)`。
   - 點擊 **「Save」**（儲存）。
4. 等候約 1 ~ 2 分鐘，重新整理頁面，頂部就會出現您的專屬網址：
   > `https://<您的GitHub帳號>.github.io/resume/` 或是 `https://<您的GitHub帳號>.github.io/`

恭喜！您的個人履歷網站就正式上線了！ 🎉

---

## 📷 如何換成自己的大頭照？
1. 準備一張您的照片，命名為 `avatar.jpg`。
2. 將照片放入與 `index.html` 相同的資料夾。
3. 打開 `index.html`，找到第 142 行的頭像區塊，將原本的 `<svg>...</svg>` 替換為：
   ```html
   <img src="avatar.jpg" alt="袁郡竑" class="w-full h-full object-cover">
   ```
4. 儲存後重新上傳到 GitHub 即可！
