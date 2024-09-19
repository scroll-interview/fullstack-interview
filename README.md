# Scroll Web Challenge

Welcome to the Scroll Simple Transfer DApp coding challenge! In this task, you will build a decentralized application (DApp) using Next.js, integrating with the Scroll Layer2 network. This challenge will test your ability to develop a fullstack DApp, including front-end UI and blockchain interaction.

## Task Overview

Your goal is to build a DApp with the following functionality:

- Users can connect their wallets (e.g., MetaMask).
- Display the user’s ETH balance on Scroll Layer2.
- Implement a simple transfer form that allows users to send ETH to a recipient’s address.
- Use a mock API to record the transfer history and display it on the front-end.

---

## 1. Task Requirements

- **Use Next.js** to create the project.
- Implement the application using **TypeScript**.
- Use **Ethers.js** or **Web3.js** to interact with the Scroll Layer2 network.
- **Frontend framework**: Use **React** (Next.js default) for the front-end.
- Create a **mock API** using the Next.js API routes feature to store and return transfer history.

### Application Features

#### Wallet Connection:

- Allow users to connect their wallet using MetaMask.
- Show the connected wallet’s address and allow the user to disconnect.

#### ETH Balance Display:

- Fetch and display the connected user's ETH balance on Scroll Layer2.

#### Transfer Form:

- Allow the user to input a recipient’s address and the amount of ETH to transfer.
- Validate input fields and handle errors (e.g., insufficient balance, invalid address).
- On successful transfer, display a confirmation message.

#### Transaction History:

- Store the transfer details (recipient address, amount, timestamp) in a mock backend using Next.js API routes.
- Display the transaction history on the front-end in a list format.

## 2. Submission Guidelines

1. **Git Workflow**:
   - Create a `develop` branch and make 2-3 meaningful commits. Use `rebase` to keep the commit history clean.
   - Once the feature is complete, submit a Pull Request from `develop` to `main`.

2. **Deliverables**:
   - The final submission should include the entire codebase along with a detailed README that includes:
     - Installation instructions.
     - How to run the project locally.
     - How to interact with the application.
     - Any other relevant information.

---

## 3. Bonus (Optional)

- Add additional UI/UX enhancements such as loading spinners during wallet connection or transaction submission.
- Implement a mobile-responsive design.
