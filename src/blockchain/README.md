# Blockchain Integration

This directory contains smart contracts and scripts for blockchain interactions within AI Battle Arena.

## Smart Contracts:
- **arena_contract.sol** - Handles in-game transactions and reward distributions.
- **governance_contract.sol** - Supports decentralized governance through DAO.

## Deployment Process:

To deploy smart contracts, follow these steps:

1. Install dependencies:

```bash
npm install
truffle compile
truffle migrate --network mainnet
