---
marp: true
theme: default
paginate: true
size: 16:9
style: |
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;700;900&family=Inter:wght@400;600;700&display=swap');

  * { font-family: 'Noto Sans TC', 'Inter', sans-serif; box-sizing: border-box; }

  section {
    background: #0f172a;
    color: #e2e8f0;
    padding: 48px 64px;
    font-size: 18px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  section.cover {
    background: linear-gradient(145deg, #0f172a 0%, #1a2744 60%, #0c1a2e 100%);
    justify-content: center;
    align-items: flex-start;
    padding: 60px 80px;
  }

  section.light {
    background: #f8fafc;
    color: #0f172a;
  }

  section.light h2 { color: #0f172a; }
  section.light p, section.light li { color: #334155; }

  h1 {
    font-size: 3em;
    font-weight: 900;
    line-height: 1.1;
    margin: 0 0 8px 0;
    color: #fff;
  }

  h2 {
    font-size: 2em;
    font-weight: 800;
    margin: 0 0 16px 0;
    color: #fff;
  }

  h3 {
    font-size: 1.15em;
    font-weight: 700;
    margin: 0 0 8px 0;
  }

  .role {
    font-size: 1.35em;
    font-weight: 400;
    background: linear-gradient(135deg, #38bdf8, #818cf8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 32px;
    display: block;
  }

  .badge {
    display: inline-block;
    background: rgba(16,185,129,0.15);
    border: 1px solid rgba(16,185,129,0.5);
    color: #34d399;
    padding: 4px 16px;
    border-radius: 100px;
    font-size: 0.7em;
    font-weight: 700;
    letter-spacing: 0.08em;
    margin-bottom: 20px;
  }

  .stats {
    display: flex;
    gap: 40px;
    margin-top: 32px;
  }

  .stat-num {
    font-size: 2.2em;
    font-weight: 900;
    color: #38bdf8;
    display: block;
    line-height: 1;
  }

  .stat-label {
    font-size: 0.65em;
    color: #64748b;
    letter-spacing: 0.1em;
  }

  .tag {
    display: inline-block;
    background: rgba(14,165,233,0.12);
    border: 1px solid rgba(14,165,233,0.3);
    color: #38bdf8;
    padding: 3px 12px;
    border-radius: 100px;
    font-size: 0.65em;
    font-weight: 600;
    margin: 3px 2px;
  }

  .tag.green {
    background: rgba(16,185,129,0.12);
    border-color: rgba(16,185,129,0.3);
    color: #34d399;
  }

  .tag.purple {
    background: rgba(99,102,241,0.12);
    border-color: rgba(99,102,241,0.3);
    color: #818cf8;
  }

  .card {
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: 16px;
    padding: 20px 24px;
    margin-bottom: 12px;
  }

  .card.light-card {
    background: #fff;
    border: 1px solid #e2e8f0;
    color: #0f172a;
  }

  .grid2 { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
  .grid3 { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 16px; }

  .accent-line {
    width: 60px; height: 4px;
    background: linear-gradient(90deg, #38bdf8, #818cf8);
    border-radius: 4px;
    margin-bottom: 20px;
  }

  .section-label {
    font-size: 0.65em;
    font-weight: 700;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: #38bdf8;
    margin-bottom: 8px;
  }

  .highlight {
    background: rgba(56,189,248,0.08);
    border-left: 3px solid #38bdf8;
    padding: 16px 20px;
    border-radius: 0 12px 12px 0;
    font-size: 0.85em;
    color: #cbd5e1;
    line-height: 1.8;
    margin: 16px 0;
  }

  .sk-icon { font-size: 1.8em; margin-bottom: 8px; display: block; }

  footer {
    position: absolute !important;
    bottom: 24px !important;
    right: 64px !important;
    font-size: 0.6em !important;
    color: #334155 !important;
  }

  section::after {
    position: absolute;
    bottom: 24px;
    right: 64px;
    font-size: 0.6em;
    color: #334155;
  }

  .contact-item {
    display: flex;
    align-items: center;
    gap: 16px;
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: 12px;
    padding: 14px 20px;
    margin-bottom: 10px;
  }

  .ci-icon { font-size: 1.4em; }
  .ci-label { font-size: 0.6em; color: #64748b; }
  .ci-val { font-size: 0.85em; font-weight: 700; color: #38bdf8; }

  .proj-cat {
    font-size: 0.6em;
    font-weight: 700;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: #818cf8;
    margin-bottom: 4px;
  }
---

<!-- _class: cover -->
<!-- paginate: false -->

<div class="badge">🟢 接案中 · 可立即開始合作</div>

# 吳竣瑋
## <span class="role">全端工程師 · AI 應用開發專家</span>

**CW Wu** — 打造 AI 驅動的商業應用，協助企業數位轉型

<div class="stats">
  <div>
    <span class="stat-num">50+</span>
    <span class="stat-label">GitHub Projects</span>
  </div>
  <div>
    <span class="stat-num">10+</span>
    <span class="stat-label">商業案例</span>
  </div>
  <div>
    <span class="stat-num">3+</span>
    <span class="stat-label">年開發經驗</span>
  </div>
  <div>
    <span class="stat-num">24h</span>
    <span class="stat-label">回覆時效</span>
  </div>
</div>

---

<!-- paginate: true -->

<div class="section-label">About Me</div>

## 🙋 關於我

<div class="accent-line"></div>

<div class="highlight">
專注於打造 <strong>AI 驅動的商業應用</strong>，擅長 Python 後端、TypeScript 全端、自動化流程，已協助多間企業完成數位轉型與智能化系統。從需求分析到系統上線，提供端對端的完整解決方案。
</div>

<div class="grid2">
<div class="card">
<div class="sk-icon">🤖</div>
<h3>AI / LLM 專家</h3>
<p style="font-size:0.75em;color:#94a3b8;margin:0">RAG 知識庫、ChatBot、多模態 Agent、語音辨識整合</p>
</div>
<div class="card">
<div class="sk-icon">⚡</div>
<h3>全端開發能力</h3>
<p style="font-size:0.75em;color:#94a3b8;margin:0">Python + TypeScript，從後端 API 到前端 UI 一手包辦</p>
</div>
</div>

---

<div class="section-label">Core Skills</div>

## 🛠 技術棧一覽

<div class="accent-line"></div>

<div class="grid3">
<div class="card">
<span class="sk-icon">🤖</span>
<h3 style="font-size:0.9em">AI / LLM 應用</h3>
<div><span class="tag">OpenAI</span><span class="tag">LangChain</span><span class="tag">LangGraph</span><span class="tag">Whisper</span></div>
</div>
<div class="card">
<span class="sk-icon">⚡</span>
<h3 style="font-size:0.9em">後端開發</h3>
<div><span class="tag">Python</span><span class="tag">FastAPI</span><span class="tag">Node.js</span><span class="tag">PostgreSQL</span></div>
</div>
<div class="card">
<span class="sk-icon">🎨</span>
<h3 style="font-size:0.9em">前端開發</h3>
<div><span class="tag purple">TypeScript</span><span class="tag purple">React</span><span class="tag purple">Next.js</span><span class="tag purple">Vue</span></div>
</div>
<div class="card">
<span class="sk-icon">🔧</span>
<h3 style="font-size:0.9em">自動化 / 爬蟲</h3>
<div><span class="tag green">Selenium</span><span class="tag green">Playwright</span><span class="tag green">Scrapy</span></div>
</div>
<div class="card">
<span class="sk-icon">📊</span>
<h3 style="font-size:0.9em">資料分析 / ML</h3>
<div><span class="tag">Pandas</span><span class="tag">scikit-learn</span><span class="tag">Transformers</span></div>
</div>
<div class="card">
<span class="sk-icon">☁️</span>
<h3 style="font-size:0.9em">部署 / DevOps</h3>
<div><span class="tag green">Docker</span><span class="tag green">GitHub Actions</span><span class="tag green">GCP</span></div>
</div>
</div>

---

<div class="section-label">⭐ Featured Project</div>

## 🤖 企業 AI RAG 知識庫管理系統

<div class="accent-line"></div>

<div class="grid2">
<div>

<div class="proj-cat">AI · RAG · 企業應用</div>

### 解決的問題
員工找內部資料靠關鍵字搜尋，既慢又不準確。

### 我的解決方案
建立 AI 知識庫系統，讓員工用**自然語言**直接問問題，秒找答案並附上原文出處。

<div style="margin-top:16px">
<span class="tag">Python</span><span class="tag">TypeScript</span><span class="tag">RAG</span><span class="tag">LangChain</span><span class="tag">OpenAI</span><span class="tag purple">Chroma DB</span><span class="tag green">Docker</span>
</div>

</div>
<div class="card">

✅ **員工可上傳** PDF / Word / Excel<br/>
✅ **自動建立**向量索引<br/>
✅ **自然語言**精準查詢<br/>
✅ **附上來源**引用，杜絕 AI 幻覺<br/>
✅ **Docker** 容器化一鍵部署<br/><br/>

**技術棧：**
Python FastAPI × Next.js TypeScript × LangChain × OpenAI Embedding × Chroma DB × Docker

</div>
</div>

---

<div class="section-label">Portfolio</div>

## 💼 更多作品案例

<div class="accent-line"></div>

<div class="grid2">
<div class="card">
<div class="proj-cat">全端 · 企業系統</div>
<h3>🏢 企業 ERP 管理系統</h3>
<p style="font-size:0.75em;color:#94a3b8;margin:8px 0">訂單管理、庫存追蹤、財務報表、人員權限控管。即時 KPI 儀表板、多角色身份驗證。</p>
<div><span class="tag purple">TypeScript</span><span class="tag purple">React</span><span class="tag">PostgreSQL</span></div>
</div>
<div class="card">
<div class="proj-cat">自動化 · 電商</div>
<h3>🛒 Cyberbiz 電商自動化</h3>
<p style="font-size:0.75em;color:#94a3b8;margin:8px 0">商品爬取、庫存同步、自動打標籤、批量訂單處理。每日排程自動執行，大幅節省人工。</p>
<div><span class="tag">Python</span><span class="tag green">Selenium</span><span class="tag green">排程</span></div>
</div>
<div class="card">
<div class="proj-cat">AI · 語音辨識</div>
<h3>🎙️ 會議錄音逐字稿系統</h3>
<p style="font-size:0.75em;color:#94a3b8;margin:8px 0">上傳錄音檔自動產生多說話者逐字稿，時間戳記標注，可匯出 Word/PDF，支援中英文。</p>
<div><span class="tag">Python</span><span class="tag">Whisper</span><span class="tag">FastAPI</span></div>
</div>
<div class="card">
<div class="proj-cat">AI · 即時通訊</div>
<h3>🌐 即時翻譯聊天系統</h3>
<p style="font-size:0.75em;color:#94a3b8;margin:8px 0">WebSocket 多語言即時互譯，整合 GPT 翻譯引擎，支援繁中、英、日，可保留語氣語境。</p>
<div><span class="tag purple">TypeScript</span><span class="tag">WebSocket</span><span class="tag">OpenAI</span></div>
</div>
</div>

---

<div class="section-label">Portfolio</div>

## 📈 數據 · 金融 · ML 專案

<div class="accent-line"></div>

<div class="grid2">
<div class="card">
<div class="proj-cat">金融 · 數據分析</div>
<h3>📉 量化交易策略回測平台</h3>
<p style="font-size:0.78em;color:#94a3b8;margin:8px 0 12px">
策略參數設定、歷史數據回測、績效指標計算（總報酬率、夏普比率、最大回撤），搭配 K 線圖與買賣點可視化。
</p>
<div><span class="tag purple">TypeScript</span><span class="tag">Charts</span><span class="tag">金融數據</span></div>
</div>
<div class="card">
<div class="proj-cat">ML · NLP · 研究</div>
<h3>🧠 機器學習 & NLP 研究專案</h3>
<p style="font-size:0.78em;color:#94a3b8;margin:8px 0 12px">
中文文本分類、情感分析、NLP Pipeline。實作 LORA/QLORA 微調、Transformer 模型訓練，<strong style="color:#34d399">模型準確率達 94.3%</strong>。
</p>
<div><span class="tag">Python</span><span class="tag">Transformers</span><span class="tag">NLP</span><span class="tag green">94.3% acc</span></div>
</div>
</div>

<div class="highlight">
🛍️ <strong>電商賣家後台管理系統</strong> — 全端後台，商品管理、訂單追蹤、庫存監控、業績報表。即時資料更新、多帳號權限管理。
<span class="tag purple">TypeScript</span><span class="tag purple">React</span><span class="tag">Node.js</span>
</div>

---

<div class="section-label">Contact</div>

## 📬 歡迎洽談合作

<div class="accent-line"></div>

<div class="grid2">
<div>

<p style="color:#94a3b8;font-size:0.85em;line-height:1.9;margin-bottom:20px">
無論是 AI 應用開發、網站系統建置、<br/>電商自動化，還是資料分析專案，<br/>都歡迎與我聯繫。<br/><br/>
收到訊息後 <strong style="color:#38bdf8">24 小時內回覆</strong>，<br/>並提供 <strong style="color:#34d399">免費的需求評估</strong>。
</p>

<div class="contact-item">
  <span class="ci-icon">✉️</span>
  <div>
    <div class="ci-label">EMAIL</div>
    <div class="ci-val">wuchunwei0518@gmail.com</div>
  </div>
</div>
<div class="contact-item">
  <span class="ci-icon">💼</span>
  <div>
    <div class="ci-label">GITHUB</div>
    <div class="ci-val">github.com/Chunweiwu518</div>
  </div>
</div>
<div class="contact-item">
  <span class="ci-icon">🌏</span>
  <div>
    <div class="ci-label">服務地區</div>
    <div class="ci-val" style="color:#e2e8f0">台灣全端 · 遠端皆可</div>
  </div>
</div>

</div>
<div>

<div class="card" style="background:linear-gradient(135deg,rgba(56,189,248,0.1),rgba(129,140,248,0.1));border-color:rgba(56,189,248,0.2);text-align:center;padding:32px 24px">

### 🚀 為什麼選擇我？

<div style="text-align:left;font-size:0.78em;color:#cbd5e1;line-height:2;margin-top:12px">
✅ 端對端全案執行，不需要多個供應商<br/>
✅ AI / 全端 / 自動化三位一體<br/>
✅ 50+ 開源專案，技術實力有據可查<br/>
✅ 10+ 商業案例，了解企業真實痛點<br/>
✅ 快速交付，溝通直接有效率<br/>
</div>

</div>

</div>
</div>

---

<!-- paginate: false -->

<div style="text-align:center;display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%">

<div style="font-size:3em;margin-bottom:24px">🎯</div>

# 謝謝您的閱覽

<span class="role" style="font-size:1.1em">吳竣瑋 · CW Wu · 全端工程師 · AI 應用開發</span>

<div style="margin: 24px 0">
<span class="tag" style="font-size:0.75em;padding:8px 20px">✉️ wuchunwei0518@gmail.com</span>
&nbsp;
<span class="tag green" style="font-size:0.75em;padding:8px 20px">💼 github.com/Chunweiwu518</span>
</div>

<div class="badge">期待與您合作 🤝</div>

</div>
