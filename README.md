# ReliefChain — Blockchain-Based Disaster Relief Fund Tracking System

**Every Donation. Every Transaction. Accountable.**

ReliefChain is a Blockchain Technology project designed to improve transparency, accountability, and traceability in disaster relief funding. It provides a platform to track donations, monitor fund allocation, review expenses, and maintain an auditable history of relief activities.

## 🌐 Live Demo

[**Demo Link**](https://reliefchain-blockcha-chx8.bolt.host/)

## 📌 Project Overview

During natural disasters, donations and relief funds must be managed efficiently and transparently. Traditional fund-tracking systems can make it difficult for donors and auditors to independently verify how funds are allocated and utilized.

ReliefChain proposes a blockchain-based approach to maintain tamper-evident records of donations, allocations, expense approvals, and relief deliveries. It aims to make financial activities easier to trace and audit.

## 🎯 Objectives

- Improve transparency in disaster relief fund management.
- Track donations from donors to relief campaigns.
- Monitor fund allocation and expenditure.
- Maintain auditable transaction records.
- Support authorized expense verification and approval.
- Detect duplicate transaction references and suspicious records.
- Provide public visibility into campaign progress and fund utilization.

## ✨ Key Features

- **Campaign Management:** View and manage disaster relief campaigns.
- **Donation Tracking:** Record donations and maintain donation histories.
- **Fund Allocation:** Monitor the allocation of funds to approved relief activities.
- **Expense Management:** Submit and review expense records with supporting evidence.
- **Transparency Dashboard:** Visualize donations, allocations, expenditures, and balances.
- **Role-Based Access:** Separate interfaces for donors, relief organizations, administrators, and public viewers.
- **Blockchain Explorer:** Display transaction records and their verification status.
- **Dispute Management:** Flag and review disputed financial records.
- **Relief Delivery Tracking:** Record milestones associated with relief distribution.
- **Demo Mode:** Explore the application's sample data and interactive features.

## 👥 User Roles

| Role | Responsibilities |
|---|---|
| Donor | Explore campaigns, make demo donations, and track contributions. |
| Relief Organization | Manage campaigns, request fund allocations, and submit expenses. |
| Administrator / Auditor | Review campaigns, verify expenses, and monitor records. |
| Beneficiary / Public Viewer | View public campaigns, fund utilization, and relief milestones. |

## 🔄 How It Works

1. **Create Campaign:** A relief organization submits a disaster relief campaign.
2. **Verify Campaign:** An administrator reviews the campaign.
3. **Collect Donations:** Donors contribute to approved campaigns.
4. **Allocate Funds:** Funds are assigned to authorized relief activities.
5. **Submit Expenses:** Organizations record expenditure details and supporting evidence.
6. **Review Expenses:** Authorized administrators approve or reject submitted expenses.
7. **Track Relief Delivery:** Relief distribution milestones are recorded.
8. **Audit Records:** Users can inspect permitted records and transaction histories.

## 🛠️ Technology Stack

The proposed technology stack includes:

- **Frontend:** React, TypeScript, and Vite
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Icons:** Lucide React
- **Charts:** Recharts
- **Routing:** React Router
- **Backend:** Node.js and Express, if configured
- **Database:** Supabase or another configured persistence solution
- **Blockchain:** Ethereum-compatible blockchain
- **Smart Contracts:** Solidity
- **Development and Testing:** Hardhat
- **Blockchain Interaction:** ethers.js

*Note: The technologies listed describe the proposed stack. Actual integration depends on the implementation deployed in the live demo.*

## 🏗️ System Architecture

The proposed system follows this architecture:

```text
Donors / Organizations / Administrators / Public
                         |
                         v
              React + TypeScript UI
                         |
                         v
                Backend / API Layer
                         |
                         v
             Validation and Permissions
                         |
                         v
               Solidity Smart Contract
                         |
                         v
             Ethereum-Compatible Network

       Database and Secure Document Storage
             Support Application Data
```

The blockchain can store transaction records and document hashes, while private documents and application-specific information remain in secure off-chain storage.

## 🔐 Security and Transparency

ReliefChain is designed around the following principles:

- Role-based access control.
- Input validation and duplicate-reference checks.
- Controlled campaign and expense approvals.
- Secure handling of private documents.
- Auditable records of important actions.
- Clear identification of simulated and verified blockchain transactions.

Blockchain provides tamper-evident records, but it cannot independently guarantee that submitted expenses or physical relief deliveries are genuine. Independent verification is still necessary.

## 🧪 Demo Data

The application may use fictional sample campaigns involving:

- Andhra Pradesh flood relief.
- Coastal cyclone relief.
- Earthquake emergency response.
- Wildfire recovery.

Sample financial figures, organizations, and beneficiaries are illustrative and should not be interpreted as real donations or actual relief activities.

**Demo Mode:** Transactions marked “Simulated — Not On-Chain” are application demonstrations, not confirmed blockchain transactions.

## 🚀 Getting Started

To run the project locally, first clone or download the source code from the project repository.

### Prerequisites

- Node.js
- npm
- Git

### Installation

```bash
# Clone your repository
git clone <YOUR_GITHUB_REPOSITORY_URL>

# Navigate into the project folder
cd <YOUR_PROJECT_FOLDER>

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open the local URL printed in your terminal, usually `http://localhost:5173`.

*Replace the placeholders with your actual GitHub repository URL and project folder name. These instructions assume the source code uses a standard Vite setup.*

### Environment Configuration

If the application uses external services, create a `.env` file based on the project's environment requirements.

Never commit private keys, passwords, API secrets, or database service-role credentials to GitHub.

## 🔮 Future Enhancements

- Integration with real donation payment gateways.
- Deployment and verification of smart contracts on a blockchain testnet.
- Secure digital identity verification for relief organizations.
- Integration with official disaster relief agencies.
- Mobile application for donors and relief workers.
- Automated anomaly detection for suspicious transactions.
- Enhanced reporting and downloadable audit records.

## 🎓 Project Information

- **Project Name:** ReliefChain
- **Domain:** Blockchain Technology
- **Category:** Disaster Relief Fund Management
- **Project Type:** Academic Demonstration
- **Primary Goal:** Transparent and auditable disaster relief fund tracking

## 📚 References

- [Ethereum Documentation](https://ethereum.org/en/developers/docs/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [Hardhat Documentation](https://hardhat.org/docs)
- [ethers.js Documentation](https://docs.ethers.org/)


---

**ReliefChain — Building Trust Through Transparency.**
