# MyToken Smart Contract

## Overview
MyToken is a simple ERC-20-like token implemented in Solidity. This contract allows minting and burning of tokens and maintains a record of balances associated with each address.

## Contract Details
- **Token Name**: MyToken
- **Token Symbol**: MTK
- **Total Supply**: Dynamically changes based on minting and burning operations.

## Functions

### `mint(address _to, uint256 _value)`
Mints new tokens by increasing the total supply and crediting the specified address with the minted amount.

### `burn(address _from, uint256 _value)`
Burns tokens by decreasing the total supply and debiting the specified address, provided the address has sufficient balance.

## How to Use
1. **Deploy the contract**: Use Remix IDE or any Ethereum development environment to deploy the `MyToken` contract.
2. **Mint Tokens**: Call the `mint` function with the desired address and amount to mint new tokens.
3. **Burn Tokens**: Call the `burn` function with the desired address and amount to burn tokens, ensuring the address has enough balance.
