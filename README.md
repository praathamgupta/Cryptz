# Cryptz

## Setup and Run
Prerequisites
### Node.js: 
Node.js is a JavaScript runtime that allows you to execute JavaScript code outside of a web browser. It's required to run JavaScript-based applications, including the Krypt DApp.

### Hardhat: 
Hardhat is a development environment for Ethereum that provides tools for compiling, deploying, testing, and interacting with smart contracts.

## Installation
### Clone the repository: 
This step involves making a copy of the project's code repository on your local machine. You'll use Git commands to do this.

### Install dependencies: 
In order to run the DApp and interact with Ethereum, you need to install the required libraries and packages. The npm install command is used to download and install these dependencies.

## Deploy Smart Contract
### Navigate to the contracts directory: 
This means changing your terminal's current directory to the location of the transactions.sol file. This file contains the Solidity code for the smart contract.

### Edit the transactions.sol file: 
This step suggests that you can make changes to the transactions.sol file if needed. You may customize the smart contract's behavior based on your requirements.

### Deploy the smart contract using Hardhat: 
Running the npx hardhat run scripts/deploy.js command compiles and deploys the smart contract to the Ethereum blockchain. The script in deploy.js is responsible for deploying the contract.

## Run the DApp
### Navigate to the src directory: 
Similarly to the previous step, this involves changing your terminal's current directory to the src directory, where the frontend code is located.

### Edit the main.jsx file: 
You're encouraged to modify the main.jsx file to tailor the frontend's behavior and appearance as per your preferences.

### Start a local development server: 
By executing npm start, you initiate a local server that hosts the DApp. This allows you to access the DApp in your web browser.

### Open the DApp in your web browser: 
After starting the local server, you can access the DApp by typing http://localhost:3000 into your browser's address bar.

## Technologies Used
### Solidity: 
This is the programming language used to write Ethereum smart contracts. Solidity code defines the logic and behavior of the Transactions smart contract.

### Hardhat: 
Hardhat is a development environment for Ethereum that assists with tasks like compiling Solidity code, deploying smart contracts, and testing.

### React: 
React is a popular JavaScript library for building user interfaces. In this case, React is used to create the frontend of the DApp.

### Web3.js: 
Web3.js is a JavaScript library that provides an interface for interacting with the Ethereum blockchain. It's used to connect the frontend (built with React) to the smart contract.

### Chai: 
Chai is an assertion library for writing tests in JavaScript. It's used in the testing process to verify that the smart contract behaves as expected.

### Ethers.js: 
Similar to Web3.js, Ethers.js is another JavaScript library used for interacting with $Ethereum$ . It's used for communication between the DApp frontend and the smart contract.

### HTML/CSS: 
HTML is the markup language used for structuring the content of web pages, while CSS is used for styling those pages.

## Design Choices
### Smart Contract Structure: 
The Transactions smart contract is structured to facilitate transactions between users. It maintains information about each transaction, including sender and receiver addresses, amount, message, timestamp, and keyword.

### Event Emission: 
The smart contract emits a Transfer event whenever a new transaction is added. This event serves as a way to notify the frontend about the occurrence of new transactions.

### Frontend Interface: 
The DApp's frontend is built using React, a popular choice for building dynamic web applications. The frontend provides a user-friendly interface for interacting with the smart contract. Users can initiate transactions, view all transactions, and see the total transaction count.

### Testing: 
The smart contract and DApp are both tested using Chai and Hardhat's testing tools. Testing is crucial to ensure that the smart contract functions as expected and that the frontend communicates with it correctly.
