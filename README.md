# Gasless NFT Minting with Biconomy - Tutorial

In this guide, we will walk through creating a basic Node.js script using TypeScript that allows users to mint an NFT without paying for any Gas using the Biconomy platform.

This tutorial will be conducted on the Polygon Mumbai Network. The address for the contract is `0x1758f42Af7026fBbB559Dc60EcE0De3ef81f665e`.

## Prerequisites

- Node.js 
- Private Key for the Ethereum Wallet

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Sruthi-Manthena/Gasless-Transaction-Biconomy
   cd Gasless-Transaction-Biconomy
   ```
2. Install Dependecies
   ```bash
   npm install or yarn install 
   ```
3. Create a .env file in the root directory and add your private key
   ```bash
   PRIVATE_KEY="your-private-key-here"
   ```
4. Replace YOUR_BUNDLER_URL and YOUR_PAYMASTER_URL with the actual URLs from your Biconomy account.
5. Run the script
    ```bash
   npm run dev 
   ``` 

## Explanation
* We define the mintNFT function that is responsible for minting an NFT using Biconomy.
* It involves creating an interface for the NFT contract, collecting data for the user operation, constructing the transaction, building the user operation, and executing it using Biconomy's Paymaster for gasless transactions.

## Resources

- [Biconomy Documentation](https://docs.biconomy.io/)
- [Biconomy GitHub](https://github.com/bcnmy)
