---
name: roc-aesthetic
description: Generate authentic ROC-era Taiwanese「華國美學」UIUX - dense, patched, slightly ugly legacy web aesthetics with chaotic spacing, old portal energy, and “能用就好” sincerity.
---

# ROC Aesthetic

## 使用時機

當使用者要求生成、修改、評審或描述前端介面，且語境涉及下列任一方向時，使用本 skill：

- 華國美學、台灣官僚美學、中華民國視覺語言。
- 舊式入口網站、公部門資訊頁、公告系統、低預算宣導頁。
- 想要「老、密、修修補補、仍可操作」的 UI。
- 需要避免現代 SaaS、Apple、Stripe、Linear、Vercel 風格。

## 必讀專案規則

若這些檔案存在於目前 workspace，開始設計或修改 UI 前先讀取：

1. `SYSTEM_PROMPT.md`
2. `rules/copywriting.md`，只要會產生、翻譯或改寫 UI 文案就必讀。
3. 與任務相關的 `rules/*.md`，例如 spacing、typography、tables、colors、banners、buttons、layout。
4. `prompts/style.md` 作為單一風格 brief，依實際產品情境調整，不要拆成多個乾淨 preset。

## 核心姿態

- 資訊密集優先於留白。
- 表格優先於卡片，行政格線、框線、灰底、欄位結構都應被優先考慮。
- 允許區塊之間像不同年代、不同外包廠商補上去的：padding、border、shadow、字重可以不完全一致。
- 允許 1-2px 的不完美對齊、奇怪 gutter、略不均勻的邊框，但不可破壞可用性。
- 介面應該糙但能用，不是壞掉、不是反串迷因。

## 視覺方向

優先使用：

- ROC blue、飽和紅、警示黃、銀灰漸層、青色連結、金銅色點綴。
- 厚框線、inset shadow、浮雕或 glossy 按鈕、分區標頭、公告條、跑馬燈式 ticker。
- 多欄、側欄、巢狀框架、資料表、附件下載區、相關連結區。
- MingLiU、DFKai-SB、Microsoft JhengHei、Arial、Tahoma 等混合字體堆疊。
- WordArt 感標題、微妙拉伸、skew、重疊陰影、雷射漸層；只在 banner 或重要公告適用。

## 文案規範

文案要真誠、正式、宣導感強，像維運多年的公共資訊系統：

- 「登入」可寫成「會員身分驗證登入系統」。
- 「最新消息」可寫成「最新公告資訊瀏覽專區」。
- 「下載」可寫成「相關附件下載區」。
- 偏好「敬請詳閱」、「為維護您的相關權益」、「誠摯為您服務」、「提升服務品質」等官腔句式。
- 可重複提醒、重複分類、重複標題，營造害怕資訊不足的感覺。

不要寫成嘲諷、復古迷因或網路梗。目標是真誠的官僚系統，不是 parody。

## 禁止方向

除非使用者明確要求，預設拒絕：

- Vercel、Stripe、Linear、Apple 式極簡或精品感。
- 大量留白、三張 feature card、完美 8px spacing scale。
- 現代 startup landing page 套路。
- 過度一致、過度乾淨、過度 premium 的設計系統。

當不確定時，選擇「醜一點但真誠的官僚維運系統」，不要選「漂亮但現代的新創介面」。
