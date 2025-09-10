# Simple NFT Example

A decentralised application (dApp) for creating, minting, and transferring NFTs built on Ethereum using Scaffold-ETH 2.

## What is this?

This is an NFT (Non-Fungible Token) marketplace application that allows users to:

- **Mint NFTs**: Create unique digital collectibles
- **View NFTs**: Browse your collection of owned NFTs  
- **Transfer NFTs**: Send NFTs to other wallet addresses
- **Interactive UI**: Easy-to-use web interface for all NFT operations

## Tech Stack

- **Frontend**: Next.js with TypeScript
- **Blockchain**: Ethereum (local development and testnets)
- **Smart Contracts**: Solidity
- **Web3 Integration**: RainbowKit, Wagmi, Viem
- **Development Framework**: Scaffold-ETH 2

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (>= v20.18.3)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation & Setup

1. **Start local blockchain**:
   ```bash
   yarn chain
   ```

2. **Deploy contracts** (in a new terminal):
   ```bash
   yarn deploy
   ```

3. **Start the frontend** (in a new terminal):
   ```bash
   yarn start
   ```

4. **Open the app**: Navigate to [http://localhost:3000](http://localhost:3000)

## Features

- **Burner Wallets**: Test the app instantly with temporary wallets
- **Local Faucet**: Get test ETH for transactions
- **Contract Debugging**: Built-in tools to interact with smart contracts
- **Responsive Design**: Works on desktop and mobile devices

## Smart Contract

The main smart contract `YourCollectible.sol` handles:
- NFT minting functionality
- Ownership tracking
- Transfer operations
- Metadata management

## Deployment

The app can be deployed to:
- **Testnets**: Sepolia, Goerli
- **Mainnet**: Ethereum mainnet
- **Frontend**: Vercel, IPFS

## Project Structure

```
packages/
├── hardhat/          # Smart contracts and deployment scripts
│   ├── contracts/    # Solidity contracts
│   └── deploy/       # Deployment scripts
└── nextjs/           # Frontend application
    ├── app/          # Next.js pages
    └── components/   # React components
```

---

Built with [Scaffold-ETH 2](https://scaffoldeth.io) - A toolkit for building decentralised applications on Ethereum.