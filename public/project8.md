---
name: 貨幣轉換
colors:
  surface: '#FFFFFF'
  surface-dim: '#E6E6E6'
  surface-bright: '#FFFFFF'
  surface-container-lowest: '#FFFFFF'
  surface-container-low: '#F5F5F5'
  surface-container: '#EEEEEE'
  surface-container-high: '#E8E8E8'
  surface-container-highest: '#E0E0E0'
  on-surface: '#1A1A1A'
  on-surface-variant: '#666666'
  inverse-surface: '#2C2C2C'
  inverse-on-surface: '#F5F5F5'
  outline: '#CCCCCC'
  outline-variant: '#E0E0E0'
  surface-tint: '#0066CC'
  primary: '#0066CC'
  on-primary: '#FFFFFF'
  primary-container: '#E6F0FF'
  on-primary-container: '#004499'
  inverse-primary: '#80B3FF'
  secondary: '#00B894'
  on-secondary: '#FFFFFF'
  secondary-container: '#E6FFF9'
  on-secondary-container: '#008B75'
  tertiary: '#FF6B6B'
  on-tertiary: '#FFFFFF'
  tertiary-container: '#FFE6E6'
  on-tertiary-container: '#CC4444'
  error: '#DC2626'
  on-error: '#FFFFFF'
  error-container: '#FEE2E2'
  on-error-container: '#991B1B'
  primary-fixed: '#E6F0FF'
  primary-fixed-dim: '#80B3FF'
  on-primary-fixed: '#003366'
  on-primary-fixed-variant: '#0055AA'
  secondary-fixed: '#E6FFF9'
  secondary-fixed-dim: '#80FFD9'
  on-secondary-fixed: '#004D3D'
  on-secondary-fixed-variant: '#008B75'
  tertiary-fixed: '#FFE6E6'
  tertiary-fixed-dim: '#FFB3B3'
  on-tertiary-fixed: '#662222'
  on-tertiary-variant: '#CC4444'
  background: '#FFFFFF'
  on-background: '#1A1A1A'
  surface-variant: '#F5F5F5'
typography:
  display-lg:
    fontFamily: Noto Sans TC
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Sans TC
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Noto Sans TC
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Noto Sans TC
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-md:
    fontFamily: Noto Sans TC
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  margin-mobile: 20px
  margin-desktop: 64px
  gutter: 16px
  section-gap: 48px
---

## 品牌與風格
此設計系統以「即時精準」為核心概念。它採用**現代極簡主義**美學，融合**卡片式設計**以創造清晰的視覺層次。目標受眾為需要快速、準確貨幣轉換的使用者，介面營造專業、可靠且易於使用的感覺。

視覺語言在清晰的資訊呈現與直觀的操作流程之間取得平衡，確保使用者在任何情境下都能快速完成轉換操作。

## 色彩
調色板建立在「清新明亮」基礎上。
- **主色**：品牌藍（#0066CC）用於主要操作按鈕和重要資訊，傳達專業與信任感。
- **次要色**：成功綠（#00B894）用於轉換成功提示和正向回饋。
- **強調色**：警示紅（#FF6B6B）用於錯誤提示和警告訊息。
- **中性色**：淺灰色背景（#F5F5F5）和深灰色文字（#1A1A1A）確保高對比度與可讀性。

## 排版
排版以清晰易讀為首要原則。我們使用 **Noto Sans TC** 字體，確保繁體中文顯示效果最佳。
- **數字顯示**：使用 `display-lg` 配合緊湊字距，讓金額數字清晰可見。
- **層次**：使用 `label-md` 標示貨幣代碼和次要資訊，區別於主要內容。
- **字重**：主要資訊使用粗體（600-700），次要資訊使用常規（400），建立清晰視覺層次。

## 佈局與間距
佈局遵循**移動優先**哲學，確保在小螢幕上也能流暢操作。
- **邊距**：適當的邊距（手機 20px）確保內容不會緊貼螢幕邊緣。
- **留白**：在輸入區域與結果顯示之間使用充足的 `section-gap`，強調轉換結果的重要性。
- **對齊**：數字右對齊以符合使用者習慣，文字資訊左對齊以確保可掃描性。

## 高度與深度
深度通過**卡片式設計**和微妙的陰影傳達：
- **表面 0**：主背景（#FFFFFF）。
- **表面 1（輸入卡片）**：淺灰色背景（#F5F5F5）搭配細微陰影。
- **表面 2（結果卡片）**：使用品牌藍背景（#E6F0FF）突出顯示轉換結果。
- **陰影**：使用柔和陰影（模糊半徑 8px、低透明度 15%）創造層次感。

## 形狀
應用**圓角**設計以柔化介面，提升現代感。
- **小元素**：輸入框和小按鈕使用 0.5rem 半徑。
- **大元素**：主要卡片和結果區域使用 `rounded-lg`（1rem）或 `rounded-xl`（1.5rem）。
- **互動狀態**：按鈕按下時輕微縮放，增加互動回饋。

## 組件
- **輸入框**：大尺寸數字輸入框，支援自動格式化與貨幣符號顯示。
- **貨幣選擇器**：下拉選單顯示貨幣代碼、國旗和名稱，提供清晰的視覺辨識。
- **轉換按鈕**：主要按鈕使用品牌藍背景，次要按鈕使用幽靈風格。
- **結果卡片**：使用品牌藍背景突出顯示轉換結果，包含匯率資訊。
- **歷史記錄**：列表形式顯示最近的轉換記錄，支援快速重複使用。
- **切換器**：貨幣對調切換按鈕，使用圓形圖示，點擊時旋轉動畫。
