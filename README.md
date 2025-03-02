# **Blockchain Projects Repository**

Welcome to the **Blockchain Projects Repository**! 🚀 This repository contains multiple blockchain-related projects, each demonstrating key concepts in cryptocurrency, Ethereum transactions, smart contract development, and blockchain analysis.

## **📂 Repository Structure**
This repository is organized into four main folders:

1. **ALI Coin** - A simplified blockchain simulation demonstrating Proof-of-Work (PoW) and fundamental blockchain mechanisms.
2. **Ethereum Transaction Analysis** - A data-driven analysis of Ethereum transactions over a one-week period.
3. **Sending Transactions** - A practical implementation of sending Ethereum transactions using Web3.py on the Base Sepolia testnet.
4. **Smart Contracts** - A project showcasing smart contract development, deployment, and interaction using Solidity and Web3.py.

---

## **🛠️ Prerequisites**
Before running any of these projects, ensure you have the following installed and set up:

- **Python 3.x**
- **Web3.py** (`pip install web3`)
- **solcx** (`pip install py-solc-x` for compiling Solidity contracts)
- **Infura Account & API Key** (for connecting to Ethereum networks)
- **MetaMask Wallet** (for managing Ethereum accounts and transactions)
- **Test ETH** on Base Sepolia (for running transactions and smart contract tests)

---

## **📜 Project Overviews**

### **1️⃣ ALI Coin - A Simplified Blockchain Simulation**
A lightweight cryptocurrency simulation that showcases the fundamental principles of blockchain, including transaction handling, Proof-of-Work mining, and Merkle Tree verification.

**Key Features:**

✅ Custom blockchain implementation with blocks linked by cryptographic hashes  
✅ Proof-of-Work (PoW) mining system with adjustable difficulty  
✅ Transaction validation and account management  
✅ Merkle Tree for transaction integrity  
✅ Dynamic Genesis Block creation  

---

### **2️⃣ Ethereum Transaction Analysis**
Analyzing real Ethereum transaction data from a one-week period (Nov 8-14, 2017). This project extracts insights on transaction volume, gas fees, block creation rates, and Ether price trends.

**Key Features:**

✅ Data loading and preprocessing from raw Ethereum transaction datasets  
✅ Aggregating and summarizing transaction statistics  
✅ Analyzing block creation rates and gas fees  
✅ Visualizing Ethereum price trends  

---

### **3️⃣ Sending Ethereum Transactions**
A Python-based implementation for sending Ethereum transactions on the **Base Sepolia** testnet using Web3.py.

**Key Features:**

✅ Connect to Base Sepolia via **Infura**  
✅ Create and sign Ethereum transactions using a **private key**  
✅ Send **0.01 ETH** to a recipient wallet  
✅ Ensure **replay protection** using chain ID  
✅ Retrieve transaction receipts for verification  

---

### **4️⃣ Smart Contract Deployment & Interaction**
This project demonstrates how to write, deploy, and interact with **Solidity smart contracts** using Web3.py.

**Key Features:**

✅ Solidity contract to store and update user **name** and **age**  
✅ Compilation and deployment on **Base Sepolia**  
✅ Interaction via Web3.py (read/write operations)  
✅ Secure **contract execution** with proper validation  

---

## **⚠️ Security Notes**
🔒 **Never expose private keys** in public repositories. Use `.env` files or a secure vault.  

