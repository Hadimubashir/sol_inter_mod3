

# MyToken (MT)

MyToken is an ERC20 token deployed on the Ethereum blockchain.

## Overview

This contract is an implementation of the ERC20 standard token with added functionalities for minting, burning, and ownership management.

### Features

- **Minting:** The owner can create new tokens and assign them to specific addresses using the `mint` function.
- **Burning:** Token holders can burn their own tokens using the `burn` function.
- **Transfers:** Standard ERC20 transfer functionality with the `transfer` function.

## Usage

### Deployment

The contract has been deployed on the Ethereum blockchain with the name "MyToken" and the symbol "MT."

### Interacting with the Contract

#### Minting Tokens

Only the contract owner can mint new tokens. To mint tokens, call the `mint` function, specifying the recipient's address and the amount of tokens to be minted.

#### Burning Tokens

Token holders can burn their tokens by calling the `burn` function, specifying the amount of tokens they want to burn.

#### Transferring Tokens

Use the standard ERC20 `transfer` function to send tokens from one address to another.

## Getting Started

To use this contract or interact with its functionalities:

1. **Connect to Ethereum Network**: Ensure you're connected to an Ethereum-compatible wallet or a development environment like Remix.
2. **Interact with the Contract**: Use the provided functions (`mint`, `burn`, `transfer`) according to the specified permissions and requirements.

## Contract Addresses

Mainnet: `<Insert Mainnet Contract Address>`  
Testnet: `<Insert Testnet Contract Address>`


---
