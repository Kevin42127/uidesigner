---
name: Chronos Precision
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1b1b1d'
  surface-container: '#1f1f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e4e2e4'
  on-surface-variant: '#c7c6ca'
  inverse-surface: '#e4e2e4'
  inverse-on-surface: '#303032'
  outline: '#919094'
  outline-variant: '#46464a'
  surface-tint: '#c8c6c7'
  primary: '#c8c6c7'
  on-primary: '#313031'
  primary-container: '#0a0a0b'
  on-primary-container: '#7a797a'
  inverse-primary: '#5f5e5f'
  secondary: '#b0c6ff'
  on-secondary: '#002d6e'
  secondary-container: '#0068ec'
  on-secondary-container: '#f2f3ff'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#090b0b'
  on-tertiary-container: '#787a7a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e3'
  primary-fixed-dim: '#c8c6c7'
  on-primary-fixed: '#1c1b1c'
  on-primary-fixed-variant: '#474647'
  secondary-fixed: '#d9e2ff'
  secondary-fixed-dim: '#b0c6ff'
  on-secondary-fixed: '#001944'
  on-secondary-fixed-variant: '#00429b'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131315'
  on-background: '#e4e2e4'
  surface-variant: '#353437'
typography:
  display-time:
    fontFamily: Inter
    fontSize: 96px
    fontWeight: '700'
    lineHeight: 100px
    letterSpacing: -0.04em
  display-time-mobile:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
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
  margin-desktop: 64px
  gutter: 16px
  section-gap: 48px
---

## 品牌與風格
此設計系統以「時間清晰度」為核心概念。它採用**極簡主義**美學，融合**玻璃擬態**以創造深度感而不顯雜亂。目標受眾重視高效能工具，希望工具感覺高級且不干擾。用戶介面營造冷靜、精準、專注的感覺，移除不必要的裝飾，讓時間和核心操作成為焦點。

視覺語言在高對比字體的嚴峻與半透明層次的柔和之間取得平衡，確保即使在深色環境中，介面感覺通透且寬敞。

## 色彩
調色板建立在「深空」基礎上。
- **主色**：深炭色（#0A0A0B）作為畫布，提供純黑感，讓 OLED 螢幕消失。
- **次要色（強調）**：電光藍（#2E7BFF）專用於互動狀態、活動切換和主要行動呼籲。
- **中性色**：中調灰色用於容器背景和玻璃效果，在不破壞深色美學的情況下維持層次。
- **文字**：純白（#FFFFFF）保留給高優先級的時間讀數，而靜音灰色（#8E8E93）用於次要元資料。

## 排版
排版是主要的結構元素。我們使用 **Inter** 字體，因其中性、系統化的特性，在不同字重下表現出色。
- **時間讀數**：使用 `display-time` 配合緊湊字距，創造單一、有力的外觀。
- **層次**：使用 `label-caps`（大寫）標示小型實用文字，如「AM/PM」或「鬧鐘標籤」，以區別於內容。
- **字重**：標題使用半粗體（600），列表項使用常規（400）。避免使用細體，以保持與深色背景的高可讀性和對比度。

## 佈局與間距
佈局遵循**固定網格**哲學，在集中式欄中維持焦點。
- **邊距**：寬敞的外邊距（手機 24px）確保內容不會緊貼裝置邊緣。
- **留白**：在主時鐘面和次要控制（如鬧鐘列表或世界時鐘）之間使用 `section-gap`，強調「時間」作為主要元素。
- **對齊**：在時鐘面語境中，所有文字應視覺中心對齊；列表和設定則左對齊，以確保可掃描性。

## 高度與深度
深度通過**玻璃擬態**和微妙的色調層次傳達：
- **表面 0**：主背景（#0A0A0B）。
- **表面 1（卡片/列表）**：稍亮的炭色（#1A1A1C）搭配 1px 描邊（白色 @ 10% 透明度）定義邊緣。
- **表面 2（玻璃覆蓋）**：對於彈窗或懸浮操作按鈕，使用背景模糊（20px）搭配半透明中性填充（白色 @ 5% 透明度）。
- **陰影**：使用「環境陰影」— 大模糊半徑（32px）、低透明度（20%），帶有微藍色調以配合強調色。

## 形狀
應用**圓角**（值 2）方法以柔化高對比專業外觀。
- **小元素**：複選框和小按鈕使用 0.5rem 半徑。
- **大元素**：列表項、鬧鐘卡片和玻璃面板使用 `rounded-lg`（1rem）或 `rounded-xl`（1.5rem）感覺現代且觸感。
- **互動狀態**：按鈕按下時應輕微變形，增加圓角半徑以強化品牌支柱中提到的「柔軟」觸感。

## 組件
- **按鈕**：主要按鈕為純電光藍背景配白色文字。次要按鈕為幽靈風格，帶有微妙玻璃模糊背景。
- **鬧鐘卡片**：使用「色調層次」方法。卡片背景為 #1A1A1C。「活動」狀態時，邊框發出柔和電光藍外陰影。
- **輸入/選擇器**：時間選擇器應使用大型垂直捲動列表，高對比中心焦點和淡化上下邊緣。
- **切換**：自定義藥丸形切換。「關閉」狀態為深灰色；「開啟」狀態為電光藍配清晰白色圓形把手。
- **進度環**：對於計時器或碼表，使用細 2pt 描邊環。活動進度為電光藍，剩餘路徑為 10% 白色描邊。