# Ethereum DApp for Ether Transactions - README
This repository contains a simple Ethereum Decentralized Application (DApp) for conducting ether transactions on the Ethereum blockchain. The DApp allows users to interact with a smart contract deployed on the Ethereum network to perform deposit and withdrawal operations.

## Prerequisites
To run this DApp locally, you need the following software installed on your system:

Node.js: The JavaScript runtime environment used for running the DApp server.
npm: The package manager for Node.js, used for installing project dependencies.

## Getting Started
1. Clone the repository to your local machine:

```
git clone https://github.com/yourusername/ether-transaction-dapp.git
cd ether-transaction-dapp
```

2. Install the dependencies:

```
npm install
```

3. Compile and Deploy the Smart Contract:
Before running the DApp, you need to deploy the Transactions smart contract to a test Ethereum network like Ganache or a public network like Rinkeby or Ropsten. You can use tools like Remix IDE or Truffle to compile and deploy the contract.

4. Configure the Frontend:
Open the index.html file in the root of the project and modify the Address variable inside the connectContract function with the deployed smart contract address.
```
const Address = "0xa55a60B0Ca597792ce1A24ce14eEfADA9f0fE780"; // Replace this with the deployed contract address
```

5. Start the DApp Server:
Run the following command to start the DApp server:
```
node app.js
```

### Access the DApp:
Open your web browser and navigate to 'http://localhost:5000' to access the DApp.

## How to Use the DApp
1. **Connect to Metamask:** Click the "CONNECT TO METAMASK" button to connect your Metamask wallet. You'll be prompted to connect, and once connected, your account address will be displayed under "User Account."

2. **Connect to Contract:** Click the "CONNECT TO CONTRACT" button to connect to the deployed smart contract on the Ethereum network. The DApp will interact with the smart contract using Web3.js library and your connected Metamask account.

3. **Get Contract Account:** Click the "GET CONTRACT ACCOUNT" button to fetch the Ethereum address of the deployed smart contract. The address will be displayed under "Contract Account."

4. **Get Balance of the Contract:** Click the "GET BALANCE OF THE CONTRACT" button to check the balance of the smart contract. The contract balance will be displayed under "Balance."

5. **Send Ether to the Contract:** Enter the amount of ether you want to deposit in the smart contract in the input field and click "Send ether to the Contract." Metamask will prompt you to confirm the transaction. After confirming, the deposit will be executed.

6. **Withdraw Ether to Any Address:** Enter the recipient's address and the amount of ether you want to withdraw from the smart contract. Click "WITHDRAW ETHER TO ANY ADDRESS." Metamask will prompt you to confirm the transaction, and upon confirmation, the specified amount of ether will be sent to the provided address.

## License
This contract is licensed under the MIT License. SPDX-License-Identifier: MIT. loom video link
https://www.loom.com/share/86563c37661d43f9a14568ad9b9e98ad

## Author
Vaishnavi Arora
