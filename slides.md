---
theme: default
background: "./images/background.webp"
title: Figma Dev Mode Introduction - Terry Lin
drawings:
  persist: false
transition: slide-left
mdc: true
---

# 為什麼 Frontend Team 需要 Figma Dev Mode？
Terry Lin @MediaTek

---
layout: center
---

# 現況痛點

設計師完成設計稿後，前端工程師需要：
- 在 Figma 和 VSCode 間頻繁切換
- 手動複製貼上 CSS 屬性值
- 逐一檢查每個元件的樣式設定
- 反覆確認複雜的互動邏輯和狀態

**缺乏自動化工具，開發效率受限**

---
layout: center
---

# Figma Dev Mode 解決方案

專為開發者設計的介面模式

✅ 大幅提升設計與開發協作效率  
✅ 減少開發誤差  
✅ 讓設計落地更精準、快速

---

# 設計稿轉程式碼：三大核心功能

<br />

| 功能 | 影響程度 | 說明 |
|------|----------|------|
| Official MCP Server | 🔥 高 | AI 直接讀取設計稿生成程式碼 |
| Link Dev Resources | 🔥 中 | 連結外部開發資源 |
| Figma for VS Code | 🔥 低 | 在 VS Code 中直接檢視和檢查設計稿 |

---
layout: section
---

# [Official MCP Server](https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Dev-Mode-MCP-Server)

---

# 什麼是 Official MCP Server？

MCP 讓 AI Agent 直接與 Figma 溝通

## 使用流程
- 工程師使用 AI Agent 工具（如 Roo Code, Cline）
- 透過 Official Figma MCP 連接設計稿
- AI 直接讀取完整設計資料，自動生成對應程式碼

## 核心優勢
- 🎯 **精準度高**：直接讀取原始設計資料
- ⚡ **效率提升**：省去手動測量和轉換
- 🔄 **即時同步**：設計更新時程式碼可快速調整
- 🏆 **官方支援**：相較第三方 Figma MCP 有更高精準度

---
layout: center
---

<video controls width="500px">
  <source src="/videos/mcp.mov">
  Your browser does not support the video tag.
</video>

---
layout: section
---

# [Link Dev Resources](https://help.figma.com/hc/en-us/articles/15023231995927-Link-Dev-resources-to-layers-in-Dev-Mode)

---

# 什麼是 Link Dev Resources？

將外部開發資源直接連結到設計元件

## 資源類型範例
- Jira：連結需求票券和 Bug 報告
- Gitea Link：連結相關的程式碼儲存庫
- Storybook：連結元件文檔和範例
- VS Code Deep‑Link：直接開啟對應的程式碼檔案

## 實際效益
- 🎯 **快速定位**：從設計稿直接跳轉到相關資源
- 📋 **資訊整合**：所有相關資訊集中在一處
- 🚀 **提升效率**：減少在不同工具間切換的時間

---
layout: image
image: /images/dev-resources.png
backgroundSize: 50%
---

---
layout: section
---

# Figma for VS Code

---

# 什麼是 Figma for VS Code？

直接在 VS Code 中檢視和檢查 Figma 設計稿

## 核心功能
- 在 VS Code 中直接開啟和檢視設計檔案
- 檢查設計元件並獲得程式碼建議
- 即時查看和回應評論與活動

## 核心優勢
- 🚀 **無縫整合**：無需離開開發環境
- 💬 **即時協作**：直接在 VS Code 中查看評論
- 🎯 **精準檢查**：完整的設計檢查功能
- 📝 **程式碼建議**：基於設計的自動完成建議

---
layout: image
image: /images/vscode.gif
backgroundSize: 50%
---

---
layout: center
---

# 總結效益

透過這三大工具，設計稿轉程式碼的過程變得：

✨ **更自動化** - AI 直接生成程式碼  
🎯 **更精準** - 減少人為轉換誤差  
⚡ **更高效** - 省去重複性手動作業  
🤝 **更協作** - 設計與開發無縫接軌

---
layout: center
---

# 下一步：導入 Figma Dev Mode

---
layout: center
---

# 導入成本

- **Dev Seat 費用**：$25/月
- **以年計算**：$300（約 NT$8,800）
- **Organization 方案**：已具備該條件

**可以先買 1 個 Dev Seat 讓 FE Team 使用！**
