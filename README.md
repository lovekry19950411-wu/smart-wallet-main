# 🔐 Smart Wallet — 免 Gas 費的開源智慧錢包
### Gas-free Smart Wallet for Everyone

[![Deploy with Vercel](https://vercel.com/button)](https://smart-wallet-wine.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Built with Alchemy](https://img.shields.io/badge/Built%20with-Alchemy-blue)](https://alchemy.com)

**Live Demo：** https://smart-wallet-wine.vercel.app

---

## 💡 這是什麼？ / What is this?

Smart Wallet 是一個開源的 Web3 工具，讓任何人都能**不需要懂加密貨幣、不需要付 Gas 費**，直接體驗 NFT 與區塊鏈。

A Web3 tool that lets anyone mint NFTs and interact with the blockchain — **no crypto knowledge, no Gas fees required.**

---

## ✨ 核心功能 / Features

| 功能 | 狀態 |
|------|------|
| 📧 Email Magic Link 登入 | ✅ 完成 |
| 💳 免 Gas 費鑄造 NFT | ✅ 完成 |
| 🔐 Account Abstraction（EIP-4337） | ✅ 完成 |
| 🌐 Ethereum Sepolia 測試網 | ✅ 完成 |
| 🔴 Optimism Sepolia 測試網 | ✅ 完成 |
| 🔑 Google / GitHub 社群登入 | 🔜 開發中 |
| 💱 跨鏈整合 | 🔜 規劃中 |
| 💳 信用卡購買入口 | 🔜 規劃中 |
| 🎵 音樂 NFT 發布 | 🔜 規劃中 |
| 🌍 World ID 真人驗證整合 | 🔜 規劃中 |
| 📖 白皮書 & 上鏈流程 | 🔜 規劃中 |

---

## 🛠 技術架構 / Tech Stack

- **前端**：Next.js 14 + TypeScript + Tailwind CSS
- **智慧錢包**：Alchemy Account Kit（Account Abstraction）
- **Gas 贊助**：Alchemy Gas Manager（Paymaster）
- **登入**：Alchemy Magic Link（Email OTP）
- **區塊鏈**：Ethereum Sepolia / Optimism Sepolia
- **部署**：Vercel

---

## 🚀 快速開始 / Getting Started

```bash
# 1. Clone 專案
git clone https://github.com/SP-WU/smart-wallet.git
cd smart-wallet

# 2. 安裝依賴
npm install

# 3. 設定環境變數
cp .env.example .env.local
# 填入你的 Alchemy API Key 和 Policy ID

# 4. 啟動開發伺服器
npm run dev
```

### 環境變數

```env
NEXT_PUBLIC_ALCHEMY_API_KEY=你的_Alchemy_API_Key
NEXT_PUBLIC_ALCHEMY_POLICY_ID=你的_Gas_Policy_ID
NEXT_PUBLIC_CHAIN_ID=11155111
```

取得 API Key：https://dashboard.alchemy.com

---

## 🗺 路線圖 / Roadmap

**Phase 1 — 基礎建設（已完成）**
- ✅ Email 登入 + 免 Gas 鑄造 NFT
- ✅ 部署至測試網（ETH Sepolia / OP Sepolia）
- ✅ 開源發布

**Phase 2 — 功能擴展（進行中）**
- 社群登入（Google / GitHub）
- 錢包管理介面
- NFT 收藏展示

**Phase 3 — 生態整合（規劃中）**
- 跨鏈橋接
- 信用卡入口
- World ID 真人驗證

**Phase 4 — 創作者經濟（規劃中）**
- 音樂 NFT 發布平台
- 創作者會員制度
- 白皮書 & 代幣設計

---

## 🌱 為什麼建這個 / Why I Built This

我曾陷入負債、遭遇詐騙、一無所有。那段經歷讓我意識到：**當個人真正陷入困境時，現有的金融系統幾乎幫不上忙。**

Web3 有潛力改變這一點，但使用門檻太高，一般人根本進不來。

Smart Wallet 的目標很簡單：**把這道門打開。**

---

## 🤝 支持這個專案 / Support This Project

如果你認同這個願景，可以透過以下方式支持：

- ⭐ 給這個 repo 一個 Star
- 🍀 Giveth 募款：https://giveth.io/project/smart-wallet-public-fundraising
- 🔁 分享給更多人
- 💬 開 Issue 提供想法或回報問題
- 🛠 Fork 並貢獻程式碼

---

## 📄 授權 / License

MIT License — 自由使用、修改、分發。

---

*Built with ❤️ by [@lovekry19950411](https://github.com/lovekry19950411-wu) — one person, part-time, from a place of genuine need.*
