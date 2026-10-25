---
name: sylvia-novel
aliases:
  - hsinyuchi-vocab-novel
  - sylvia-vocab-novel
version: 2.9.0
author: hsinyuchi (Sylvia 紀老師)
license: CC BY-NC-SA 4.0
description: >-
  打造專屬「高中職情境單字小說互動閱讀器」(Sylvia's Vocab Novel Pro) 與「小說總覽」(Sylvia's Novels Hub)。
  由 hsinyuchi (Sylvia 紀老師) 為臺灣高中職（普高/技高）學生量身打造之沉浸式單字學習宇宙。
  對齊 108 課綱核心素養、大考中心 7000 單字 Level 2~4、CEFR A2~B1 分級閱讀。
  具備【唯一黃金母板規範：100% 以 B3L2 重生逆襲篇為基準代碼，後續課次僅更換色系與文本】、
  【短段落呼吸感與台詞獨立成段鐵律：嚴禁大段塞字，重要對話必須獨立成段，排版輕盈無壓力】、
  【當紅影視多元流派庫：涵蓋 Netflix 黑白大廚、K-POP 韓團選秀、韓劇復仇、仙俠陸劇、特工電影、劇本殺、戀綜等流行文化題材】、
  【生動角色對話鐵律：每篇小說必須包含 2~4 句高衝突角色對話，嚴禁純旁白式乾癟敘事】、
  【純淨零個人名規範：首頁開頭嚴禁「新豐高中研發」、頁尾嚴禁「研發策劃人名」，確保課堂與研習純粹推廣】、
  【Novels Hub 總部三欄對齊規範：總部比照 Songs Hub，一排呈現 3 個 (3-Column Grid)】、
  【Portal 標準小卡靠左規範：Portal 內 Novels Hub 為單一標準小卡，靠左放置，右邊留白】、
  【教師課本單字輸入 ➔ 自動提案 5 大多元流派爽文（600-800字）供教師挑選】標準工作流。
  具備【跨 Agent 零歧義標準：原生純前端無依賴，通殺 Antigravity、Codex、Claude Code、ChatGPT】、
  【去 AI 味與真人作家筆觸：嚴禁說教翻譯腔，深度融入爽點套路與高頻句型】、
  【嚴格字數標準：中文故事本體嚴格 600~800 字（約 5~6 分鐘閱讀），英文純英改寫 400~550 字】、
  【雙重視圖架構：導讀焦點單字預覽頁 ＋ 沉浸式閱讀內文頁】、
  【三階鷹架切換：Step 1 學習版（括號提示）、Step 2 複習版（雙向翻牌遮罩：遮中文測字義 / 遮英文考拼字）、Step 3 全英版（純美語自然語音串流 / 高音質 MP3 外掛）】、
  【零滑動便當盒單字卡：音標、釋義、例句直觀一屏收納】、
  【片語底線淨化規範：杜絕 in_addition_to 發音與顯示報錯】、
  【極致載具防護：雙層吸頂導航列、單字卡五重順滑收合、手機「上一步」popstate 歷史攔截】、
  【命運分水嶺：三分支結局 A/B/C 點擊即刻彩帶爆破 ＋ 英文名言點睛】、
  【純淨版權聲明：頁底 CC BY-NC-SA 4.0 國際授權與大考課綱指示性合理使用免責聲明】、
  【一課一主題色 (如 Songs Hub 體系)】與 Cloudflare Pages 部署規範。
---

# 📚 高中職情境單字小說互動閱讀器 (Sylvia's Vocab Novel Pro / Novels Hub) v2.9.0

> 🏆 **黃金母板唯一鐵律 (Golden Master Law)**：  
> **所有課次（B3L2、B3L4、B4L1 等）必須 100% 嚴格以 B3L2 重生逆襲篇 (`b3l2/index.html`) 作為實體「黃金母板」！**  
> 嚴禁任何 Agent 自由發揮重寫版型、拆分組件或改動 DOM 結構。任何新課次**僅允許置換主題色系、單字庫 (vocabDb)、故事 tokens (storyParagraphs) 與結局 (endingsData)**！

---

## ⚡ 核心原則一：文字去 AI 味 ＆ 生動角色對話鐵律 (Dialogue Mandate)

> ⚠️ **最高禁令**：**嚴禁純旁白式乾癟敘事！嚴禁 AI 說教味與英翻中翻譯腔！**  
> 為了讓故事栩栩如生、讓高中生欲罷不能，**每篇小說必須包含 2 ~ 4 句高戲劇張力、帶有強烈衝突的真人角色對話**：
> 1. **反派的傲慢叫囂或挑釁**（例如：「這種路邊攤的大鍋菜根本不配稱為料理！」、「你連報名的資格都沒有！」）。
> 2. **主角從容霸氣的打臉回懟**（例如：「在真正的火候面前，你的松露不過是掩飾心虛的遮羞布！」、「想要別人認真看待你，就為每根線條付出心力！」）。
> 3. **第三方/評審/群眾的震撼驚呼**（例如：「我的上帝……這碗湯徹底打開了我的雙眼！這不是料理，這是靈魂！」、「黑湯匙加油！狠狠打天龍人的臉！」）。

