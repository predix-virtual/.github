# 🧠 Predix - AI Powered PvP Prediction Market

**Turn your predictions into on-chain PvP battles — powered by AI agents and built on Base.**

Predix is a decentralized, AI-driven prediction platform where users can create and join head-to-head markets using simple prompts. Our platform leverages the **GAME SDK's High-Level Planner (HLP) and Low-Level Planner (LLP)** architecture to automate market creation, matchmaking, oracle integration, resolution, and payouts seamlessly across chains. No confusing UX, no bridging hurdles — just intelligent automation driving PvP prediction markets.

---

## 🚀 Overview

PrediX simplifies speculative betting through natural language prompts and peer-to-peer matchups. Our platform uses an AI agent system, built with the GAME SDK, featuring:

1.  llama 3.1: Core model of the GAME sdk.
2.  Workers: Specialized agents that execute specific tasks assigned by the HLP 

This architecture enables automated market generation, outcome resolution using real-world data via oracles, and ensures fair play via smart contracts — all on Base for fast, low-cost transactions.

---
<p align="center">
  <img src="https://predix-dev.s3.ap-northeast-2.amazonaws.com/Home%5Bconnect-wallet%5D_show-games.png" alt="Home - Show Games" width="45%" />
  <img src="https://predix-dev.s3.ap-northeast-2.amazonaws.com/chatting_.png" alt="Chatting" width="45%" />
</p>

---


## 🔑 Key Features

### 🤖 AI-Powered Prediction Flow
- **Prompt Interpretation**: The Planner receives a user prompt (e.g., _"Will Arsenal beat Tottenham this weekend?"_) and delegates the parsing task to a specialized LLP (Worker).
- **Structured Market Generation (LLP)**: An LLP, equipped with the necessary functions (`action_space`), structures the prediction market data .
- **Lifecycle Management (HLP)**: The HLP oversees the entire market lifecycle, coordinating LLPs for tasks like status updates (open, locked, resolving, closed) and resolution tracking using GAME SDK's state management (`get_state_fn`).

### ⚔️ Peer-vs-Peer Matchmaking
- No house edge — users face off directly.
- AI-Driven Fairness
- Stake USDC, community tokens, or KoL tokens.

### 🌐 Cross-Chain Liquidity via Wormhole
- Bring assets from Solana, Avalanche, or Optimism to Base in 1 click.
- **AI Confirmation**: An monitors bridging events and confirms token arrival and market participation in real-time, updating the system state.

### 🧾 Automated Resolution & Transparent Payouts
- **Oracle Interaction**: Game ends → HLP directs a specialized Oracle LLP to fetch results (e.g., query `api-sports.io` for "Arsenal wins 2-1") using pre-defined `Functions`.
- **Smart Contract Execution**: Based on the verified outcome, another triggers the resolution logic in the smart contract → Payouts issued instantly.
- **AI Explanation**: A dedicated Explanation LLP synthesizes the fetched data and execution steps to provide results in plain language.

---

## 🧠 AI Architecture: Leveraging GAME SDK's HLP/LLP

Predix's AI capabilities are built upon the **GAME SDK**, employing a hierarchical planning model:

1.  **High-Level Planner (HLP - The `Agent`)**:
    *   **Role**: The central coordinator, responsible for achieving the overall `agent_goal`

2.  **Low-Level Planners (LLPs - The `Workers`)**:
    *   **Role**: Specialized task executors, each with a specific `worker_description` (e.g., "Oracle Interaction Worker," "Smart Contract Interaction Worker,").

3.  **State Management (`get_state_fn`)**: Both HLP and LLPs use state functions to maintain awareness of the environment (market status, user balances, oracle data availability) based on the results (`FunctionResult`) of executed actions.

4.  **Foundation Models**: Powered by configurable llm (e.g., Llama-3.1-405B) to enable natural language understanding and sophisticated planning.

This architecture allows Predix to handle complex workflows autonomously, adapt to new information, and maintain modularity for future upgrades.

---

## 🔗 How Predix Leverages Base

### ⚡ High-Speed, Feeless Transactions
- Base's throughput = real-time bets, payouts, and efficient AI automation (LLPs trigger transactions quickly).

### 🔐 On-Chain Fairness
- Solidity smart contracts (via Hardhat) handle market logic and resolution, triggered by authorized AI LLPs.
- No centralized authority — just the HLP/LLP system orchestrating interactions with immutable code.

### 💰 Tokenized Ecosystem
- Support for ERC20 tokens including community coins.
- Contract: [`PrediX`](https://sepolia.basescan.org/token/0xe21835fbe4df83a02d72a717fd8bc1dcbcc6c042)
- txHash : https://sepolia.basescan.org/tx/0x811adf8ab6ec754dfc8c2eb601dc4851e18557e59b374c5c3f90d11e08e353b1

### 🛠️ Embedded Wallet Onboarding
- Non-crypto users can onboard via embedded wallets.
- Optional top-up via swaps (1inch Aggregator API) and fiat ramps (coming soon). AI LLPs can potentially assist in guiding users through these processes.

---

## 💸 Business Model – PvP Prediction Platform

Predix is designed with a sustainable, scalable revenue model that grows alongside user activity and community engagement.

### 1. Platform Fee from Each Game
- A **customizable fee (default 3%)** is taken from the total wager pool of each game.
- This fee ensures long-term platform sustainability without relying on external funding.

> 🟢 **Example**: In a 100 USDC game, 3 USDC goes to the platform, and 97 USDC is distributed to the winner(s).

- Transparent fee logic handled entirely on-chain, potentially monitored or verified by an AI LLP for reporting.
- Scales naturally with prediction volume and user participation.

### 2. Featured Prediction Listings (Coming Soon)
- **Creators, KoLs, or token projects** can pay to highlight their games.
- Featured games appear in:
  - Homepage spotlight
  - Leaderboards
  - Integrated Twitter (X) feed via Blink (Potentially managed by an AI LLP interacting with Twitter APIs).

> 💡 Fees accepted in USDC or ecosystem/partner tokens.

- Helps communities **showcase their tokens in real-world prediction use cases**.
- Opens doors for **cross-project collaboration and co-marketing**.

### 3. Optional Add-Ons (Monetization Expansion)
- **Branded Tournaments**:
  - Run sponsored competitions with co-funded prize pools.
  - Partner with DAOs, sports brands, or gaming communities. AI LLPs could assist in tournament setup and management.

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
- Creators drive engagement and monetize audience, potentially leveraging AI tools for market creation.

### 🤖 AI + Real-Time Data = The Future
- AI agents resolve, and explain prediction markets autonomously.
- Reduces manual admin, speeds up resolution, and enhances user experience compared to traditional or less automated platforms.

---

## 🧱 Tech Stack

| Layer | Tech |
|--------------|------|
|**Chain** | Base
|
| **Smart Contracts** | Solidity + Hardhat
|
| **Oracles** | [`api-sports.io`](https://api-sports.io/), [`OKX Wallet`](https://www.okx.com/wallet-api)
|
| **Wallet/Swap** | Embedded wallets + 1inch Aggregator API
|
| **Tokens** | ERC20 (e.g., USDC, PrediX token) |
| **AI** | GAME |
| **AI models** | Llama-3.1-405B |


---

##
🔐 Governance & Security

- AI-based resolution verification + oracle fallback.
- Smart contract immutability ensures fairness.
- Regular audits and community governance.
- Wallet protection & withdrawal guardrails for safety.

---

## 🤝 Contribute

We welcome contributors! Open issues, suggest features, or submit a pull request. Help shape the future of AI-powered PvP markets using advanced agent architectures.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

