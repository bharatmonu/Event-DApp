# Decentralized Event Management System (DApp)

This **Decentralized Event Management System (DApp)** leverages **React** and **Solidity** to offer a robust platform for managing events on the Ethereum blockchain. Users can perform operations such as creating, modifying, canceling, and viewing events through a seamless interface integrated with the MetaMask wallet.

---

## Key Features

- **MetaMask Wallet Integration**: Securely connect your MetaMask wallet to interact with Ethereum smart contracts.
- **Create Events**: Add new events with details like event ID, name, date, and a participant cap.
- **Modify Events**: Update event attributes, including the name, date, or registration limit.
- **Cancel Events**: Mark events as canceled by specifying their unique ID.
- **Manage Events**: Clear all events or refresh the list dynamically.
- **Event Overview**: View a comprehensive table of events showing ID, name, date, participant limits, and cancellation status.

---

## Prerequisites

Before proceeding, ensure you have the following tools installed:

- [Node.js](https://nodejs.org/) (for package management and development)
- [MetaMask](https://metamask.io/) (as a browser extension)
- [Hardhat](https://hardhat.org/) (Ethereum development framework)

---

## Setup Guide

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/bharatmonu/Event-DApp.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Event-DApp
   ```

3. **Install Required Dependencies**:
   ```bash
   npm install
   ```

---

### Running the DApp Locally

1. **Start a Local Ethereum Node**:
   Open a terminal and run:
   ```bash
   npx hardhat node
   ```

2. **Deploy the Smart Contract**:
   In a new terminal, deploy the contract:
   ```bash
   npx hardhat run --network localhost scripts/deploy.js
   ```

3. **Launch the Frontend**:
   Start the development server in another terminal:
   ```bash
   npm start
   ```

4. **Access the DApp**:
   Open your browser and navigate to:
   ```
   http://localhost:XXXX
   ```
   Connect your MetaMask wallet to start interacting with the application.

---

## User Interface Overview

The interface includes:

- **Event Details Form**: Fields for inputting event ID, name, date, and maximum participants.
- **Functional Buttons**:
  - `Add Event`: Registers a new event.
  - `Update Event`: Modifies an existing event.
  - `Cancel Event`: Marks an event as canceled.
  - `Clear All`: Deletes all registered events.
  - `Refresh`: Reloads the list of events.
- **Event Table**: A real-time display of all events with their statuses and details.

---

## Technology Stack

- **Solidity**: Backend smart contract logic.
- **React.js**: Frontend application framework.
- **MetaMask**: Wallet for Ethereum transactions.
- **Hardhat**: Development environment for deploying and testing contracts.

---

## Usage Instructions

1. Open the application and click **Connect Wallet** to link MetaMask.
2. Use the form to add, modify, or cancel events.
3. Manage all events effectively with options to clear, refresh, or cancel specific entries.
4. The event table will automatically update with real-time data.

---

## Error Handling

The DApp incorporates comprehensive error-handling mechanisms:

- Prompts users to install MetaMask if unavailable.
- Displays error messages for failed transactions or invalid inputs.
- Notifies users about insufficient gas or connectivity issues.

---

## License

This project is distributed under the **MIT License**, making it open for customization and redistribution.



