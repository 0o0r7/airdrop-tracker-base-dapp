# AirdropTracker Base Dapp - Setup Guide

## Project Overview

AirdropTracker is a Mini Dapp on Base Layer 2 for tracking and managing airdrop campaigns with social gating and reward mechanisms.

## Technology Stack

- **Frontend:** Next.js 14, React 18, TypeScript
- **Styling:** Tailwind CSS
- **Web3:** Wagmi, Viem, OnchainKit
- **Blockchain:** Base Layer 2 (Sepolia Testnet)

## Installation & Setup

### Prerequisites
- Node.js 18+
- npm or yarn
- Git
- Wallet with Base testnet funds (Sepolia)

### Step 1: Clone Repository
```bash
git clone https://github.com/0o0r7/airdrop-tracker-base-dapp.git
cd airdrop-tracker-base-dapp
```

### Step 2: Install Dependencies
```bash
npm install
# or
yarn install
```

### Step 3: Environment Setup
Create `.env.local` file:
```
NEXT_PUBLIC_BASE_RPC_URL=https://sepolia.base.org
NEXT_PUBLIC_CHAIN_ID=84532
NEXT_PUBLIC_WALLET_CONNECT_ID=YOUR_WALLET_CONNECT_ID
```

### Step 4: Run Development Server
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
/app                    # Next.js app directory
/components             # React components
/contracts              # Solidity smart contracts
/public                 # Static files
/styles                 # Tailwind CSS config
/hooks                  # Custom React hooks
/utils                  # Utility functions
/types                  # TypeScript type definitions
```

## Development Roadmap

1. **Phase 1:** Airdrop tracking & user profiles
2. **Phase 2:** Smart contracts & token gating
3. **Phase 3:** Notification system & reminders
4. **Phase 4:** Leaderboards & gamification
5. **Phase 5:** Testnet deployment

## Building & Deployment

### Build for Production
```bash
npm run build
npm run start
```

### Deploy to Vercel
```bash
vercel
```

## Contributing

Please follow the existing code style and create feature branches for new work.

## License

MIT License - See LICENSE file for details.
