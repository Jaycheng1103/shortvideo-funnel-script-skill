# 短影音漏斗腳本發想 Skill

給賣東西的老闆用的短影音腳本發想 Skill。照五個步驟走：收資料 → 個人品牌八個問題訪談 → 照銷售漏斗 28 種格式各出一個題目 → 挑題 → 用「Hook → 證據 → 內容」寫成可拍的腳本。

支援 ChatGPT Codex、Claude Code 等能讀 Skill 的 AI Agent。

## 安裝

在你的工作資料夾執行：

```sh
npx skills add Jaycheng1103/shortvideo-funnel-script-skill
```

安裝器會問你要裝到哪一個 Agent，選 Codex（或你用的那一個）。

## 開始使用

打開 Codex，貼上：

> 請用 shortvideo-funnel-script 幫我發想短影音。我賣的是＿＿，主要客人是＿＿。先問我問題，一次問一題。

AI 會先問你產品與客人，接著做八個問題的訪談，然後給你 28 個題目。挑好題目後，它會一支一支幫你寫腳本。

## 內容

| 檔案 | 用途 |
|---|---|
| `skills/shortvideo-funnel-script/SKILL.md` | 五個步驟的流程與規則 |
| `references/八個問題.md` | 個人品牌訪談題目 |
| `references/28種格式.md` | TOFU／MOFU／BOFU 28 種格式、怎麼排、示意題目 |
| `references/腳本結構.md` | 開頭三句話、Super Hook 三種寫法、研究型的資料調查、結尾怎麼收 |
| `references/輸出模板.md` | 品牌答案表、題目清單、腳本的格式 |

## 出處

- 28 種格式的分類整理自 Logan Forsyth 的 Content funnel examples。
- 開頭三句話與 Super Hook 的結構整理自 Chris Chung（@iamchrischung）的短影音。
- 八個問題由傑少（無界聯盟）整理，部分改寫自 Dan Koe 談個人品牌的問題。
- 中文說明、排法與示意例子是無界聯盟整理；示意例子都是虛構的。

## 注意

- AI 只用你給的真實資料，沒講過的經歷和數字會標「待補」，不會替你編。
- 產出是腳本草稿，不保證流量或成交。拍前請念一遍，改成你自己會說的話。
