# From Vibe Coding to Future Software

## 從 AI 寫程式，到交付真正能用的軟體

AI 可以協助研究需求、產生程式、撰寫測試，甚至執行部署。但從「做得出來」到「能在真實環境中運作」，仍然需要清楚的需求、工程方法，以及對結果負責的人。

這是一份面向學生、約一小時的 AI 軟體工程分享簡報。從 Vibe Coding 出發，串起軟體開發流程、AI Coding Agent 的工作方式，以及 FDE 與企業導入案例，說明如何與 AI 一起完成可驗證、可交付、可持續改善的軟體。

> **AI 改變軟體工程的運作方式；人對需求、品質與交付結果的確認責任，沒有改變。**

**[開始閱讀簡報](https://linkanwei.github.io/AI_Coding/ai_coding.html)** · **[全螢幕播放入口](https://linkanwei.github.io/AI_Coding/ai_coding.html?present=1)** · **[GitHub 專案](https://github.com/linkanwei/AI_Coding)**

## 這份簡報在談什麼？

| 主題 | 內容重點 |
| --- | --- |
| **1. 從 Vibe Coding 到人機協作** | 從自然語言產生程式，走向有規格、有審查、有驗證的 Human–Agent Engineering。 |
| **2. AI 時代的軟體工程** | 需求、規格、系統分析與設計、開發、Review、測試、部署及維運，各階段如何運用 AI，以及人需要確認什麼。 |
| **3. AI Coding Harness** | 理解模型之外的工具、規則、Skills 與檢查關卡，如何支撐 Agent 完成工作；認識 MCP 與 Skill 的分工。 |
| **4. FDE 實務經驗** | 如何帶領 Junior 從業務訪談、共同建模，走到前後台、資料庫、測試驗收與安裝上線。 |
| **5. 企業 AI Data Mart 導入案例** | 從規格到客戶上線，理解 AI 專案如何連結資料、系統與現場需求。 |
| **6. 用這份簡報看 AI 協作** | 以簡報本身的製作過程，分享在 Cursor、不同模型與 Claude Code 之間協作、調整與確認的經驗。 |

貫穿全課的開發流程：

**需求 → 規格 → 系統分析（SA）→ 系統設計（SD）→ 開發 → Review → Test → Deploy → 上線驗證 → PDCA**

AI 可以加速每個環節；工程團隊仍須確認需求是否被正確理解、設計是否合理，以及交付結果是否符合使用情境。

## 你可以帶走什麼？

- **把模糊想法變成可執行規格**：釐清角色、流程、業務規則、例外情境與驗收條件。
- **建立與 Coding Agent 的協作節奏**：先研究與規劃，再分段實作、審查與測試。
- **辨識「能跑」與「能交付」的差距**：從程式碼一路檢查到 Git 紀錄、部署、監控與使用者回饋。
- **理解 FDE 的工作方式**：連結業務現場與工程系統，從問題定義一路參與到上線結果。
- **累積可重用的工程經驗**：將每次修正轉成規格模板、Skills、測試與檢查規則。

## 適合誰閱讀？

- 想了解 AI 如何改變軟體開發的學生。
- 已經使用 AI 寫程式，希望進一步掌握完整交付流程的初階工程師。
- 希望用實務案例介紹 AI 軟體工程的教師、講者與團隊帶領者。

閱讀時不必先熟悉所有工具；可以先掌握整體流程，再回到各章節理解細節。

## 如何使用簡報

### 線上閱讀

直接開啟 **[網頁簡報](https://linkanwei.github.io/AI_Coding/ai_coding.html)**。

| 操作 | 功能 |
| --- | --- |
| 方向鍵、空白鍵 | 切換投影片 |
| `N` | 顯示／隱藏講者備註 |
| `F` | 全螢幕播放 |
| `T` | 切換白底、灰底、黑底主題 |

也可以透過網址指定起始位置或播放模式：

- [從第 12 頁開始](https://linkanwei.github.io/AI_Coding/ai_coding.html?slide=12)
- [直接進入播放模式](https://linkanwei.github.io/AI_Coding/ai_coding.html?present=1)

### 本機開啟與修改

下載本專案，保留原有檔案與圖片的相對路徑，再用瀏覽器開啟 [`ai_coding.html`](ai_coding.html)。簡報使用外部 CDN 載入樣式，建議在有網路連線的環境下開啟。

若要調整教材，可從 `ai_coding.html` 中的 `slidesData` 編輯投影片標題、內容與講者備註，再以瀏覽器檢查呈現結果。

## 參考資料與致謝

本簡報由講者自行編排，結合軟體工程觀點與實務經驗。以下資料作為概念、角色定義與教學討論的參考；本專案並非 Stanford CS146S 的官方教材或官方譯本。

| 參考資料 | 對應內容 |
| --- | --- |
| [Stanford CS146S: The Modern Software Developer](https://themodernsoftware.dev/) | AI 時代的軟體開發與工程方法。 |
| [Andrej Karpathy：Vibe Coding 原始貼文](https://x.com/karpathy/status/1886192184808149383) | Vibe Coding 概念；簡報提供貼文截圖與中譯供課堂對照。 |
| [Andrej Karpathy：一週年回顧與 Agentic Engineering](https://x.com/karpathy/status/2019137879310836075) | 從 Vibe Coding 到 Agentic Engineering 的討論。 |
| [The Modern Software AI Coding Agents Workshop](https://ford-proposal.themodernsoftware.dev/) | Research → Plan → Implement → Test 工作流程。 |
| [Palantir：A Day in the Life of a Forward Deployed Software Engineer](https://blog.palantir.com/a-day-in-the-life-of-a-palantir-forward-deployed-software-engineer-45ef2de257b1) | FDE 角色與工作方式。 |

## 授權與使用

本專案的**原創簡報文字、編排結構與自繪圖像**採用 [Creative Commons Attribution 4.0 International（CC BY 4.0）](https://creativecommons.org/licenses/by/4.0/) 授權。

歡迎分享、改作或用於教學。使用時請保留作者姓名、附上專案來源與授權連結，並註明是否修改。

**第三方內容不在上述授權範圍內**，包括 Karpathy 貼文截圖及所引用的原文；相關權利仍屬原權利人。Stanford 課程原文與教材亦不包含在本專案的 CC BY 4.0 授權中。本專案未收錄該課程投影片、作業或講義全文。
