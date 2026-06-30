---
name: 模擬航空公司官網
colors:
  surface: '#FFFFFF'
  surface-dim: '#E8E8E8'
  surface-bright: '#FFFFFF'
  surface-container-lowest: '#FFFFFF'
  surface-container-low: '#F0F4F8'
  surface-container: '#E8EEF4'
  surface-container-high: '#DCE8F0'
  surface-container-highest: '#D0E0EC'
  on-surface: '#1A2B3C'
  on-surface-variant: '#5A6B7C'
  inverse-surface: '#2C4A5C'
  inverse-on-surface: '#F0F8FC'
  outline: '#B0C4D4'
  outline-variant: '#D0E0EC'
  surface-tint: '#0066CC'
  primary: '#0066CC'
  on-primary: '#FFFFFF'
  primary-container: '#E6F0FF'
  on-primary-container: '#004499'
  inverse-primary: '#66B3FF'
  secondary: '#0088CC'
  on-secondary: '#FFFFFF'
  secondary-container: '#E6F7FF'
  on-secondary-container: '#006699'
  tertiary: '#FF6B35'
  on-tertiary: '#FFFFFF'
  tertiary-container: '#FFE6D9'
  on-tertiary-container: '#CC5522'
  error: '#DC2626'
  on-error: '#FFFFFF'
  error-container: '#FEE2E2'
  on-error-container: '#991B1B'
  primary-fixed: '#E6F0FF'
  primary-fixed-dim: '#66B3FF'
  on-primary-fixed: '#003366'
  on-primary-fixed-variant: '#0055AA'
  secondary-fixed: '#E6F7FF'
  secondary-fixed-dim: '#66D9FF'
  on-secondary-fixed: '#003D5C'
  on-secondary-fixed-variant: '#006699'
  tertiary-fixed: '#FFE6D9'
  tertiary-fixed-dim: '#FFB399'
  on-tertiary-fixed: '#662211'
  on-tertiary-variant: '#CC5522'
  background: '#FFFFFF'
  on-background: '#1A2B3C'
  surface-variant: '#F0F4F8'
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
  margin-mobile: 24px
  margin-desktop: 80px
  gutter: 24px
  section-gap: 64px
---

## 品牌與風格
此設計系統以「專業可靠」為核心概念。它採用**企業級設計**美學，融合**現代卡片式佈局**以創造清晰的資訊架構。目標受眾為尋找航班資訊與訂票服務的旅客，介面營造專業、值得信賴且易於導航的感覺。

視覺語言在企業專業感與現代使用者體驗之間取得平衡，確保使用者能快速找到所需資訊並完成訂票流程。

## 色彩
調色板建立在「航空藍」基礎上。
- **主色**：航空藍（#0066CC）用於主要品牌元素、導航和重要操作按鈕，傳達專業與信任。
- **次要色**：天空藍（#0088CC）用於次要互動元素和連結。
- **強調色**：活力橙（#FF6B35）用於促銷資訊、特價標籤和緊急操作。
- **中性色**：淺藍灰色背景（#F0F4F8）和深藍灰色文字（#1A2B3C）確保高對比度與可讀性。

## 排版
排版以清晰易讀與專業感並重。我們使用 **Noto Sans TC** 字體，確保繁體中文顯示效果最佳。
- **主標題**：使用 `display-lg` 配合緊湊字距，建立強烈的視覺焦點。
- **層次**：使用 `headline-lg` 用於區塊標題，`label-md` 用於小型標籤和導航。
- **字重**：標題使用粗體（600-700），內容文字使用常規（400），建立清晰視覺層次。

## 佈局與間距
佈局遵循**響應式網格**哲學，確保在各種裝置上都能提供最佳瀏覽體驗。
- **邊距**：寬敞的外邊距（手機 24px、桌面 80px）確保內容呼吸感。
- **留白**：在主要區塊之間使用充足的 `section-gap`，建立清晰的視覺區隔。
- **對齊**：主要內容左對齊以確保可讀性，導航和操作元素右對齊。

## 高度與深度
深度通過**卡片式設計**和微妙的陰影傳達：
- **表面 0**：主背景（#FFFFFF）。
- **表面 1（內容卡片）**：淺藍灰色背景（#F0F4F8）搭配細微陰影。
- **表面 2（互動卡片）**：使用航空藍背景（#E6F0FF）突出顯示重要資訊。
- **陰影**：使用環境陰影（模糊半徑 16px、低透明度 20%）創造層次感。

## 形狀
應用**圓角**設計以柔化企業風格，提升現代感。
- **小元素**：輸入框和小按鈕使用 0.5rem 半徑。
- **中元素**：卡片和資訊區塊使用 `rounded-lg`（1rem）。
- **大元素**：主要區塊和橫幅使用 `rounded-xl`（1.5rem）。
- **互動狀態**：按鈕和卡片懸停時輕微上浮，增加互動回饋。

## 組件
- **導航欄**：頂部固定導航，包含品牌標誌、主要選單和登入/註冊按鈕。
- **航班搜尋器**：大型搜尋卡片，包含出發地、目的地、日期和旅客人數輸入。
- **航班列表**：卡片式航班資訊顯示，包含航空公司、時間、價格和預訂按鈕。
- **促銷橫幅**：全寬橫幅顯示特價資訊和促銷活動。
- **服務卡片**：網格佈局顯示各項服務（行李、座位、餐點等）。
- **頁尾**：多欄式頁尾，包含公司資訊、服務連結和社交媒體。
