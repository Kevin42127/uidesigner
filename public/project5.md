---
name: 高效店家搜尋應用
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f1'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e3e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#3e4944'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#6e7a74'
  outline-variant: '#bdc9c2'
  surface-tint: '#006c52'
  primary: '#00664d'
  on-primary: '#ffffff'
  primary-container: '#008163'
  on-primary-container: '#ddffef'
  inverse-primary: '#75d9b6'
  secondary: '#bc0004'
  on-secondary: '#ffffff'
  secondary-container: '#e1271c'
  on-secondary-container: '#fffbff'
  tertiary: '#914037'
  on-tertiary: '#ffffff'
  tertiary-container: '#af584d'
  on-tertiary-container: '#fff5f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#91f6d1'
  primary-fixed-dim: '#75d9b6'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#00513d'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4a9'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#930002'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#3e0403'
  on-tertiary-fixed-variant: '#792f26'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e0'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  button-text:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-padding: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
  gutter: 16px
---

## 品牌與風格
設計系統基於「高效實用」理念——平衡高效率零售導航與精緻優美美學。介面設計感覺快速、可靠且輕鬆，消除使用者前往實體位置的過程阻力。

風格融合了**企業現代**與**極簡主義**。利用大量空白防止資訊過載，確保地圖資料和店家詳情保持焦點。雖然功能實用，但執行層次高級，具備平滑過渡、寬大點擊目標，以及在高能量品牌色彩與寧靜臨床背景間的刻意運用。

## 色彩
色調以活躍的「7-11 靈感」綠色為主，象徵成長與前往點。橘色重點色節制但策略性地用於高優先級行動呼籲、通知或狀態指示器（如「即將關閉」）。

- **主色 (#008163)：** 用於主要品牌時刻、啟用狀態和導覽圖標。
- **次要色 (#EE3124)：** 保留給「路線」按鈕、緊急警報和高對比標記。
- **表面層級：** 使用潔白基底搭配極淺冷灰色（`#F2F4F3`）用於元素和卡片分組，創造細膩層次效果而不依賴重邊框。
- **字體：** 深炭灰色中性色確保所有表面的高可讀性和可存取對比度。

## 字體
此設計系統整個字體比例使用 **Inter**。Inter 提供系統化、實用清晰度，對搜尋尋找應用至關重要。

- **字重策略：** 標題使用半粗體（600）和粗體（700）為尋找店家名稱和距離的使用者創造清晰「掃描路徑」。
- **可讀性：** 內文優化為 16px 用於一般資訊，14px 用於次要元資料（如營業時間、地址詳情）。
- **大寫：** 距離或狀態標籤使用大寫配輕微字母間距區別於互動內文。

## 佈局與間距
佈局遵循針對手持裝置優化的**流動網格**模型。依賴一致的 8px 空間系統維持垂直節奏。

- **移動限制：** 4 欄網格配 20px 外邊距。
- **視覺呼吸空間：** 主要區域間大 24px 間隙（如地圖與店家清單間）維持「高級」感。
- **安全區域：** 互動元素保持最少 48px 高度確保移動時易於點擊。

## 高度與深度
為達成「高效實用」感，系統避免重深色陰影。改用**環境陰影**和**色調層次**。

- **層級 1（表面）：** 預設背景（`#FFFFFF`）。
- **層級 2（卡片）：** 店家詳情浮動卡片使用非常柔和擴散陰影（模糊：16px，Y：4px，顏色：`#000000` 5% 透明度）。
- **層級 3（模態框/工作表）：** 店家資訊底部工作表使用更顯著陰影（模糊：32px，Y：8px，顏色：`#000000` 10% 透明度）表示最頂層互動層。
- **玻璃擬態：** 導覽列和「移動中搜尋」按鈕使用背景模糊（20px）配半透明白色填充維持後方地圖上下文。

## 形狀
形狀語言友善現代，利用顯著圓角柔化應用實用重質特性。

- **標準元素：** 按鈕、輸入欄位和卡片使用 16px（`rounded-lg`）圓角。
- **小元素：** 晶片和狀態徽章使用 8px（`rounded-md`）圓角。
- **搜尋列：** 完全膠囊形（圓角：100px）區別為使用者意圖主要進入點。

## 元件

- **按鈕：** 
  - **主要（路線）：** 實心 `#EE3124`（橘色）配白文字。高對比驅動主要使用者目標。
  - **次要（店家詳情）：** 實心 `#008163`（綠色）配白文字。
  - **幽靈：** 透明配 1px 主色邊框用於較次要行動如「篩選」。
- **輸入欄位：** 搜尋列應為膠囊形，具備細膩 1px 邊框（`#E0E0E0`）和前置「搜尋」圖標。
- **卡片：** 店家卡片具備大 16px 圓角，左側店家圖片右側文字。應顯現略微提升配環境陰影。
- **晶片：** 用於篩選（如「營業中」、「有加油站」、「電動車充電」）。啟用晶片使用主色綠背景；非啟用晶片使用淺灰表面。
- **清單：** 清單檢視店家結果以細膩 1px 分隔線或分組卡片配 16px 間隙分隔。
- **底部工作表：** 移動版，店家詳情透過可拖曳底部工作表顯示，具備 24px 頂部圓角，允許使用者閱讀詳情時保持地圖檢視。