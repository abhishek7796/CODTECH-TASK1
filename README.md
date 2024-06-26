![Task 1 Remix IDE SS](https://github.com/abhishek7796/CODTECH-TASK1/assets/120003948/19b918e4-7334-4499-b117-c4c2d9432991)# CODTECH-TASK1
INTERNSHIP TASK 1

1. Prerequisites
Before starting, make sure you have the following:
MetaMask: A browser extension that allows you to interact with the Ethereum network.
Remix IDE: An online tool for developing smart contracts using Solidity.
Sepolia Test Network: A test network for deploying and testing your smart contracts without using real Ether.

2. Setting Up MetaMask
Install MetaMask: Add the MetaMask extension to your browser from the official website.
Create an Account: Set up a new wallet or import an existing one.
Add Sepolia Network:
Open MetaMask and click on the network dropdown at the top.
Select "Add Network".
Enter the Sepolia network details:
Network Name: Sepolia Test Network
New RPC URL: https://rpc.sepolia.org
Chain ID: 11155111
Currency Symbol: ETH
Block Explorer URL: https://sepolia.etherscan.io
Click "Save".
Get Test Ether: You can obtain test Ether from a Sepolia faucet. One such faucet is Sepolia Faucet.

3. Writing the Smart Contract
Open Remix IDE: Go to Remix IDE.
Create a New File: Click on the file explorer icon, then click on the "New File" button. Name it SimpleStorage.sol.
Write the Contract:
Contract written in file name SmartContract


4. Compiling the Contract
Select the Compiler Version: In Remix, go to the "Solidity Compiler" tab and select version 0.8.0 or any compatible version.
Compile: Click on the "Compile SimpleStorage.sol" button.

5. Deploying the Contract
Connect MetaMask to Remix: In Remix, go to the "Deploy & Run Transactions" tab.
Select Environment: Choose "Injected Web3" from the Environment dropdown. MetaMask will prompt you to connect your wallet. Choose the account with the Sepolia network.
Deploy: Make sure the "SimpleStorage" contract is selected, then click on the "Deploy" button. Confirm the transaction in MetaMask.

6. Interacting with the Contract
View Deployed Contracts: After deployment, you’ll see the deployed contract in the "Deployed Contracts" section.
Interact:
Use the "set" function to store a value.
Use the "get" function to retrieve the stored value.
