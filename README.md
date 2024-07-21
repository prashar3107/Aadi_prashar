# Project Title
MyToken
# Simple Overview
MyToken is a basic Ethereum smart contract that implements a simple token with minting and burning capabilities.

# Description
MyToken is designed to provide basic functionalities for a cryptocurrency token. It includes the ability to mint new tokens, which increases the total supply and the balance of the specified address. Conversely, it also allows burning tokens, which decreases the total supply and the balance of the specified address. The contract ensures that tokens can only be burned if the balance is sufficient.

# Getting Started
## Installing
To get started with MyToken, you need to have a development environment set up for Ethereum smart contract development. We recommend using Remix IDE or setting up a local environment using tools like Truffle or Hardhat.

* Clone the repository or copy the contract code.
*  Open the contract in your preferred development environment.Remix
# Executing Program
To deploy and interact with the MyToken contract, follow these steps:

1. Compile the Contract: Use the compiler in your IDE to compile the MyToken contract.
2. Deploy the Contract: Deploy the contract to a local blockchain (e.g., Ganache) or a testnet (e.g., Ropsten).
3. Mint Tokens: Call the mint function with the desired address and amount to mint new tokens.
solidity
```

myToken.mint("0xYourAddress", 1000);
```
4. Burn Tokens: Call the burn function with the desired address and amount to burn tokens.
solidity
```
myToken.burn("0xYourAddress", 500);
```
# Help
For any issues or common problems, please refer to the following:

* Ensure you have a sufficient balance for burning tokens.
* Check the contract deployment address and network configuration.
# Authors
Dominique Pizzie - Aditya Prashar