---

## 📱 核心原則二：短段落呼吸感 ＆ 台詞獨立成段排版 (Short Paragraph & Standalone Dialogue)

> 💡 **網路微小說排版鐵律（告別大坨字塊）**：  
> 網路世代與行動載具的閱讀習慣講求「乾淨明快、節奏感強」。**嚴禁將 150 ~ 200 字硬塞在同一個大段落中**！
> 1. **短段落原則**：每個敘事段落以 **1 ~ 3 句話** 為限，交代一個動作、反應或場景轉換即可斷段。全篇切分為 **10 ~ 19 個段落**。
> 2. **台詞獨立成段**：凡是角色的核心對白（引號「……」之言），**一律獨立成為單獨一段**！前後不拖泥帶水，營造強大的戲劇重擊感。
> 3. **雙語段落 1:1 對齊**：英文文本 (`en_tokens`) 必須與中文文本 (`zh_tokens`) 的段落切分保持 100% 嚴格對應，確保 Step 1、Step 2 與 Step 3 切換時毫秒對齊。

---

## 🏛️ 核心原則三：Novels Hub 總部三欄排版 (3-Column Grid)

> 💡 **比照 Songs Hub 規格（一排 3 個）**：  
> 點擊進入 Novels Hub 總部（`08_Vocab_Novel/index.html`）後：
> 1. **版面容器**：最大寬度設定為 `max-width: 1140px`。
> 2. **卡片列表**：在大螢幕上一排呈現 **3 個卡片**（`@media (min-width: 1024px) { grid-template-columns: repeat(3, 1fr); gap: 24px; }`），與 Songs Hub 視覺完全一致！
> 3. **未滿課次處理**：尚未上線的課次以質感的「STORY 03 ｜ 即將解鎖」虛線卡補齊，維持一排三張的均衡對稱。

---

## 🖼️ 核心原則四：Portal 標準小卡靠左規範 (Portal Harmonization)

在教師總部 Portal (`00_Portal/index.html`) 中：
1. **標準精簡小卡**：Novels Hub、Four-Stage Learning Hub、AI Agent Workflow Hub 均嚴格採用與 `One Teaching Hub` 相同的標準小卡尺寸 (`md:col-span-6`)。
2. **拿掉多餘亮點格**：嚴禁在 Portal 卡片內部塞入龐大的 2x2 亮點格或子故事卡片，保持首頁純淨統一。
3. **左右各一與 Novels Hub 靠左留白**：
   - Four-Stage Learning Hub 與 AI Agent Workflow Hub 左右各一（佔滿一行 12 欄）。
   - Novels Hub 在下一行**靠左放置 (`md:col-span-6`)，右側 6 欄維持空白**（搭配隱藏 spacer），不與其他卡片硬擠，維持從容呼吸感。

---

## 🛡️ 純淨品牌與去個人名規範 (Zero-Personal-Branding Mandate)

1. **首頁開頭與閱讀器頂部 (Intro Card)**：
   - 徽章統一為純粹簡約的 **`單字小說`**。
   - 標題與簡介下方 `.intro-meta` 僅保留客觀數據：
     ```html
     <div class="intro-meta">
       <span>📚 25 個核心詞彙</span>
       <span>⏱ 建議閱讀 5 分鐘</span>
     </div>
     ```
   - ❌ **嚴禁出現**：`✨ 新豐高中 · 紀欣妤老師 (Sylvia) 研發` 或任何學校個人字樣！

2. **頁尾結尾 (Footer)**：
   - ❌ **嚴禁出現**：`研發策劃：國立新豐高級中學 紀欣妤老師 (Sylvia Chi)` 等人名標籤！
   - ✅ **統一採用純淨版權宣告與 CC BY-NC-SA 4.0 國際授權**：
     ```html
     <footer class="app-footer">
       <div class="app-footer-brand">Sylvia's Novels Hub · 臺灣高中職英語互動教學專案</div>
       <div class="app-footer-disclaimer">
         © 2026 Sylvia's Novels Hub. All Rights Reserved.<br>
         本站故事文本與互動程式碼採 <strong>CC BY-NC-SA 4.0</strong> 國際授權條款釋出，僅限教育課堂與非商業研習推廣使用。<br>
         單字釋義與大考核心詞彙版權歸原課綱與原出版機構所有。
       </div>
     </footer>
     ```
