# **Blockchain Smart Contract Deployment and Interaction 🚀**  

This project demonstrates how to **compile, deploy, and interact** with a Solidity smart contract using **Python and Web3.py**. The smart contract allows storing and updating a user's **age** and **name** on the Ethereum blockchain.  

## **📌 Features**  
- ✅ Write a **Solidity smart contract** to store and update user data  
- ✅ **Compile** the contract using `solcx`  
- ✅ **Deploy** the contract on **Base Sepolia Testnet**  
- ✅ **Read** and **update** contract data via Web3  

## **📂 Project Structure**  
- **`storage_contract.py`** – The Python script that compiles, deploys, and interacts with the contract  
- **`Storage.sol`** – The Solidity smart contract file  
- **`README.md`** – Documentation for the project  

## **🛠️ Prerequisites**  
Before running the script, ensure you have the following installed:  
- Python 3.x  
- Web3 (`pip install web3`)  
- solcx (`pip install py-solc-x`)  
- An Infura API key for connecting to Base Sepolia  

## **📜 Smart Contract Explanation**  
The Solidity contract:  
- Stores two variables: `age` and `name`  
- Provides functions to **retrieve** (`getAge`, `getName`) and **update** (`update`) these values  
- Uses a **constructor** to set initial values during deployment  

## **📌 Key Functions in `storage_contract.py`**  
- **Compile Solidity code** and extract **ABI & Bytecode**  
- **Connect to Base Sepolia Testnet** using Web3  
- **Deploy the contract** and obtain its address  
- **Read data** from the contract  
- **Update stored data** by sending transactions  

## **📢 Notes**  
⚠️ **Security Warning**: Never expose your **private key** in public repositories. Use `.env` files or a secure key management system.  
⚠️ This project **runs on the Base Sepolia testnet**, so **no real funds** are used.  
