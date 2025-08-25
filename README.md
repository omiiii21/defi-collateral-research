# Symbiotic DefaultCollateral Protocol: Mechanics & Indexing

A research and development project exploring the **Symbiotic protocol's DefaultCollateral contracts** on Ethereum.  
This repo analyzes the mechanics of **deposit/withdraw functions**, indexes deployed contract instances from the factory, and simulates collateral interactions off-chain.

---

<img width="953" height="497" alt="image" src="https://github.com/user-attachments/assets/ebd60d1c-b713-49c5-b987-237e9be657c5" />

## 📌 Overview

This project was designed as a structured assessment to demonstrate:

1. **Theoretical Understanding**  
   - Mechanics of the `deposit` and `withdraw` functions in Symbiotic’s `DefaultCollateral` contract.  
   - Input/output token flows and key balance tracking logic.  
   - Restrictions or conditions affecting collateral withdrawals.  

2. **Indexing the Factory Contract**  
   - Fetch all deployed `DefaultCollateral` contracts from the `DefaultCollateralFactory`.  
   - Extract deposit and withdrawal tokens for each deployed contract.  
   - Handle on-chain queries using RPC (e.g., Infura).  

3. **Off-Chain Simulation**  
   - Implemented `deposit` and `withdraw` functions in Python/TypeScript (your choice).  
   - Calculate output amounts based on conversion logic.  
   - Provide a sandbox for testing collateral mechanics without deploying on-chain.  

---

## 🛠️ Tech Stack

- **Solidity (EVM contracts reference)**  
- **Python / Web3.py** for off-chain indexing & simulation  
- **Infura RPC** for Ethereum mainnet queries  
- **Node.js / Ethers.js** (optional) for contract interactions  

---

## 🔍 References

- [Symbiotic Docs](https://docs.symbiotic.fi/)  
- [Current Deployments](https://docs.symbiotic.fi/deployments/current/)  
