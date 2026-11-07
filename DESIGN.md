---
name: 城南蜃樓 主視覺提案
colors:
  bg: "#11100f"
  surface: "#1a1917"
  line: "#34312d"
  text: "#ece6dc"
  muted: "#a39b8f"
  accent: "#d8432f"   # 頁面介面唯一強調色；各方向的配色只出現在該方向區塊內
fonts:
  display: "Noto Serif TC" 900
  body: "Noto Sans TC" 400/500/700
  mono: "JetBrains Mono" 400/700
  kai: "LXGW WenKai TC"（只用在示範字體）
radius: 2px
spacing: 10（拼貼間距） 24 36 56 72 88
---

# 判讀

臺大藝術季《城南蜃樓》主視覺提案頁，給設計部與各部門看方向。用途是體驗：每個方向用真實照片即時套上效果。版面變化 7、動態 5、密度 5。

# 色彩

只有深色主題，讓照片與各方向的色票在同一個中性暗底上比較。介面只用一個朱紅強調色。三個方向各有四色色票：

- 面譜電路：#0D0F0E、#F2EDE4、#D7262B、#2FD39B
- 城南蜃樓：#141B2B、#E7C9A0、#4F8F86、#C8402F
- 金光外台：#C4161C、#FFD23F、#FF3D7F、#38FF8C

# 字型

標題 Noto Serif TC 900，內文 Noto Sans TC，行高 1.75，內文寬度上限 34em 到 40em。標籤與資訊文字用 JetBrains Mono。中文標題字距 0。

# 版面

每個方向一個 12 欄拼貼：左側大圖是即時效果示範，右側是字體示範與參考照片，下方三欄寫配色、字體與圖案、延伸應用。手機寬度改成 6 欄。

# 動態

面譜電路的走線上有光點流動，紋樣畫一次靜態圖；LED 掃描線、萬花筒持續動畫；蜃樓用 SVG 水波濾鏡做水中倒影。中英文切換用 data-en 屬性，選擇存在 localStorage，網址可加 ?lang=en。`prefers-reduced-motion` 時全部停在靜態畫面。
