# 🐍 HTML5 貪食蛇遊戲 - 教學演進專案 (Snake Game Lesson)

本專案專為程式教學設計，展現一個單一 HTML 檔案如何從基礎畫面佈局，逐步演進為具備完整遊戲邏輯與選單系統的網頁遊戲。

---

### 🚀 各階段線上預覽與程式碼 (Interactive Demos)

學生與測試者可以直接點擊下方連結，體驗不同開發階段的網頁成果：

| 開發階段 | 網頁即時預覽連結 (Demo) | GitHub 程式碼分支 (Branch) |
| :--- | :--- | :--- |
| **Stage 1: UI 介面與控制** | [👉 點此體驗 Stage 1](https://snake-game-git-stage-1-ui-mingpig.vercel.app/) | [`stage-1-ui`](https://github.com/mingpig-edu/snake-game/blob/26d3856f14377c93389b112d5867e47b3a9775b7/index.html) |
| **Stage 2: 核心碰撞與地圖** | [👉 點此體驗 Stage 2](https://snake-game-git-stage-2-core-mingpig.vercel.app/) | [`stage-2-core`](https://github.com/mingpig-edu/snake-game/blob/fcc62bc0364470747198223632b33fe0c93b1846/index.html) |
| **Stage 3: 完整流程與選單** | [👉 點此體驗 Stage 3 (完整版)](https://snake-game-six-kappa-24.vercel.app/) | [`main`](https://github.com/mingpig-edu/snake-game/blob/6e229a7f2e1d4cf7bec53bc96f7f5cec652014ef/index.html) |

> 💡 **提示**：請將網址中的 `YOUR_ACCOUNT` 替換為你的 GitHub / Vercel 帳號名稱！

---

### 📚 階段演進說明 (Stage Breakdown)

#### 1. Stage 1: UI 介面與控制 (stage-1-ui)
* **重點內容**：建立 1:1 RWD 響應式 Canvas 畫布、建構半透明虛擬 D-Pad 按鈕、監聽鍵盤 (WASD/方向鍵) 與觸控事件。

#### 2. Stage 2: 核心碰撞與地圖 (stage-2-core)
* **重點內容**：貪食蛇移動與吃食物變長、3 款固定難度迷宮地圖、防爆食物生成演算法（100% 避開蛇身與牆壁）。

#### 3. Stage 3: 完整流程與選單 (main)
* **重點內容**：首頁設定面板、`localStorage` 玩家偏好記憶、過場關卡彈窗、全關卡通關慶祝畫面。
