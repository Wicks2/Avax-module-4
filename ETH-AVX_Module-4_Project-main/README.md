# Degen Gaming Token - README

## Overview

Welcome to the Degen Gaming Token project! This is an Ethereum-based ERC20 token smart contract designed to facilitate rewards and in-game purchases for Degen Gaming, a renowned game studio. Players can earn tokens as rewards, transfer them to others, redeem them for items in the in-game store, and burn them if they are no longer needed. The smart contract is deployed on the Avalanche blockchain, a leading platform for web3 gaming projects, ensuring fast and low-fee transactions.

## Getting Started

To get started with the Degen Gaming Token, follow the instructions below:

### Prerequisites

1. An Metamask wallet that supports ERC20 tokens (e.g., Metamask).
2. An Avalanche Network.
3. An Account which have enough AVAX to perform this contract.
4. Use Avalanche fuji test Network.
5. These are the settings to make a new netwok of Avalanche fuji test network
   
  Network Name
  Avalanche Testnet C-Chain
  
  Network URL
  https://api.avax-test.network/ext/bc/C/rpc
  
  Chain ID
  43113
  
  Currency Symbol
  AVAX
  
  Block Explorer URL
  https://testnet.snowtrace.io/
  
6. After that go to faucet.avax.network and request the AVAX in your wallet address. 

### Deployment

1. Access the [Remix IDE](https://remix.ethereum.org) or any other Solidity IDE with Ethereum deployment capability.

2. Copy and paste the entire smart contract code into the editor.

3. Compile the smart contract by selecting the appropriate Solidity compiler version (0.8.18 or later).

4. Select "Injected Web3" as the environment in Remix.

5. Choose the metamask wallet address you want to deploy the contract from in Remix.

6. Deploy the smart contract to the Avalanche blockchain by clicking the "Deploy" button.

7. Confirm the transaction in your metamask wallet when prompted.

8. Once the contract is deployed, you will receive the contract address for the Degen Gaming Token.

### Interacting with the Contract

After deploying the smart contract, you can interact with it using the following functions:

1. **Minting new tokens**: Only the contract owner can mint new tokens. Use the `mint` function to create and distribute tokens to players as rewards.

2. **Transferring tokens**: Players can transfer their tokens to others using the `transferTokens` function.

3. **Redeeming tokens**: Players can redeem their tokens for in-game items from the store using the `redeemTokens` function. Players need to provide the token choice (1 to 5) and the corresponding payment to obtain the selected item.

4. **Checking token balance**: Players can check their token balance at any time using the standard ERC20 `balanceOf` function.

5. **Burning tokens**: Users can burn (destroy) tokens they own but no longer need using the `burnTokens` function.

Please note that some functions have specific requirements and conditions. Always verify the availability of tokens and balances before attempting transactions.

## Game Store Items

The Degen Gaming Token can be redeemed for the following in-game items:

1. Naruto Headband - 500 DGN
2. Madara Susano - 1200 DGN
3. Fireball Punch - 300 DGN
4. Itachi Sharingaan - 800 DGN
5. Kurama 9 Tailed Beast - 1000 DGN

## License

The Degen Gaming Token smart contract is licensed under the MIT License. You are free to use, modify, and distribute the code as per the terms of the license.

## Disclaimer

This smart contract is provided as an educational example and for demonstration purposes only. While efforts have been made to ensure the security and accuracy of the code, it is essential to conduct a thorough audit before deploying it in any production environment. The authors and maintainers of this smart contract are not liable for any damages or losses resulting from the use or misuse of this code.
