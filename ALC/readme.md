# AliCoin - A Simplified Blockchain Simulation

## Introduction
AliCoin is a lightweight cryptocurrency simulation designed to demonstrate fundamental blockchain concepts using Proof-of-Work (PoW). This project implements a functional blockchain with key features such as account management, transaction handling, mining, and Merkle Tree-based transaction verification.

## Features
- **Blockchain Structure**: Implements an immutable chain of blocks linked via cryptographic hashes.
- **Genesis Block**: The first block in the chain, created dynamically when necessary.
- **Accounts**: User accounts with balances and transaction history.
- **Transactions**: Secure and validated peer-to-peer transactions.
- **Merkle Tree**: Ensures transaction integrity within blocks.
- **Miners**: Simulated mining entities with computational resources.
- **Proof-of-Work**: A PoW-based mining mechanism with difficulty adjustments and mining rewards.

## Technical Implementation

### 1. Blockchain Structure
Each block in AliCoin contains:
- A **list of validated transactions**.
- A **reference to the previous block’s hash** (ensuring immutability).
- A **nonce** obtained through PoW.
- A **Merkle Root** derived from the transaction data.

### 2. Genesis Block
- The blockchain starts with a **Genesis Block**.
- It is created dynamically when the blockchain is empty and pending transactions exist.
- Uses a predefined `previous_hash` of "0".

### 3. Accounts
Each account has:
- `id`: A unique identifier.
- `balance`: The available AliCoin funds.
- `transactions`: A history of transactions.

Transactions update balances atomically, preventing race conditions.

### 4. Transactions
Each transaction consists of:
- `sender` and `recipient`: Unique IDs of the transacting parties.
- `amount`: The amount transferred.
- `id`: A unique transaction identifier.
- `timestamp`: A UNIX timestamp for transaction creation.

Validation ensures:
- The sender has a sufficient balance.
- Invalid transactions are rejected before processing.

### 5. Merkle Tree
- Used to generate a **Merkle Root**, a single cryptographic hash representing all transactions within a block.
- Enhances transaction integrity and security.

### 6. Miners
- Special accounts with a **randomly initialized computational power (`resources`)**.
- Higher computational power increases the likelihood of successful mining.

### 7. Mining and Proof-of-Work
AliCoin employs a Proof-of-Work (PoW) system where miners:
1. Construct a **block header** containing:
   - `previous_hash`
   - `merkle_root`
   - `timestamp`
   - `difficulty`
   - `nonce`
2. Search for a **nonce** such that the hash meets the difficulty target.
3. The first miner to solve the PoW puzzle **receives a reward of 10 AliCoins (10 @)**.
