# Algorand Project – Simple Token Wallet

## Overview
This repository contains my Algorand-based project for the course assignment.[page:1]  
The goal is to build a simple token wallet on the Algorand blockchain that lets a user create, view, and transfer a custom Algorand Standard Asset (ASA).[page:1]

## Project Idea
The project is a basic token wallet running on Algorand TestNet.  
It allows a user to:
- Create their own custom token (ASA)
- Check their account and token balance
- Transfer tokens to another Algorand address

This helps me learn Algorand accounts, transactions, and ASA operations in a practical way.

## Tech Stack
- Programming language: Python
- Algorand SDK: Algorand Python SDK
- Network: Algorand TestNet (or local Sandbox)
- Tools: Algorand Sandbox or TestNet node, AlgoExplorer for viewing transactions

## Features (Planned)
- Generate or configure an Algorand account for the wallet
- Create a custom Algorand Standard Asset (token)
- Check Algo and token balances
- Transfer tokens to another Algorand address

## Repository Structure
- `wallet/` – Python code for wallet operations (create asset, check balance, transfer)
- `scripts/` – Helper scripts for setup or testing
- `README.md` – Project documentation

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/algorand-simple-token-wallet.git
   cd algorand-simple-token-wallet
   ```
2. Create and activate a virtual environment (optional but recommended).
3. Install dependencies:
   ```bash
   pip install py-algorand-sdk
   ```
4. Configure Algorand network settings (TestNet or Sandbox) in a config file or environment variables.

## Usage
1. Make sure your Algorand account is funded on TestNet (using a TestNet faucet).
2. Run the script to create your custom token:
   ```bash
   python wallet/create_asset.py
   ```
3. Run the script to check balances:
   ```bash
   python wallet/check_balance.py
   ```
4. Run the script to transfer tokens:
   ```bash
   python wallet/transfer_token.py
   ```

Each script will print transaction IDs so they can be verified on AlgoExplorer.

## Course Notes
- This is an original public repository created specifically for my Algorand project and is not a fork.[page:1]  
- It will be used consistently throughout the course for meaningful project development commits, not empty or repetitive commits.[page:1]  
- The GitHub repository link for submission will point to this public repository as required by the assignment.[page:1]

## License
MIT License (or another license of your choice).
