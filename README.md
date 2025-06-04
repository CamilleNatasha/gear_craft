⚔️ GearCraft — Modular In-Game Item System dApp

**GearCraft** is a decentralized application (dApp) that empowers players to **craft, upgrade, and trade modular in-game items** (like swords with customizable blades and hilts). It leverages:

**ERC721** for unique base items
**ERC1155** for stackable components
**EIP-4626** for yield-generating staking via the Forge

---

## 🔧 Tech Stack

**Frontend**: React + Vite + TailwindCSS
**Smart Contracts**: Solidity using Hardhat
**Blockchain**: Compatible with Base, zkSync, and other EVM chains
**Wallet Integration**: Ethers.js + Radix UI + MetaMask
**Gasless UX**: Optional integration with Xsolla ZK or Paymasters

---

## 🧪 Commands

To get started with the backend (smart contracts):

```bash
npx hardhat help                # View all available Hardhat tasks
npx hardhat test                # Run contract tests
REPORT_GAS=true npx hardhat test  # Run tests with gas reporting
npx hardhat node                # Start a local Hardhat node
npx hardhat run scripts/deploy.ts --network localhost  # Deploy locally
