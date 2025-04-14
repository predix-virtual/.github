# 🧠 Predix - AI Powered PvP Prediction Market

**Turn your predictions into on-chain PvP battles — powered by AI agents and built on Base.**

Predix is a decentralized, AI-driven prediction platform where users can create and join head-to-head markets using simple prompts. No confusing UX, no bridging hurdles — just AI-powered matchmaking, resolution, and payouts across chains.

---

## 🚀 Overview

Predix simplifies speculative betting through natural language prompts and peer-to-peer matchups. Our platform uses AI to generate markets, resolve outcomes with real-world data, and ensure fair play via smart contracts — all on Base for fast, low-cost transactions.

---
<p align="center">
  <img src="https://predix-dev.s3.ap-northeast-2.amazonaws.com/Home%5Bconnect-wallet%5D_show-games.png" alt="Home - Show Games" width="45%" />
  <img src="https://predix-dev.s3.ap-northeast-2.amazonaws.com/chatting_.png" alt="Chatting" width="45%" />
</p>

---


## 🔑 Key Features

### 🤖 AI-Powered Prediction Flow
- AI agents auto-generate structured markets from prompts.
- Example: _"Will Arsenal beat Tottenham this weekend?"_
- Agents label outcomes, manage game status, and track resolution.

### ⚔️ Peer-vs-Peer Matchmaking
- No house edge — users face off directly.
- AI agents handle entry fee logic, pairing, and fairness.
- Stake USDC, community tokens, or KoL tokens.

### 🌐 Cross-Chain Liquidity via Wormhole
- Bring assets from Solana, Avalanche, or Optimism to Base in 1 click.
- AI confirms token bridging and market participation in real-time.

### 🧾 Automated Resolution & Transparent Payouts
- Game ends → AI fetches results from oracles (e.g., Arsenal wins 2-1).
- Smart contract resolves outcome → Payouts issued instantly.
- AI explains results in plain language.

---

## 🧠 AI-Powered Prompt System

Interact with Predix using natural commands:

- _"Create a BTC prediction for next 48 hours. Bet 2 ETH on UP."_
- _"Join the third prediction with 10 USDC."_
- _"List top 5 active predictions by total stake."_
- _"Show my history and claim rewards."_

---

## 🔗 How Predix Leverages Base

### ⚡ High-Speed, Feeless Transactions
- Base's throughput = real-time bets, payouts, and AI automation.

### 🔐 On-Chain Fairness
- Solidity smart contracts (via Hardhat) handle market logic and resolution.
- No centralized authority — just agents + code.

### 💰 Tokenized Ecosystem
- Support for ERC20 tokens including community coins.
- Contract: [`PrediX`](https://sepolia.basescan.org/token/0xe21835fbe4df83a02d72a717fd8bc1dcbcc6c042)
- txHash : https://sepolia.basescan.org/tx/0x811adf8ab6ec754dfc8c2eb601dc4851e18557e59b374c5c3f90d11e08e353b1

### 🛠️ Embedded Wallet Onboarding
- Non-crypto users can onboard via embedded wallets.
- Optional top-up via swaps (1inch Aggregator API) and fiat ramps (coming soon).

---

## 📱 SocialFi & Creator Tools

- **PnL NFT Cards**: Mint NFTs showing your win/loss record.
- **In-App Chat**: TalkJS or Sendbird integration for live discussions.
- **Twitter (X) Blink**: Create or join predictions directly from X posts.
- **Creator Markets**: KoLs can launch branded markets and earn revenue share.

---

## 💸 Business Model – PvP Prediction Platform

Predix is designed with a sustainable, scalable revenue model that grows alongside user activity and community engagement.

### 1. Platform Fee from Each Game
- A **customizable fee (default 3%)** is taken from the total wager pool of each game.
- This fee ensures long-term platform sustainability without relying on external funding.

> 🟢 **Example**: In a 100 USDC game, 3 USDC goes to the platform, and 97 USDC is distributed to the winner(s).

- Transparent fee logic handled entirely on-chain.
- Scales naturally with prediction volume and user participation.

### 2. Featured Prediction Listings (Coming Soon)
- **Creators, KoLs, or token projects** can pay to highlight their games.
- Featured games appear in:
  - Homepage spotlight
  - Leaderboards
  - Integrated Twitter (X) feed via Blink

> 💡 Fees accepted in USDC or ecosystem/partner tokens.

- Helps communities **showcase their tokens in real-world prediction use cases**.
- Opens doors for **cross-project collaboration and co-marketing**.

### 3. Optional Add-Ons (Monetization Expansion)
- **Branded Tournaments**:
  - Run sponsored competitions with co-funded prize pools.
  - Partner with DAOs, sports brands, or gaming communities.

- **Revenue-Sharing with Creators**:
  - Top-performing creators and KoLs receive a share of platform revenue from their hosted games.
  - Builds loyalty and incentivizes community-driven growth.

### Future Opportunities
- **Ad-Supported Prediction Streams**:
  - Monetize traffic via embedded ads, sponsored prompts, or native tokens.
- **Subscription-Based Premium Features**:
  - Advanced analytics, early access to AI-generated markets, or zero-fee betting tiers.
- **NFT Utility & Gamification**:
  - Offer discounts, exclusive matches, or higher rewards to NFT holders.

---

## 🌍 Market Opportunity

### 📈 Speculation as Engagement
- Prediction = gamified betting on what people already care about.
- $200B+ market covering sports, crypto, politics, and pop culture.

### 🎮 Rise of Onchain Gamified Finance
- Prediction = perfect blend of SocialFi, GameFi, and DeFi.
- Inspired by platforms like Polymarket, Helix, and friend.tech.

### 👩‍💼 KoL & Creator Economy Synergy
- PvP predictions are viral and community-powered.
- Creators drive engagement and monetize audience.

### 🤖 AI + Real-Time Data = The Future
- AI agents create, resolve, and explain prediction markets.
- No more manual admin, delayed results, or clunky UX.

---

## 🧱 Tech Stack

| Layer        | Tech |
|--------------|------|
| **Chain**    | Base |
| **Smart Contracts** | Solidity + Hardhat |
| **Oracles**  | [`api-sports.io`](https://api-sports.io/), [`OKX Wallet`](https://www.okx.com/wallet-api) |
| **Wallet/Swap** | Embedded wallets + 1inch Aggregator API |
| **Tokens**   | ERC20 (e.g., USDC, PrediX token) |

---

## 🔐 Governance & Security

- AI-based resolution verification + oracle fallback.
- Smart contract immutability ensures fairness.
- Regular audits and community governance.
- Wallet protection & withdrawal guardrails for safety.

---

## 🤝 Contribute

We welcome contributors! Open issues, suggest features, or submit a pull request. Help shape the future of AI-powered PvP markets.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).
