# 作品集網站更新指南

**網站網址：** https://chunweiwu.netlify.app  
**GitHub Repo：** https://github.com/Chunweiwu518/portfolio  
**本地資料夾：** `C:\Users\wuchu\Desktop\portfolio_deploy`

---

## ✅ 更新網站步驟（目前用這個）

修改 `portfolio_deploy\index.html` 後，執行：

```powershell
$env:NETLIFY_AUTH_TOKEN = "nfc_2aEbPRDMZyMnGeHPPe98knsG5iMeWCkY63f1"
$env:NETLIFY_SITE_ID = "558fc5f2-2302-49de-9876-bd921ab8f508"
cd C:\Users\wuchu\Desktop\portfolio_deploy
netlify deploy --prod --dir .
```

約 10 秒網站更新完成。

---

## 🚀 GitHub 自動部署（之後啟用）

GitHub Actions 已設定好（`.github/workflows/deploy.yml`），但**新帳號需要等 GitHub 審核通過 runner** 才能自動跑（通常 1~2 天）。

啟用後只要 git push，Netlify 就會自動更新：

```powershell
cd C:\Users\wuchu\Desktop\portfolio_deploy
git add -A
git commit -m "更新說明"
git push origin main
```

---

## 替換專案截圖

截圖放在 `portfolio_deploy\images\` 資料夾：

| 檔案名稱             | 對應專案              |
|--------------------|--------------------|
| `ke_ming.png`      | 科明 AI RAG Chat 系統 |
| `erp.png`          | ERP 管理系統         |
| `translation.png`  | 即時翻譯聊天系統       |
| `cyberbiz.png`     | Cyberbiz 自動化工具   |
| `transcription.png`| 會議錄音逐字稿系統     |
| `waterdrop.png`    | 電商賣家後台           |
| `backtest.png`     | 量化回測平台           |
| `ml.png`           | 機器學習 NLP 專案     |

替換後執行上面的 netlify deploy 指令即可。

---

## 帳號資訊

- **Netlify 帳號：** wuchunwei0518@gmail.com
- **Netlify Site ID：** `558fc5f2-2302-49de-9876-bd921ab8f508`
- **Netlify Token：** `nfc_2aEbPRDMZyMnGeHPPe98knsG5iMeWCkY63f1`
- **GitHub：** Chunweiwu518
