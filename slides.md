---
theme: default
background: './images/background.webp'
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
| Code Connect | 🔥 中 | 在設計稿中顯示真實程式碼 |
| Link Dev Resources | 🔥 低 | 連結外部開發資源 |

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
- AI 直接讀取完整的設計資料
- 自動生成對應的程式碼

## 核心優勢
- 🎯 **精準度高**：直接讀取原始設計資料
- ⚡ **效率提升**：省去手動測量和轉換
- 🔄 **即時同步**：設計更新時程式碼可快速調整
- 🏆 **官方支援**：相較第三方 Figma MCP 有更高精準度

---
layout: section
---

# [Code Connect](https://help.figma.com/hc/en-us/articles/23920389749655-Code-Connect)

---

# 什麼是 Code Connect？

連接設計元件與真實程式碼的橋樑

## 核心概念
- 在 Figma 設計稿中直接顯示**真實的程式碼**
- 不是自動生成的程式碼片段
- 由開發團隊維護和更新

## 實際效益
- 🔗 **設計與程式碼同步**：確保設計稿反映實際實作
- 📚 **程式碼文檔化**：設計稿成為活的程式碼文檔
- 🤝 **團隊協作**：設計師能看到實際的實作方式

---
layout: section
---

# [Link Dev Resources](https://help.figma.com/hc/en-us/articles/15023231995927-Link-Dev-resources-to-layers-in-Dev-Mode)

---

# 什麼是 Link Dev Resources？

將外部開發資源直接連結到設計元件

## 支援的資源類型
- 📝 **Jira**：連結需求票券和 Bug 報告
- 🔗 **Gitea Link**：連結相關的程式碼儲存庫
- 📖 **Storybook**：連結元件文檔和範例
- 💻 **VS Code Deep‑Link**：直接開啟對應的程式碼檔案

## 實際效益
- 🎯 **快速定位**：從設計稿直接跳轉到相關資源
- 📋 **資訊整合**：所有相關資訊集中在一處
- 🚀 **提升效率**：減少在不同工具間切換的時間

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

# 導入成本與效益

- **Dev Seat 費用**：$25/月
- **年費**：$300（約 NT$8,800）
- **Organization 方案**：已具備該條件

**可以先買一個帳號讓 FE Team 實際使用於工作**
