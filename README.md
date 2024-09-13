# Solana Token Management Scripts

This project contains scripts designed to help you create and manage Solana-based tokens using a custom keypair. The provided scripts can:

- **Generate Keypairs**: Create a keypair from a base58 encoded private key using the `generateKeypair.js` script, essential for interacting with Solana's blockchain.
- **Create and Manage Tokens**: Use the `generateToken.js` script to automate the process of creating a Solana token, setting up a token account, minting the initial supply, and managing on-chain and off-chain metadata.

## Features

- **Keypair Generation**: Create a keypair from your wallet's private key to securely manage your tokens.
- **Token Creation**: Easily create a new token on the Solana blockchain, specifying supply, name, symbol, and more.
- **On-Chain and Off-Chain Metadata**: Store and manage token metadata both on-chain and off-chain, including images hosted on IPFS.
- **Authority Management**: Configure and revoke mint and freeze authorities to enhance security and control over your token.

## Requirements

- **Node.js**: Required to run the scripts.
- **Solana CLI**: Essential for executing Solana blockchain commands.
- **Phantom Wallet**: Your wallet for storing private keys and managing tokens.
- **IPFS Hosting**: Host images and files using a compatible IPFS service like [web3.storage](https://web3.storage/).
- **SPL Token Program**: Installable via Solana CLI, needed for token management.
- **Metaboss**: Required for adding metadata to your token on-chain.

## How to Use

1. **Set Up Your Environment**: Install Node.js, Solana CLI, and other required tools.
2. **Generate Keypair**: Run the `generateKeypair.js` script to create a keypair.
3. **Create a Token**: Use the `generateToken.js` script to create your token, mint supply, and configure its metadata.

## Contact

For detailed instructions or assistance, please contact [@Krypto_Hans on Telegram](https://t.me/Krypto_Hans).
