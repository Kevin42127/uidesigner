---
name: TaskMaster
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#4648d4'
  on-secondary: '#ffffff'
  secondary-container: '#6063ee'
  on-secondary-container: '#fffbff'
  tertiary: '#7e3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#a44100'
  on-tertiary-container: '#ffd2be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  container-padding-mobile: 16px
  container-padding-desktop: 40px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

TaskMaster 的設計理念基於「簡潔高效的任務管理」。目標使用者是忙碌的專業人士和學生，需要一個能減少認知負擔而非增加負擔的工具。視覺語言採用 **極簡主義與功能性**，傾向於現代企業美學，感覺可靠且親切。

UI 優先考慮高水平的留白，讓任務有「呼吸的空間」，確保使用者的專注力完全集中在當前目標上。動畫應該微妙——柔和的淡入淡出和輕微的垂直位移——以強化平靜、有組織的工作空間感覺。

## Colors

調色板以專業的 **靛藍色** 為主色，選擇它因為與專注和穩定性相關。

- **主要色與次要色：** 用於活動狀態、主要操作（新增任務）和品牌元素。
- **中性色階：** 使用冷灰色調維持清晰、現代的感覺。背景是非常淺的灰白色 (#F8FAFC)，與純白色相比減少眼睛疲勞。
- **語義優先級：** 高優先級任務使用柔和的紅色，中等使用溫暖的琥珀色，低優先級/已完成任務使用平靜的翠綠色。這些應該謹慎使用，作為小指示器或細邊框，避免壓倒極簡佈局。

## Typography

設計系統對所有角色使用 **Inter** 字體，以確保最大的可讀性和系統化的乾淨外觀。

- **標題：** 使用更緊的字元間距和半粗體重量，為列表標題和日期創建強烈的視覺錨點。
- **內文：** 標準化為 16px 以在任務管理期間獲得最佳可讀性。
- **標籤：** 在較小尺寸時使用稍重的重量（中等/半粗體），用於標籤、優先級徽章和元數據如到期日。

## Layout & Spacing

佈局遵循 **固定網格** 哲學，適用於桌面版，以防止任務行變得過長且難以掃描。在行動裝置上，系統過渡到流體模型，具有 16px 邊距。

嚴格的 **8px 基礎單位** 管理所有間距。
- **任務列表：** 任務內的元素（核取方塊、文字、標籤）以 12px 或 16px 分隔。
- **垂直節奏：** 任務卡片以 8px 或 12px 間隙堆疊，以維持清晰但密集的資訊流。
- **分組：** 大型區塊（例如「今天」對「即將到來」）以 48px 分隔，提供清晰的認知中斷。

## Elevation & Depth

此設計系統使用 **色調層** 結合 **環境陰影** 來創建有組織堆疊的感覺。

- **層級 0（背景）：** 工作區地面 (#F8FAFC)。
- **層級 1（卡片）：** 任務和主要內容區域位於白色表面上，具有非常柔和、擴散的陰影（模糊：10px，Y：4px，不透明度：主要靛藍色的 4%），使它們看起來略微提升。
- **層級 2（互動）：** 懸停的任務或活動選單略微增加陰影擴散和不透明度（模糊：20px，Y：8px，不透明度：8%），以暗示「拾取」互動性。
- **模態框：** 使用背景模糊（12px）將使用者專注於任務創建或編輯流程。

## Shapes

形狀語言是 **圓角形**，使用 0.5rem (8px) 基礎半徑用於標準元素，以柔化專業美學。

- **標準（8px）：** 任務卡片、輸入欄位和較小按鈕。
- **大型（16px）：** 主要導航面板、模態容器和功能亮點。
- **超大型/膠囊形（24px+）：** 搜尋欄、優先級標籤和「新增任務」按鈕，使它們感覺更觸感且吸引人。

## Components

### 按鈕
主要按鈕使用實心靛藍色背景配白色文字。幽靈按鈕（僅輪廓）適用於次要操作，如「取消」或「編輯」，以維持乾淨的視覺層次。

### 任務卡片
卡片是設計系統的主要單位。它們具有白色背景、微妙的 1px 邊框 (#E2E8F0) 和柔和的陰影。左邊緣的細 4px 垂直條表示優先級顏色（紅色、琥珀色、綠色）。

### 核取方塊
核取方塊自定義樣式為大型圓形或高度圓角正方形。勾選時，它們應該從空狀態過渡到實心靛藍色填充配白色勾號，並伴隨任務文字的刪除線和 50% 不透明度降低。

### 輸入欄位
新增任務的輸入欄位應該突出，使用 16px 內邊距和微妙的靛藍色聚焦環（2px 寬度）。使用描述性的佔位符文字（例如「需要做什麼？」）。

### 晶片/標籤
類別標籤（例如「工作」、「個人」）使用淺灰色背景配中等重量文字。它們應該具有膠囊形狀半徑（rounded-xl），以獲得友好、現代的感覺。

### 進度指示器
列表或類別頂部的微妙進度條在任務完成時提供視覺滿足感，使用主要靛藍色作為填充，淺灰色作為軌道。