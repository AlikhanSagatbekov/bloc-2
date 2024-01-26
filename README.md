## Blockchain - 2 Assignment Documentation

To begin, we start by obtaining the Web3 package and the package.json file for the project.

For the purpose of this assignment, INFURA is utilized in conjunction with the Sepolia TestNet. This setup is connected to MetaMask, providing a seamless integration for interacting with the Ethereum blockchain. image

In the first phase of the project (Assignment 1), the smart contract was deployed. This was achieved by compiling the contract and obtaining the ABI (Application Binary Interface) along with the bytecode. These critical pieces of information were stored in Demo.json. The deployment process was orchestrated using a deployment script contained in the Deploy.js file .

image

In the final steps, a transaction was signed and sent, invoking a function within the deployed smart contract. The interaction was facilitated through the Call.js file, which encapsulates the logic for signing transactions, sending them to the Ethereum network, and calling specific functions within the deployed contract. This marks the culmination of the project, demonstrating the end-to-end process of deploying, interacting with, and executing functions on a smart contract.

image

That's all. Thank you!
