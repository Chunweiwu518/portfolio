# 作品集網站更新指南

**網站網址：** https://chunweiwu.netlify.app  
**GitHub Repo：** https://github.com/Chunweiwu518/portfolio  
**本地資料夾：** `C:\Users\wuchu\Desktop\portfolio_deploy`

---

## 更新網站步驟

1. 修改 `portfolio_deploy\index.html`（改文字、換截圖等）
2. 執行以下指令推上 GitHub，Netlify 會自動部署：

```powershell
cd C:\Users\wuchu\Desktop\portfolio_deploy
git add -A
git commit -m "更新說明（例如：新增XX專案）"
git push origin main
```

約 1~2 分鐘後網站自動更新完成。

---

## 替換專案截圖

截圖放在 `portfolio_deploy\images\` 資料夾，對應關係如下：

| 檔案名稱             | 對應專案              |
|--------------------|--------------------|
| `ke_ming.png`      | 科明 AI 知識庫系統    |
| `erp.png`          | ERP 管理系統         |
| `translation.png`  | 即時翻譯聊天系統       |
| `cyberbiz.png`     | Cyberbiz 自動化工具   |
| `transcription.png`| 會議錄音逐字稿系統     |
| `waterdrop.png`    | 電商賣家後台           |
| `backtest.png`     | 量化回測平台           |
| `ml.png`           | 機器學習 NLP 專案     |

替換截圖後同樣執行上面的 git 指令即可。

---

## 備用：手動部署（若 GitHub Actions 有問題）

```powershell
$env:NETLIFY_AUTH_TOKEN = "nfc_2aEbPRDMZyMnGeHPPe98knsG5iMeWCkY63f1"
$env:NETLIFY_SITE_ID = "558fc5f2-2302-49de-9876-bd921ab8f508"
netlify deploy --prod --dir "C:\Users\wuchu\Desktop\portfolio_deploy"
```

---

## 聯絡與帳號資訊

- **Netlify 帳號：** wuchunwei0518@gmail.com  
- **Netlify Site ID：** `558fc5f2-2302-49de-9876-bd921ab8f508`  
- **GitHub：** Chunweiwu518
