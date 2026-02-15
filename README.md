# PayStream - Continuous Salary Streaming with Smart Contracts

PayStream is a decentralized platform enabling continuous, on-demand salary streaming between employers and employees. Built with Solidity smart contracts, Express.js backend, and React frontend with advanced UI components.

## Project Structure

```
paystream/
├── backend/          # Hardhat project + Express API
│   └── contracts/    # PayStream.sol smart contract
└── frontend/         # React + Vite application
    └── src/          # React components and pages
```

## Quick Start

### Backend Setup
```bash
cd backend
npm install
cp .env.example .env
npx hardhat compile
npm run deploy
npm start
```

### Frontend Setup
```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

## Features

- **Continuous Salary Streaming**: Real-time salary flow to employees
- **Live Balance Ticker**: Server-Sent Events (SSE) for real-time balance updates
- **3D Interactive UI**: Spline background with Three.js and particle effects
- **Responsive Design**: Tailwind CSS with parallax scroll animations (GSAP)
- **Wallet Integration**: MetaMask and HeLa chain support

## Technologies

- **Smart Contracts**: Solidity, Hardhat
- **Backend**: Express.js, Node.js
- **Frontend**: React, Vite, Tailwind CSS, GSAP, Three.js
- **Blockchain**: Ethereum-compatible networks
