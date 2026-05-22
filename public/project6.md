---
name: 幸運抽籤
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#464554'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#767586'
  outline-variant: '#c7c4d7'
  surface-tint: '#494bd6'
  primary: '#4648d4'
  on-primary: '#ffffff'
  primary-container: '#6063ee'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0c1ff'
  secondary: '#b4136d'
  on-secondary: '#ffffff'
  secondary-container: '#fd56a7'
  on-secondary-container: '#600037'
  tertiary: '#904900'
  on-tertiary: '#ffffff'
  tertiary-container: '#b55d00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#ffd9e4'
  secondary-fixed-dim: '#ffb0cd'
  on-secondary-fixed: '#3e0022'
  on-secondary-fixed-variant: '#8c0053'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703700'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-rng:
    fontFamily: Sora
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 90px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  element-gap: 16px
  section-margin: 40px
  touch-target: 48px
---

## 品牌與風格

此設計系統基於**高對比極簡主義**建立。它優先考慮「抽籤時刻」——用戶期待的頂峰——通過去除不必要的界面裝飾，完全專注於數字輸出和操作。

美學風格專業且充滿活力，利用廣闊的留白空間讓鮮豔的主要強調色更具影響力。情感目標是喚起公平、清晰和興奮感。它避免傳統賭博應用的雜亂外觀，採用「工具優先」的方法，感覺高級且可靠。

## 色彩

調色板使用精緻的**靛藍色**作為主要動作和品牌識別的驅動力。**粉紅/玫瑰紅**的次要顏色保留用於裝飾性強調或次要互動狀態，以保持高能量氛圍。

- **主要色 (靛藍):** 用於主要的「生成」或「抽籤」按鈕和活動選擇狀態。
- **次要色 (玫瑰):** 謹慎用於高亮、慶祝動畫或「新」標籤。
- **中性色:** 從近白色背景開始的冷灰色範圍，確保界面感覺呼吸。
- **成功色 (翡翠):** 專門用於「獲勝者」狀態或最終結果，提供即時正面強化。

## 字體

字體系統依賴**Sora**的幾何、現代和高影響力個性。它用於所有「結果」數字和主要標題，確保抽籤期間的最大可讀性。

**Inter**為設定、標籤和次要資訊提供功能性對比，提供不會與主要資料競爭的中性和系統感。對於移動版面，如果生成的數字超過四位數，`display-rng` 大小應縮放到 `56px` 以防止容器溢出。

## 佈局與間距

此設計系統使用**8px 基礎網格**，專注於移動工具典型的垂直堆疊佈局。

- **焦點區域:** 螢幕中央三分之一保留給 RNG 結果，使用最大留白吸引視線。
- **觸控目標:** 所有互動元素（輸入、按鈕、切換）必須保持最小 48px 高度以確保可訪問性。
- **安全區域:** 所有視圖應用標準 24px 水平邊距，防止內容擁擠移動顯示邊緣。
- **對齊方式:** 結果螢幕偏好中央對齊，設定和歷史列表使用左對齊以幫助掃描。

## 高度與深度

通過**環境陰影**和細微色調分層建立層次結構。

- **表面層級 (0dp):** 主要應用背景 (#F9FAFB)。
- **提升層級 (1dp):** 卡片和列表項目使用細微 1px 邊框 (#E2E8F0) 且無陰影以保持乾淨。
- **互動層級 (2dp):** 主要按鈕使用柔軟、著色陰影（靛藍色 20% 不透明度，12px 模糊，4px Y 偏移）看起來「抬起」和觸感。
- **覆蓋層級 (3dp):** 模態框和底部工作表使用背景模糊 (10px) 在專注用戶注意力於抽籤設定的同時保持上下文。

## 形狀

設計系統採用**圓角（值 2）**幾何。這轉化為較小組件如輸入欄位和列表項目的基礎半徑 **8px (0.5rem)**，擴展到主要容器和結果卡片的 **16px (1rem)**。

這種圓角級別軟化了數字生成器的技術性質，讓應用感覺更平易近人，更像現代生活方式工具而非冷靜的實用工具。完整藥丸形狀專門保留給「狀態」標籤（例如「歷史」、「設定」）。

## 組件

### 按鈕
- **主要動作:** 大型、全寬度按鈕，16px 圓角。使用主要靛藍色配白色文字。高對比和觸感。
- **次要/幽靈:** 用於「清除」或「重置」動作。透明背景配 1px 邊框。

### 輸入欄位
- **數字步進器:** 大型、居中文字輸入用於「最小」和「最大」值，兩側配大型 + 和 - 圖標便於單手調整。
- **切換:** 使用主要顏色表示「開」狀態；高對比軌道表示「關」狀態。

### 結果卡片
- 抽籤後出現的獨特容器。應具有 `display-rng` 字體。使用細微進入動畫（輕微放大）強調「揭示」。

### 歷史列表
- 乾淨的水平行，使用 `body-md` 文字。每行包含時間戳記和生成結果。使用交替淺灰色背景提高可掃描性。

### 標籤/徽章
- 用於過濾（例如「最近 10 個」、「全部時間」）。小型、圓形完整形狀配 `label-bold` 文字。