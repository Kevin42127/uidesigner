---
name: 模擬搜尋引擎
colors:
  surface: '#FFFFFF'
  surface-dim: '#F0F0F0'
  surface-bright: '#FFFFFF'
  surface-container-lowest: '#FFFFFF'
  surface-container-low: '#F8F9FA'
  surface-container: '#F1F3F4'
  surface-container-high: '#E8EAED'
  surface-container-highest: '#E0E2E5'
  on-surface: '#202124'
  on-surface-variant: '#5F6368'
  inverse-surface: '#3C4043'
  inverse-on-surface: '#F8F9FA'
  outline: '#DADCE0'
  outline-variant: '#E0E2E5'
  surface-tint: '#1A73E8'
  primary: '#1A73E8'
  on-primary: '#FFFFFF'
  primary-container: '#E8F0FE'
  on-primary-container: '#0D47A1'
  inverse-primary: '#8AB4F8'
  secondary: '#5F6368'
  on-secondary: '#FFFFFF'
  secondary-container: '#F1F3F4'
  on-secondary-container: '#3C4043'
  tertiary: '#EA4335'
  on-tertiary: '#FFFFFF'
  tertiary-container: '#FCE8E6'
  on-tertiary-container: '#C5221F'
  error: '#EA4335'
  on-error: '#FFFFFF'
  error-container: '#FCE8E6'
  on-error-container: '#C5221F'
  primary-fixed: '#E8F0FE'
  primary-fixed-dim: '#8AB4F8'
  on-primary-fixed: '#0D47A1'
  on-primary-fixed-variant: '#1967D2'
  secondary-fixed: '#F1F3F4'
  secondary-fixed-dim: '#DADCE0'
  on-secondary-fixed: '#3C4043'
  on-secondary-fixed-variant: '#5F6368'
  tertiary-fixed: '#FCE8E6'
  tertiary-fixed-dim: '#FAD2CF'
  on-tertiary-fixed: '#6B1815'
  on-tertiary-variant: '#C5221F'
  background: '#FFFFFF'
  on-background: '#202124'
  surface-variant: '#F8F9FA'
typography:
  display-lg:
    fontFamily: Noto Sans TC
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Noto Sans TC
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0em
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
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  margin-mobile: 16px
  margin-desktop: 120px
  gutter: 16px
  section-gap: 48px
---

## 品牌與風格
此設計系統以「極簡高效」為核心概念。它採用**極簡主義**美學，融合**Material Design**原則以創造直觀的使用者體驗。目標受眾為追求快速搜尋結果的使用者，介面營造簡潔、專注且無干擾的感覺。

視覺語言在極簡與功能性之間取得平衡，確保使用者能快速輸入搜尋並獲得清晰的結果，無需被多餘的裝飾分散注意力。

## 色彩
調色板建立在「Google 風格」基礎上。
- **主色**：Google 藍（#1A73E8）用於主要互動元素、連結和重要操作按鈕。
- **次要色**：中性灰（#5F6368）用於次要文字和圖示。
- **強調色**：Google 紅（#EA4335）用於錯誤提示和警示訊息。
- **中性色**：純白背景（#FFFFFF）和深灰文字（#202124）確保極致簡潔與高可讀性。

## 排版
排版以清晰易讀與極簡風格為重。我們使用 **Noto Sans TC** 字體，確保繁體中文顯示效果最佳。
- **品牌標誌**：使用 `display-lg` 配合自定義字重，建立獨特的品牌識別。
- **搜尋結果**：使用 `body-lg` 用於標題，`body-md` 用於描述，建立清晰資訊層次。
- **字重**：主要使用常規（400），強調元素使用中粗體（500），避免過度粗體以維持極簡感。

## 佈局與間距
佈局遵循**中心對齊**哲學，確保搜尋框始終是視覺焦點。
- **邊距**：極寬的左右邊距（桌面 120px）創造呼吸感與專注感。
- **留白**：在主要元素之間使用充足的 `section-gap`，避免視覺擁擠。
- **對齊**：主要內容中心對齊以建立強烈的視覺焦點，搜尋結果左對齊以確保可讀性。

## 高度與深度
深度通過**微妙的陰影**和邊框傳達：
- **表面 0**：主背景（#FFFFFF）。
- **表面 1（搜尋框）**：純白背景搭配細微陰影和邊框（#DADCE0）。
- **表面 2（懸停狀態）**：使用輕微陰影增加互動回饋。
- **陰影**：使用極細陰影（模糊半徑 4px、低透明度 10%）保持極簡風格。

## 形狀
應用**圓角**設計以柔化介面，符合現代設計趨勢。
- **小元素**：圖示和小按鈕使用 0.25rem 半徑。
- **中元素**：搜尋框和結果卡片使用 `full`（9999px）創造藥丸形狀。
- **大元素**：主要區塊使用 `rounded-lg`（1rem）。
- **互動狀態**：按鈕懸停時輕微變色，搜尋框懸停時陰影加深。

## 組件
- **搜尋框**：中心對齊的大型藥丸形搜尋框，包含搜尋圖示、輸入區域和語音/圖片搜尋按鈕。
- **搜尋按鈕**：懸浮在搜尋框下方的兩個按鈕（Google 搜尋、好手氣）。
- **搜尋結果列表**：左對齊的搜尋結果，包含標題、描述、連結和網站資訊。
- **相關搜尋**：底部顯示相關搜尋建議的標籤式佈局。
- **頁尾導航**：底部固定的導航欄，包含主要功能分類連結。
- **快速捷徑**：首頁顯示常用服務的快速捷徑圖示。
