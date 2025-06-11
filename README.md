# 💰 CrowdMint – A Blockchain-Based Crowdfunding Platform

A decentralized crowdfunding platform built on Ethereum that enables users to raise and contribute funds transparently with smart contract logic and community-driven withdrawal approvals.

---

## 🚀 Project Features – CrowdMint 💰

- **Start Fundraising**: Users can create a fundraising campaign by setting a funding goal and deadline.
- **Contribute to Campaigns**: Any user with a connected wallet can contribute to active crowdfunding campaigns.
- **Auto-End on Success**: Campaigns automatically end if the target funding amount is successfully raised.
- **Auto-Expire on Deadline**: If the goal isn’t met by the set deadline, the campaign expires.
- **Fund Withdrawal Request**: Campaign creators can request to withdraw raised funds.
- **Contributor Voting System**: Contributors can vote to approve or reject the fund withdrawal request.
- **Majority Approval for Withdrawal**: At least 50% approval from contributors is required for the creator to access the funds.
- **MetaMask Integration**: Seamless wallet connection and transaction signing using MetaMask.

---

## 🛠️ Tech Stack & Packages Used

| Package           | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Next.js**       | React-based framework for building the frontend                            |
| **Solidity**      | Smart contract language for implementing blockchain logic                  |
| **Tailwind CSS**  | Utility-first CSS framework for responsive UI design                       |
| **Ethers.js**     | Web3 client library used for backend contract deployment & interaction     |
| **Web3.js**       | Web3 client used in frontend for user interaction with smart contracts     |
| **React-Toastify**| For displaying real-time toast notifications in the UI                     |
| **Hardhat**       | Development environment for compiling, testing, and deploying contracts     |
| **Redux**         | Centralized state management for frontend components                       |

---

##  How to Run the Project

### Start the Local Ethereum Node
```
npm install
npx hardhat node
```
### Deploy Contract to Localhost Network
```
npx hardhat run scripts/deploy.js --network localhost
```
### Run the Frontend (Next.js)
```
cd client
npm install
npm run dev
```
Photos
![Connect Metamask](Photos/ConnectMetamask.png)
![CrowdMint Home Page](Photos/HomePage.png)
![Fund Raiser Form](Photos/FundRaiserForm.png)
![Contribution Progress](Photos/ContributionProgress.png)
![Contribution List](Photos/ContributionList.png)
![Voting Mechanism](Photos/VotingMechanismforContribution.png)
![Creator Withdraw](Photos/WithdrawforCreator.png)
![Successful Withdraw](Photos/Withdrawsuccessful.png)

