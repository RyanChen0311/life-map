# 人生地圖 Life Map

互動式人生系統視覺化工具，展示各生活面向之間的相互影響關係。本專案由 AI 輔助創作。

## 線上展示

[https://RyanChen0311.github.io/life-map/](https://RyanChen0311.github.io/life-map/)

## 專案說明

人生地圖將十個核心生活面向建模為互聯圖中的節點。將滑鼠移至任一節點，即可高亮顯示其直接與間接影響路徑，並在下方面板中閱讀簡短說明。

**涵蓋面向**

| 節點 | 類別 |
|---|---|
| 正向思考 | 生活習慣 |
| 好習慣 | 生活習慣 |
| 社交生活 | 生活習慣 |
| 身心健康 | 核心系統 |
| 戶外生活 | 身心健康 |
| 心理健康 | 身心健康 |
| 知識成長 | 職涯發展 |
| 職涯發展 | 職涯發展 |
| 工作環境 | 職涯發展 |
| 財務基礎 | 財務 |

## 功能特色

- 互動式節點圖，滑鼠移入即高亮顯示影響路徑
- 區分直接與間接影響邊線
- 活躍節點動態發光效果
- 下方說明面板顯示節點詳細描述
- 響應式版面配置

## 技術棧

- 純 HTML / CSS / JavaScript（單一檔案，無需建置）
- Canvas API 繪製邊線
- [Tabler Icons](https://tabler-icons.io/) 節點圖示
- Google Fonts — Noto Serif TC / Noto Sans TC

## 使用方式

直接用瀏覽器開啟 `index.html`，或前往上方的 GitHub Pages 連結，無需安裝任何套件。

---

> 本專案由 [Claude](https://claude.ai)（Anthropic）AI 輔助設計與開發。
