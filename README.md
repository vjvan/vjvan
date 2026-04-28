# 允雷 (Van)

我不接 AI 諮詢，我交付會上線收訂單的系統。

過去半年用 Claude Code 一個人幫 5 家中小企業把人工流程改成 AI 系統：35 年水產加工的 LINE LIFF 補貨、高雄連鎖汽車美容的會員預約、31 年吊裝工程集團的 B2B 詢盤站、35 年雞肉供應商的 ERP 整合提案、4 店連鎖洗車的來客經營系統。

不是 demo，是 production。客戶下單、客戶收錢、客戶 LINE 收推播。

---

### 我在做的事

**988 廚房 B2B 補貨系統**｜35 年水產加工老字號的 LINE LIFF + n8n + Supabase 架構

凌晨 5 點人工打單變成客戶 LINE 自助下單，18 點截單後系統自動列印製單。webhook + outbox + 三層保險，跑了三週踩到 5 次靜默失敗，全部修完寫進 SOP。雙向客戶確認推播，客戶下完單 LINE 立刻收到品名規格金額，閉環。

**[transcribe-proposal](https://github.com/vjvan/transcribe-proposal)**｜會議錄音一鍵轉提案 PPTX

OpenAI Whisper + 結構化 prompt + python-pptx。客戶諮詢錄音丟進去，48 小時內出 proposal + battle card + domain brief 三件組。

**P2P AI Lab**｜Prompt to Pixel, the One-Person AI Video Pipeline

Premium 訂閱社群 (Skool, Founding Member US$49/月)。教專業創作者 / 代理商 / 顧問用 AI 建一人影片產線。不是初學者課程，11 個 Module、49 個單元，配套 ai-video-studio 示範專案 + Weavy.ai 節點工作流 + video-cut skill 實作。

**[vjvan-website](https://github.com/vjvan/vjvan-website)**｜個人品牌站

Next.js 16 + Tailwind 4 + MDX。AI 商業系統架構師的部落格與作品集。Editorial Issue 01 設計風格 (紙色 + 電氣藍 + Instrument Serif)。

---

### 我相信的幾件事

**AI 寫的 code 不算交付，能上線收錢的系統才算。** 一個人公司沒有後援團，每一行 code 都要對得起客戶的營收與聲譽。我把工作台拆成「實作席 Claude Code + 驗收席 OpenAI Codex CLI」雙層架構，用 tmux 四件套指令分離席位，避免同一個 AI 自己寫自己驗的盲點。

**B2B 系統真正的競爭力，是讓 60 歲阿姨也能下單。** 客戶群多是 50 到 70 歲的採購決策人，老花眼、不擅手機。字 17px 起、按鈕 52px 起、視覺標記優於文字、少決策。這條規則優先於任何技術優雅。

**台灣中小企業導入 AI 的 ROI，要拿小時數算，不是百分比。** 顧問公司投影片寫「效率提升 30%」沒人懂。改寫「凌晨 4 小時人工作業變成 0 小時」，客戶馬上知道值多少錢。

---

### 技術棧

**Frontend**: TypeScript, Next.js 16, React, Tailwind CSS 4, MDX

**Backend**: Node.js, Supabase (Postgres + Edge Functions + RLS), Cloudflare Workers

**AI / Automation**: Claude Code, OpenAI Codex CLI, n8n, Weavy.ai, OpenAI API, Anthropic API

**Infrastructure**: Vercel, Cloudflare, GitHub Actions, ngrok, Docker

---

### 找到我

[vjvan.com](https://vjvan.com) ｜
[Threads @vjvan_n](https://www.threads.com/@vjvan_n) ｜
[YouTube @允雷](https://www.youtube.com/@允雷) ｜
P2P AI Lab (招生中, US$49/月 Founding Member 鎖定前 100 位)
