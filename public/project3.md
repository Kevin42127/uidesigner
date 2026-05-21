---
name: Modern Portfolio Design System
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb783'
  on-tertiary: '#4f2500'
  tertiary-container: '#d97721'
  on-tertiary-container: '#452000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703700'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Outfit
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.0'
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
  container-max: 1200px
  gutter: 24px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
---

## 品牌與風格
設計系統專為平衡技術熟練度與編輯優雅的高端個人品牌而設計。它針對設計、工程和創意科技領域的專業受眾。

視覺方向遵循**極簡現代**美學。它優先考慮清晰度和意圖性，使用寬敞的留白讓作品呼吸。介面採用精緻的深色模式以減少眼睛疲勞並創造「高級」感，以單一鮮豔的強調色點綴，引導用戶注意力關鍵行動呼籲。整體情感回應應是可靠性、精確性和前瞻性創新。

## 色彩
調色板建立在「午夜」基礎上。背景是深近黑海軍藍，提供比純十六進制黑色更多深度。

- **主色（電光靛藍）**：用於主要操作、活動狀態和突出關鍵成就。
- **次要色（祖母綠）**：謹慎用於成功狀態或特定「開放工作」指示器。
- **中性/表面**：一系列板岩灰色用於通過色調層次而非重邊框創造層次。
- **文字**：高對比白色用於標題，靜音板岩灰用於內文，確保長文可讀性。

## 排版
排版策略使用幾何無襯線字體配衝擊力，和高度可讀的新哥特字體配內容。

- **Outfit（標題）**：選擇因其乾淨、幾何構造感覺現代且親切。大型顯示尺寸使用緊湊字距，營造「設計」編輯外觀。
- **Inter（內文）**：用於所有功能文字。它在小尺寸下提供卓越可讀性，並保持中性、專業語調。
- **JetBrains Mono（標籤/系統）**：等寬字體用於標籤、類別和技術元資料，強化「科技前進」品牌支柱。

## 佈局與間距
設計系統在桌面上採用**12 欄流動網格**，在手機上採用**4 欄網格**。

佈局原則：
- **垂直節奏**：嚴格的 8px 基礎單元控制所有內距和外距。
- **部分呼吸空間**：顯著的垂直內距（120px+）用於部分之間，定義單頁流程並防止資訊過載。
- **對齊**：內容通常居中對齊或遵循作品集項目的「之字形」交替模式，以維持視覺趣味。
- **最大寬度**：內容限制在 1200px，確保在超寬螢幕上線長保持可讀。

## 高度與深度
深度通過**色調層次**和**環境陰影**創造。在此深色主題環境中，高度通過表面「接近」用戶時變亮來表示。

- **層級 0（背景）**：最深海軍藍（#020617）。
- **層級 1（卡片/表面）**：板岩海軍藍（#0F172A）。
- **陰影**：使用大型、超柔陰影（模糊：40px+）配低透明度（15-20%）黑色。避免嚴峻邊緣。
- **互動**：懸停時，卡片應在 Y 軸上平移 -4px 並增加陰影擴散，模擬物理升起。
- **邊框**：卡片上使用 1px 微妙邊框（#1E293B）以確保對背景的定義。

## 形狀
形狀語言為**精緻圓角**。所有容器、按鈕和輸入欄位使用一致的圓角半徑以柔化技術美學。

- **基礎半徑**：0.5rem（8px）用於標準組件，如按鈕和輸入。
- **大半徑**：1rem（16px）用於作品集卡片和主要內容容器。
- **媒體**：圖片和專案縮圖應始終匹配容器的 1rem 半徑。

## 組件
### 按鈕
- **主要**：純電光靛藍背景配白色文字。無邊框。
- **次要**：透明背景配 1px 板岩灰邊框。懸停時轉換為幽靈主色。
- **縮放**：高內距（12px 24px）確保大型點擊目標和高級感。

### 作品集卡片
- 背景：表面顏色（#0F172A）。
- 內容：頂部圖片（16:9 比例），後接標題（Outfit）和簡短描述（Inter）。
- 標籤：底部小型等寬標籤，用於技術堆疊圖標或文字。

### 輸入
- 僅底部邊框或非常微妙填充樣式。聚焦狀態將邊框顏色轉換為主電光靛藍。

### 導航（固定）
- 極簡玻璃擬態模糊（背景濾鏡：模糊 12px）固定到視口頂部，帶有微妙底部分隔線。

### 晶片/標籤
- 小型藥丸形元素，配微妙背景色調（主色 5% 透明度）和主色標籤。