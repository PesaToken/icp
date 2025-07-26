# 🪙 PesaToken – Crypto Utility Infrastructure for Africa

PesaToken is a crypto utility platform designed to bridge the gap between digital assets and real-world financial use cases. It enables users and businesses to interact with crypto in practical ways—such as funding accounts, making payments, and receiving digital payouts—via a seamless, multilingual, and mobile-friendly interface.

> 🚀 Mainnet MVP: [https://duka.pesatoken.org](https://duka.pesatoken.org)  
> 🧪 Local Canister: [`umunu-kh777-77774-qaaca-cai`](http://127.0.0.1:4943/dashboard?canisterId=umunu-kh777-77774-qaaca-cai)

---

## 🔧 Key Features

### 🌍 Web3 Onboarding & Wallet Connectivity
- Supports leading EVM-compatible wallets: MetaMask, Trust Wallet, Coinbase Wallet, Phantom (EVM).
- Unified onboarding experience using Reown Modal.
- Wallet state persistence and reconnect handling.

### 💳 Crypto Funding & Checkout
- Fund platform accounts using ETH or USDT from connected wallets.
- Coinbase-hosted checkout integration for fiat-to-crypto conversions.
- Dynamic transaction validation, max balance utility, and explorer links for transparency.

### 📨 Messaging & Notifications
- Secure, end-to-end encrypted messaging via XMTP.
- Support for direct user communication and automated transaction alerts.

### 🧠 Multilingual User Experience
- UI support for major African languages (Swahili, Kikuyu, Yoruba, Hausa, Zulu, etc.).
- Language preferences are saved per user and reflected across the experience.
- Integration with translation APIs for educational and transactional content.

### 🏦 Business & Merchant Use
- Merchant wallets capable of receiving payments in crypto (e.g., USDT, ETH).
- Multi-sig control and API integration for business payment routing (e.g., DurraFX).
- Dashboards and contract alerts for cross-border businesses.

---

## 🛠️ Local Development

### Prerequisites
- `dfx` CLI installed (`dfx version` >= 0.17.0)
- Node.js (v18+ recommended)
- Internet Computer local replica running:  
  ```bash
  dfx start --background

  cd frontend
  npm install
  npm run build
  cd ..

  dfx deploy

