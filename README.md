# MyToken 

## Overview

This repository contains the source code for the MyToken smart contract, a simple ERC-20 token deployed on the Ethereum blockchain. The contract is implemented in Solidity and utilizes the OpenZeppelin library for ERC-20 functionality and Ownable for access control.

## Smart Contract Features

### ERC-20 Compliance

The MyToken contract is ERC-20 compliant, providing standard functions for token transfers, approvals, and querying token balances.

### Minting

The contract allows the owner (deployer) or authorized addresses to mint new tokens. The `mint` function is used for this purpose, allowing the creation of tokens and their assignment to a specified destination address.

### Burning

Token holders can burn their own tokens using the `burn` function. This operation decreases the total token supply and the balance of the burning address.

### Transfer

The `transfer` function allows token holders to transfer tokens to another address. It checks for valid transfer conditions, including a positive transfer amount, a valid destination address, and sufficient token balance.

### Access Control

The contract uses the Ownable pattern to restrict certain functions to the owner or authorized addresses. The `onlyOwnerOrAuthorized` modifier ensures that only the owner or authorized addresses can execute specific functions, such as minting.

### getTotalSupply

The `getTotalSupply` function provides a read-only method to retrieve the total supply of MyToken.

## Deployment

The contract is deployed using Solidity version 0.8.0 and is based on the OpenZeppelin contracts version available at the time of deployment.

## Usage

Developers can deploy the MyToken contract to the Ethereum blockchain and interact with it using Ethereum-compatible wallets, scripts, or other smart contracts.

## License

This smart contract is licensed under the MIT License. See the `LICENSE` file for more details.


## Contact 

Krishna M

km1527771@gmail.com

