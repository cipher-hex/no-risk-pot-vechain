### **Project Overview**

**No Risk Pot** is an innovative **DeFi lottery platform** built on **VeChain**, introducing a **no-loss lottery** system where participants can enjoy the thrill of winning without ever losing their principal investment.

#### **How It Works**

Participants purchase lottery tickets using **COIN (a stablecoin)**. The collected funds are then pooled and deployed into VeChain-based liquidity pools or yield-generating strategies through smart contracts. The **interest earned** from these investments is used to fund the lottery prizes, while each participant receives back their **original ticket amount**, ensuring a **zero-risk experience**.

#### **Prize Distribution**

- 🥇 **1st Prize:** 50% of total interest earned
- 🥈 **2nd Prize:** 30% of total interest earned
- 💼 **Platform Fee:** 20% of the interest earned goes to the platform owner

This model ensures transparency, fairness, and sustainability while making DeFi participation fun and accessible.

#### **Why Blockchain (VeChain)?**

VeChain’s dual-token system **(VET & VTHO)** and **native smart contract efficiency** make it ideal for **low-cost transactions** and **traceable fund management**. Using VeChain’s transparency and immutability, users can verify ticket purchases, fund usage, and prize distributions directly on-chain, ensuring trust and accountability without intermediaries.

#### **Real-World Impact**

No Risk Pot encourages broader adoption of DeFi by removing the fear of loss—turning traditional gambling into a **sustainable, trustless savings and rewards system**. It promotes **financial inclusion** and **responsible participation** in decentralized finance while offering a verifiable and transparent entertainment model.

#### **Value Proposition**

- Zero-risk participation model — users never lose their investment.
- Transparent and automated prize distribution via VeChain smart contracts.
- Sustainable yield generation from liquidity strategies.
- Lower gas fees and carbon footprint due to VeChain’s efficient consensus model.

#### **Roadmap & Sustainability**

- **Phase 1:** Smart contract deployment and testnet launch on VeChain.
- **Phase 2:** Integration with VeChain’s yield-generating protocols.
- **Phase 3:** Launch of mainnet version with community governance.
- **Phase 4:** Expansion into multi-chain yield aggregation while maintaining VeChain as the primary chain.

The business model is designed for **long-term sustainability**, with platform fees reinvested into marketing, yield optimization, and ecosystem growth.

---

## 🖼️ Project Screenshots

### 🏠 Home Page

**Home Page - View 1**  
![Home Page - View 1](./frontend/public/home1.png)

**Home Page - View 2**  
![Home Page - View 2](./frontend/public/home2.png)

**Home Page - View 3**  
![Home Page - View 3](./frontend/public/home3.png)

### 🎟️ Buy Ticket Page

**Buy Ticket using COIN**  
![Buy Ticket - Step 1](./frontend/public/buy_tkt.png)

### 🛠️ Admin Dashboard

**Admin Page - view-1**  
![Admin Page - Lottery Overview](./frontend/public/adminpage1.png)

**Admin Page - view-2**  
![Admin Page - Manage Tickets](./frontend/public/adminpage2.png)

**Admin Page - view-3**  
![Admin Page - Winners List](./frontend/public/adminpage3.png)

### 💰 Claim Fund Page

**Claim Fund Page**  
![Claim Fund Page](./frontend/public/claim_fund_page.png)

## Project Structure

```
frontend/
├── public/
│   ├── index.html
│   └── *.png (screenshots)
├── src/
│   ├── App.js
│   ├── index.js
│   ├── components/
│   │   └── NetworkError.js
│   ├── pages/
│   │   ├── Home.js
│   │   ├── BuyTickets.js
│   │   ├── AdminPanel.js
│   │   └── ClaimFunds.js
│   ├── styles/
│   │   ├── Home.css
│   │   ├── BuyTickets.css
│   │   ├── AdminPanel.css
│   │   ├── Navbar.css
│   │   └── NetworkError.css
│   └── artifacts/
│       └── addresses.json
├── package.json
├── pnpm-lock.yaml
└── README.md
```

## 🚀 How to Run the Frontend

### Prerequisites

- Node.js 18 LTS recommended
- npm or pnpm
- MetaMask (or a compatible EVM wallet)

### Steps

1. Install dependencies

   ```bash
   npm install
   # or
   pnpm install
   ```

2. Start the development server

   ```bash
   npm start
   # or
   pnpm start
   ```

3. Open http://localhost:3000 in your browser.

### Network

- We have tried very hard to deploy on the vechain testnet and mainnet but due to technical errors we were not able to deploy on the vechain testnet and mainnet. So we have deployed the dApp on the Avax Fuji Testnet. If you are on another network, the app will prompt you to switch or add the network automatically.
- You may need some test COIN on Avax Fuji Testnet to perform transactions.

## 📜 Deployed Contracts (Avax Fuji Testnet)

Contracts are already deployed. You can verify them on the explorer below:

- Coin: `0xd2Cab77F7A111f77b2113Fb3CA5824db535D63e3`
- ZeroLossLottery: `0x5e6c03E14002aF759680cd86ad4534D4b8FA0648`

> Note: The frontend reads addresses from `frontend/src/artifacts/addresses.json`.

## Security Considerations

- Always ensure your `.env` files are included in `.gitignore`
- Never commit sensitive keys or secrets to version control
- Use a dedicated development wallet with limited funds for testing
- Consider using a hardware wallet for production deployments
