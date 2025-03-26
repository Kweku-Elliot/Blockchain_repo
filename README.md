# 🚀  Blockchain_repo
This repository contains **starter templates** for Ethereum and Solana smart contracts. Ideal for developers looking to quickly deploy and experiment with blockchain projects.  

---

## 📂 Project Structure
```
blockchain-boilerplate/
│── contracts/
│   └── NEBIX.sol  # Ethereum ERC-20 contract
│── solana/
│   └── Terin.rs   # Solana Rust contract
│── README.md
```

---

## 🔥 Ethereum: ERC-20 Token Contract  
📌 **File:** `contracts/NEBIX.sol`  
📌 **Language:** Solidity  
📌 **How to Deploy:**  
1. Install [Remix](https://remix.ethereum.org/) or use Hardhat.  
2. Compile with Solidity 0.8+  
3. Deploy on Ethereum testnet using MetaMask.  

---

## 🔥 Solana: Basic Rust Contract  
📌 **File:** `solana/Terin.rs`  
📌 **Language:** Rust  
📌 **How to Deploy:**  
1. Install Solana CLI:  
   ```sh
   sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
   ```
2. Create a Solana program:  
   ```sh
   cargo new my-solana-program --lib
   ```
3. Replace `lib.rs` with `MyToken.rs`.  
4. Build & Deploy using:  
   ```sh
   cargo build-bpf
   solana program deploy ./target/deploy/my_solana_program.so
   ```

---

## 📫 Contact Me  
💻 GitHub: [github.com/Kweku-Elliot](https://github.com/Kweku-Elliot)  
🐦 Twitter/X: [@ElliotElikplim](https://twitter.com/ElliotElikplim)  
💬 Telegram: [@ElliotCEO](https://t.me/ElliotCEO)  

🚀 **Let's build the future of blockchain together!**  


