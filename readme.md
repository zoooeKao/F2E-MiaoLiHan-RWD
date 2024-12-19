# F2E-MiaoLiHan-RWD

![Responsive Design](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-brightgreen)
![CSS](https://img.shields.io/badge/CSS-SCSS-blue)
![BEM](https://img.shields.io/badge/CSS%20Methodology-BEM%20%7C%20SMACSS-orange)

## 專案介紹

此專案是一個 **響應式網頁設計切版練習** (RWD)，參考 [Figma 設計稿](https://www.figma.com/design/DCnuTZQ00D5VHiDkBLhxQ3/2023-The-F2E-%E7%AB%8B%E5%A7%94%E7%AB%B6%E9%81%B8%E5%AE%98%E7%B6%B2?node-id=139-170&p=f&t=UN0d9tmpuacnb9l1-0)，包含手機版、平板版與桌機版。

CSS 結構設計參考 **BEM 方法論** 和 **SMACSS 方法論**，保持樣式的模組化和可維護性。

政策議題區塊手刻網格系統。

## 使用技術

- HTML5
- SCSS

## 專案結構

```plaintext
F2E-LAYOUT/
├── .vscode/             # VSCode 設定檔
├── assets/              # 靜態資源 (圖片、字型等)
├── style/               # SCSS 樣式檔案
│   ├── _base.scss       # 基礎樣式
│   ├── _layout.scss     # 佈局樣式
│   ├── _module.scss     # 模組樣式
│   ├── _reset.scss      # 樣式重置
│   ├── _variable.scss   # SCSS 變數
│   ├── style.css        # 編譯後的 CSS 檔案
│   ├── style.css.map    # CSS 對應的 Source Map
│   └── style.scss       # SCSS 主入口
├── index.html           # 頁面 HTML 檔案
└── README.md            # 專案說明文件
```

## CSS 方法論

此專案中的 SCSS 構建基於以下方法論：

- BEM（Block Element Modifier）方法論 <br>
  以模組化的方式命名 CSS 類。 <br>
  範例：

  ```code
    .block {
      &__element {
        &--modifier {
          color: red;
        }
      }
    }
  ```

- SMACSS（Scalable and Modular Architecture for CSS）方法論 <br>
  將樣式分為 Base、Layout、Modules、State 和 Theme 五個類型，此練習參考 Base、Layout、Modules。 <br>
