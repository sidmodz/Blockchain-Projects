# **Blockchain Projects Repository**

Welcome to the **Blockchain Projects Repository**, a collection of blockchain-related projects demonstrating various aspects of cryptocurrency, Ethereum transaction analysis, smart contract development, and blockchain interactions. Each folder contains a specific project with detailed documentation, code implementation, and setup instructions.

## 📂 **Repository Structure**

### 1️⃣ **ALI Coin - A Simplified Blockchain Simulation**
A lightweight cryptocurrency simulation designed to showcase fundamental blockchain concepts. This project implements a functional blockchain using **Proof-of-Work (PoW)** and includes:
- **Immutable blockchain structure** with cryptographic hashing.
- **Transaction processing** and **Merkle Tree verification**.
- **Mining mechanism** with adjustable difficulty.
- **Genesis block creation** and **reward system**.
- **Account and transaction management**.


---

### 2️⃣ **Ethereum Transaction Analysis**
This project analyzes **Ethereum blockchain transactions** over a one-week period (Nov 8-14, 2017) using data from **Blockchair**. It provides insights into:
- **Transaction trends** and **block creation frequency**.
- **Transaction fees** and **gas usage statistics**.
- **Ethereum price trends** over time.
- **Daily and hourly transaction distribution**.

Includes data visualizations such as bar charts, histograms, and time series plots.

---

### 3️⃣ **Sending Transactions on Base Sepolia**
A hands-on guide to sending **Ethereum transactions** on the **Base Sepolia testnet** using **Web3.py**. Key functionalities include:
- **Connecting to the Base Sepolia network** via Infura.
- **Creating, signing, and broadcasting transactions**.
- **Ensuring replay protection** with proper chain ID.
- **Retrieving transaction receipts** after confirmation.

---

### 4️⃣ **Smart Contracts - Deployment & Interaction**
This project demonstrates how to **compile, deploy, and interact** with a Solidity smart contract using **Python and Web3.py**. Features include:
- **Writing a Solidity contract** to store and update user data.
- **Compiling the contract** with `solcx`.
- **Deploying the contract** on **Base Sepolia Testnet**.
- **Interacting with the contract** using Python scripts.


---

### **Prerequisites**
- Python 3.x
- Web3.py (`pip install web3`)
- Infura API Key (for Ethereum interactions)
- Solidity Compiler (`pip install py-solc-x`)

