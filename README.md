# Blockchain String Saver | Dapp

A small Ethereum DApp for saving and retrieving a string on the Sepolia testnet.

## What it does

- Connects to MetaMask
- Saves a string to a smart contract
- Retrieves the latest saved string
- Shows transaction history for the connected wallet

## Stack

- HTML, CSS, and JavaScript
- ethers.js
- MetaMask
- Sepolia testnet

## Run it

1. Open `index.html` in a browser.
2. Make sure MetaMask is installed and unlocked.
3. Connect to Sepolia. If you need test ETH, get some from the [Google Sepolia Faucet](https://cloud.google.com/application/web3/faucet/ethereum/sepolia) (the Chainstack Faucet mentioned in the blog no longer works reliably).
4. Save a string and view the transaction on Etherscan.

## Note

The contract address is hardcoded in `script.js`, so if you deploy a new contract you will need to update it there.

## Based on

[A Hands-on Guide to Building Your First Decentralized Application](https://hyperskill.org/blog/post/a-hands-on-guide-to-building-your-first-decentralized-application) by Davide Zambiasi on the Hyperskill blog.
