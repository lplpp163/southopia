---
name: Southopia 應徵作品頁
colors:
  bg: "#07080d"
  surface: "#0f1119"
  line: "#262a38"
  text: "#ece6da"
  muted: "#9c978d"
  accent: "#ff4a3d"   # 霓虹朱紅，全頁唯一強調色
  jade: "#2de2c4"     # 只用在畫布與 AR 線條，不用在介面元件
fonts:
  display: "Noto Serif TC" 700/900
  body: "Inter", "Noto Sans TC" 400/500/700
  mono: "IBM Plex Mono" 400
radius: 2px（籤條、按鈕），畫布 0
spacing: 4 8 12 16 24 40 64 112
---

# 判讀

臺大藝術季《Southopia 城南蜃樓》應徵用的作品頁，用途是體驗。主題是東方賽博龐克：墨黑底、朱紅霓虹、明體標題。版面變化 7、動態 7、密度 4。

# 色彩

只有深色主題（`color-scheme: dark`），作品頁的氛圍需要固定的暗場。朱紅用在按鈕、標題強調與分隔線；玉綠只出現在畫布裡。內文 #ece6da 對 #07080d 的對比約 15:1，次要文字 #9c978d 約 7:1。

# 字型

標題用 Noto Serif TC 900，帶戲曲刊頭的氣質；內文 Noto Sans TC，行高 1.75；標籤與程式字用 IBM Plex Mono。中文標題字距 0，不做全大寫小標。

# 版面

每個區塊版型不同：主視覺滿版畫布；AR 區左畫面右說明；海報區左控制右成品；工作坊用時間軸。內文寬度上限 34em。

# 動態

主視覺持續動畫，滑鼠位置改變蜃樓的扭曲程度；區塊進場淡入 400ms。`prefers-reduced-motion` 時主視覺只畫一張靜態圖。
