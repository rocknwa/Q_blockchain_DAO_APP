# Q_blockchain_DAO_APP

A decentralized autonomous organization (DAO) application for managing proposals, voting, and execution on a blockchain. This repository contains the smart contracts, deployment scripts, and a web interface to interact with the DAO.

## About
Q_blockchain_DAO_APP is a DAO platform that lets token holders create proposals, vote, and (optionally) execute actions when proposals pass. The app is intended to be modular so you can extend governance rules, add multiple token types, and plug in off-chain services.

## Features
- Create proposals
- Token-weighted voting (on-chain)
- Execution of successful proposals (on-chain)
- Local development and automated testing for smart contracts

## Architecture
- Smart contracts: Solidity (Hardhat) — contains the DAO, governance, and token contracts.
- Scripts: Deployment and management scripts using Hardhat.
- Tests: Unit tests for contracts

## Quick start

### Prerequisites
- Node.js >= 16
- npm or yarn
 
### Clone and install
```bash
git clone https://github.com/rocknwa/Q_blockchain_DAO_APP.git
cd Q_blockchain_DAO_APP
npm install
```

### Environment variables
Create a `.env` from `.env.example` and fill in the values
 
> Never commit real private keys or secrets to version control. Use a vault or CI secrets for production.

