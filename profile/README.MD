# Predix - AI-Powered PvP Prediction Market

## Overview
Predix is an AI-driven, prompt-based PvP prediction market built on the Base blockchain. The platform enhances reliability through decentralized smart contract logic, real-time oracle data, and AI-powered automation for market creation, resolution, and payouts. Predix enables users to create and participate in prediction markets seamlessly, leveraging Base’s high-speed, low-cost transactions.

---

## Key Features

### ✅ AI-Powered Prediction Markets
- AI agents automate market creation, answer selection, and resolution.
- Smart contracts ensure fair and transparent outcomes.
- Real-world data is retrieved from trusted API providers (e.g., `api-sports.io` for sports, OKX Wallet API for crypto).

### ✅ On-Chain Betting System on Base
- Users bet on predefined outcomes in a decentralized environment.
- All transactions are recorded on-chain, ensuring transparency.
- Market resolution is fully automated using AI and on-chain governance.

### ✅ Base-Optimized Trading & Wallet System
- Users deposit ETH into an embedded wallet to place bets.
- Integrated with Jupiter API for seamless swaps between Eth, altcoins, and meme coins.
- Future support for EVM asset top-up and cash-out solutions.

### ✅ SocialFi & Community Engagement
- **PnL NFT Cards**: Users can mint and share performance-based NFTs via Metaplex.
- **In-App Chat & Networking**: Social features powered by TalkJS or Sendbird.
- **Blink Integration for X (Twitter) Interaction**: Create and join markets directly from X.

### ✅ Fast, Feeless Transactions
- Users can place bets with minimal transaction fees thanks to Base’s low-cost architecture.
- Optimized for real-time, high-frequency trading.

### ✅ AI-Powered Prompt System
- Users can interact with the platform through natural language commands:
  - _"Create a prediction for the Man City vs Tottenham match next week. Bet 1 Eth on Tottenham."_
  - _"Show me ongoing predictions."_
  - _"Join the second prediction with 2 Eth."_
  - _"Create a BTC price up/down prediction, starting today at 12 PM UTC, resolution in 48 hours. Bet 2 ETh on UP."_
  - _"List ongoing predictions by highest bet."_
  - _"Show my winning predictions and claim all rewards."_

---

## How Predix Leverages Base

### 🔹 High-Speed Transactions
- Base’s high throughput enables real-time market creation and settlement.
- Low-latency transactions ensure instant bet placements and payouts.

### 🔹 Decentralized Smart Contracts
- Built with Hardhat, Base’s Solidity-based smart contract framework.
- Fully automated resolution process with immutable on-chain verification.

### 🔹 Tokenized Economy with Erc20 Tokens
- Users deposit and withdraw funds using Base’s Erc20 token standard.
- Rewards and payouts are distributed instantly without intermediaries.

### 🔹 Secure & Efficient Betting Mechanism
- Embedded wallets allow seamless onboarding for non-crypto users.
- Market outcomes are determined on-chain, ensuring fairness and transparency.

---

## Key Technologies
- **Programming Language**: Rust
- **Blockchain**: Base
- **Smart Contract Framework**: [Hardhat](https://github.com/NomicFoundation/hardhat/)
- **Oracles & APIs**:
  - [api-sports.io](https://api-sports.io/) (sports data)
  - [OKX Wallet API](https://www.okx.com/wallet-api) (crypto data)
- **Token Standards**:
  - ERc20 Token
  - 0xE21835FBE4Df83a02D72a717Fd8BC1dcBCC6C042

---

## Environment Setup
Ensure the following environment variables are configured:
```env
RPC_URL=<your_sol_rpc_url>
PREDIX_PROGRAM_ID=<your_predix_smart_contract_address>
```

---

## Governance & Security
### 🔹 Fair Play & Anti-Manipulation Measures
- AI verification for prediction integrity.
- Strict security policies to prevent market manipulation.

### 🔹 User Protection & Compliance
- Embedded wallet security mechanisms.
- Adheres to DeFi best practices for transparent financial operations.

### 🔹 Policy Updates & Community Governance
- Regular policy reviews based on user feedback.
- Transparent governance with community-driven updates.

---

## Business Model
Predix operates on a sustainable revenue model through transaction-based fees and SocialFi partnerships:

### 🔹 Market Resolution Fee
- A **3% fee** is deducted from the total payout of completed predictions to sustain platform operations.

### 🔹 SocialFi Engagement & Ads
- Sponsored prediction markets.
- In-app chat monetization through integrated promotions.

---

## Contribution
Contributions are welcome! Feel free to open issues and submit pull requests.

---

## License
This project is licensed under the MIT License.