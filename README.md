# 產業研究檔案室 · 投資學習筆記

以視覺化方式記錄台灣科技供應鏈的產業研究筆記。

🔗 https://350016z.github.io/investment-notes/

## 目前收錄

### 產業筆記

| 檔案 | 主題 |
|------|------|
| [矽光子 × CPO 圖鑑](notes/silicon-photonics-cpo.html) | 光通訊、矽光子、共封裝光學 |
| [CoPoS 與玻璃基板](notes/glass-substrate.html) | 先進封裝、玻璃基板 |
| [台灣被動元件產業全景圖](notes/passive-components.html) | MLCC、電阻、電感 |

### 公司專題

| 檔案 | 關聯產業 |
|------|----------|
| [康寧 GLW](notes/companies/corning.html) | 矽光子 × CPO |

## 結構

```
├── index.html                 # 首頁(檔案室入口)
├── notes/                     # 產業筆記
│   ├── *.html                 # 各篇產業筆記
│   └── companies/             # 公司專題(掛在對應產業筆記下)
│       └── *.html
└── README.md
```

## 新增方式

**新增一份產業筆記**
1. HTML 放進 `notes/`(建議英文檔名)
2. 編輯 `index.html`,複製一個 `<section class="dossier-group">` 區塊並修改內容

**新增一份公司專題**
1. HTML 放進 `notes/companies/`
2. 在 `index.html` 對應產業筆記的 `dossier-group` 內,加一個 `<a class="sat-pill">` 連結
3. 同一家公司可同時掛在多份產業筆記下

## 聲明

本站僅為個人學習筆記,內容整理自公開資訊,不構成任何投資建議。
