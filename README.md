MyToken Smart Contract
Overview
The MyToken smart contract is a simple implementation of an ERC-20-like token. It allows for minting and burning of tokens while maintaining a total supply and balances for different addresses. This contract is created using Solidity and runs on the Ethereum blockchain.

Features
Public Variables:

tokenName: Stores the name of the token (e.g., "Meta").
tokenAbbrv: Stores the abbreviation of the token (e.g., "Mta").
totalSupply: Tracks the total supply of the token in circulation.
Mapping for Balances:

balances: Maps an address to its token balance.
Mint Functionality:

Adds tokens to a specified address and increases the total supply.
Burn Functionality:

Reduces tokens from a specified address and decreases the total supply.
Includes a check to ensure the address has sufficient balance to burn the specified amount.
