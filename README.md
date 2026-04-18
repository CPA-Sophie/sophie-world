# Sophie's World — Personal Webpage

> 智慧決策分析系統實作 · Web Design Assignment · 2026

**網站入口：** `index.html`
**GitHub Pages：** [cpa-sophie.github.io/sophie-world](https://cpa-sophie.github.io/sophie-world/)
**GitHub：** [CPA-Sophie](https://github.com/CPA-Sophie)

---

## Changelog

### 2026-04-19

- `sophie.html` → 改名為 `index.html`，成為 GitHub Pages 根網址主頁
- 移除舊版 `index.html`（舊個人頁面）
- About 段落：新增 **Hometown 區塊**（台西，雲林 → 世界 → AI 敘事起點）
- About 段落：還原出生地 `born in Taixi, Yunlin, Taiwan`
- 旅行卡片：`台灣 Taiwan · 故鄉 Home` → 移除「故鄉」，保留 `Home`
- 興趣卡片：新增 🍷 **葡萄酒 Wine**
- About 自介文字更新：
  - 中文：「天生好奇，喜歡學習新事物，也喜歡走步道——」→「對世界充滿好奇，熱愛學習新事物，喜歡走在步道上，」
  - 英文：`walking trails — experiencing every place on foot` → `exploring trails—experiencing each place step by step`
- 地圖（SVG）：新增後因效果不佳移除

---

## 頁面結構

| 檔案 | 說明 |
|------|------|
| `index.html` | 個人主頁（旅行、興趣、自我介紹）· GitHub Pages 根網址 |
| `ai-program.html` | AI Program 學習日誌（Summary + 12 章日誌） |

---

## Sophie · 個人資料

| 項目 | 內容 |
|------|------|
| 出生地 | 雲林縣台西鄉 · Taixi, Yunlin, Taiwan |
| 現居 | 新北市 · New Taipei |
| 職業 | 會計師 · CPA |
| 學程 | AI Program Student |
| 星座 | 雙子座 ♊ Gemini |
| 興趣 | 旅行、咖啡、閱讀、美食、音樂、瑜珈、葡萄酒、AI |
| 名字由來 | 《蘇菲的世界》— 開始思考哲學、存在的意義、我是誰 |
| 最愛的書 | 《小王子》The Little Prince |

---

## 旅行足跡

### 台灣（故鄉 · 最大卡）
New Taipei · Taichung · Tainan · Kaohsiung · Yilan · Taitung · Keelung · Yunlin · Xitou

### ★ Favourite — 挪威 Norway
Oslo · Bergen · Flåm · God's Valley

### ★ Favourite — 英國 UK（第二個故鄉）
London · Cambridge · Second Home

### 日本 Japan
Tokyo · Nagoya · Kyoto · Kyushu · Fukuoka · Karuizawa · Hokkaido · Okinawa

### 韓國 South Korea
Seoul

### 瑞典 Sweden
Stockholm

### 義大利 Italy
Venice · Rome · Florence · Milan · Sangina · Sardinia

### 荷蘭 Netherlands
Amsterdam · Borden

### 西班牙 Spain
Madrid · Barcelona · Gaudí

---

## 興趣卡片

| 興趣 | 說明 |
|------|------|
| ✈️ 旅行 Travel | 探索不同文化與城市 |
| ☕ 咖啡 Coffee | 在各城市咖啡廳感受氛圍 |
| 📚 閱讀 Reading | 旅途中的書本陪伴 |
| 🍜 美食 Food | 探索當地美食 |
| 🎵 音樂 Music | YouTube 嵌入播放清單 |
| 🧘 瑜珈 Yoga | 忙碌生活中的呼吸與空間 |
| 🤖 AI 學習 | 連結至 `ai-program.html` |

---

## AI Program 頁面結構

- **Summary Block**（深色背景）：6 段學習總結
- **Learning Journal**：12 章，分 4 幕

| Act | 章節 | 主軸 |
|-----|------|------|
| Act I · Beginning | 1–3 | 起點、陌生、迷茫 |
| Act II · Struggle | 4–7 | 壓縮、疲憊、孤獨摸索 |
| Act III · Turning Point | 8–9 | 對齊、看見意義 |
| Act IV · Now | 10–12 | 反省、感恩、期待 |

---

## 技術架構

- 純 HTML5 / CSS3 / JavaScript，無框架
- Google Fonts：Playfair Display · Noto Serif TC · DM Sans
- YouTube iframe 嵌入（音樂卡片）
- Intersection Observer scroll reveal 動畫
- RWD 響應式設計（768px 斷點）
- 色彩系統：Cream / Ink / Terracotta / Sage / Brown / Gold
