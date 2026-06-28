# Pickleball Court Markers Helper AR

**用 AR 在地面投影 1:1 真實比例的匹克球場線條，幫助你精準放置場地標記。**  
**An AR web tool that projects a full-scale pickleball court onto the ground to help you place court markers accurately.**

---

## 什麼是這個工具？ / What is this?

這是一個免安裝的網頁 AR 工具，專為需要在空地上臨時標記匹克球場的使用者設計。  
用 iPhone Safari 開啟網址，即可透過相機看到 1:1 真實比例的球場線條疊加在地面上，再沿線放置 marker 即可。

This is a web-based AR tool — no app installation required. Designed for anyone who needs to temporarily mark a pickleball court on an open surface.  
Open the URL in iPhone Safari, point at the ground, and a 1:1 scale court overlay appears. Place your markers along the lines.

---

## 球場規格 / Court Specifications

| 項目 | 尺寸 |
|------|------|
| 整體尺寸 Overall size | 20 × 44 ft（6.1 × 13.4 m） |
| 廚房區深度 Kitchen depth | 各 7 ft from net |
| 發球區 Service courts | 10 × 15 ft × 2 |
| 線條寬度 Line width | 2 inches |

---

## 如何使用 / How to Use

> 僅支援 iPhone / iPad · iOS 12 以上 · Safari  
> iPhone / iPad only · iOS 12+ · Safari required

**1.** 用 iPhone Safari 開啟網址 / Open the URL in iPhone Safari:  
👉 **https://neoclarus.github.io/pickleball-court-markers-helper-ar**

**2.** 點擊「開啟 AR 球場」，跳出相機畫面後，請**對著地面緩慢移動** iPhone  
Tap **Open AR Court**. Once the camera opens, **slowly move your iPhone** while pointing at the ground.

**3.** 系統偵測完成後，球場線條會自動以 **1:1 真實比例**出現在地面上  
Once detected, the court lines will display at **1:1 real-world scale** on the ground.

**4.** **單指拖曳**球場，將球場移動到您想要的位置  
**Drag with one finger** to move the court to your desired position.

**5.** **雙指旋轉**球場，調整球場角度以對齊現場方向  
**Two-finger rotate** to adjust the court angle and align it with your space.

**6.** ⚠️ **雙指縮放會改變真實比例**。若尺寸跑掉，**雙擊（按兩下）** 球場即可重置回 1:1 原始大小  
⚠️ **Pinch to scale will alter real-world size.** If this happens, **double-tap** the court to reset to 1:1 scale.

**7.** 當球場調整至理想位置後，即可順著螢幕上的**虛擬線條**在地面**放置標記**  
Once the court is in position, place **markers on the ground** following the **virtual lines** on screen.

---

## 技術說明 / Technical Notes

- 使用 Apple AR Quick Look（USDZ 格式），無需下載 App  
  Uses Apple AR Quick Look (USDZ format) — no app download required
- 球場幾何由 USD/Python 程式生成，尺寸依官方 USA Pickleball 規格  
  Court geometry generated via USD/Python, dimensions per official USA Pickleball specifications
- 僅支援 iOS Safari（WebXR 在 iOS 上受 Apple 限制，故採用 AR Quick Look）  
  iOS Safari only — AR Quick Look is used because Apple restricts WebXR on iOS

---

## 授權 / License

MIT License
