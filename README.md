https://1drv.ms/i/c/f8399c854efe0c54/IQAr4UgtuE6rRLIeCgcYcTuuAYi6QIS2Oh1SEMUcJXfXqC0?e=2Ynxe5


# 🪙 NFT Fractionalization on Stellar (Soroban)

## 📌 Project Description

This project implements a basic NFT Fractionalization smart contract using Soroban on the Stellar network. It allows a single NFT to be divided into multiple fungible shares, enabling multiple users to co-own a high-value digital asset.

The goal is to improve accessibility and liquidity in NFT markets by lowering the barrier to entry for ownership.

---

## ⚙️ What it does

- Locks an NFT inside a smart contract
- Mints fractional shares representing ownership of that NFT
- Allows users to transfer shares between accounts
- Tracks ownership balances on-chain

Each share represents partial ownership of the NFT.

---

## ✨ Features

- 🔐 NFT ownership secured via smart contract
- 🧩 Fractional ownership (ERC20-like behavior)
- 🔄 Transferable shares between users
- 📊 On-chain balance tracking
- ⚡ Built using Soroban (Stellar smart contracts)

---

## 🏗️ How it works

1. Contract is initialized with:
   - NFT metadata
   - Owner address
   - Total number of shares

2. All shares are initially assigned to the owner

3. Owner can distribute shares to other users

4. Users can transfer shares freely

---

## 🔗 Deployed Smart Contract Link

(https://stellar.expert/explorer/testnet/contract/CBKEQBGLMKFUYAI3HEBEZBCQH2KCVAWC5YXDR7MP6RXTNW5RN7J5D3IM)

---

## 🚀 Future Improvements

- Marketplace for trading shares
- Buyout mechanism (full ownership claim)
- Governance (vote with shares)
- Integration with real NFT standards
- Royalties distribution

---

## 🛠️ Tech Stack

- Rust
- Soroban SDK
- Stellar Blockchain

---

## 📄 License

MIT License
