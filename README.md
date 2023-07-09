# MyToken

This repository contains a Solidity contract called "MyToken" which implements a basic ERC20 token with minting and burning functionality.

## Contract Details
SPDX-License-Identifier: MIT
Solidity version: 0.8.18

## Public Variables
tokenName: A public string variable representing the name of the token (currently set to "Random").
tokenAbbrv: A public string variable representing the abbreviated name of the token (currently set to "Rndm").
totalSupply: A public uint256 variable representing the total supply of tokens (initialized to 0).

## Mapping
balances: A mapping that associates addresses with their corresponding token balances. It maps an address to a uint256 value representing the balance of tokens held by that address.

## Functions
## mint
The mint function allows for the creation of new tokens. It takes two parameters: _address (the address to which the tokens will be assigned) and _value (the amount of tokens to mint). The function increases the total supply of tokens by the specified value and assigns the minted tokens to the given address.

## burn
The burn function enables the destruction of tokens. It takes two parameters: _address (the address from which the tokens will be burned) and _value (the amount of tokens to burn). The function verifies that the address has a sufficient balance to burn the specified amount of tokens. If the balance is enough, it reduces the total supply by the specified value and subtracts the burned tokens from the address's balance.

Please note that this contract does not implement any access control or security features, and it is meant for educational or demonstration purposes only.

## Important: 
Before deploying or using this contract in a production environment, make sure to review and address any potential security vulnerabilities and follow best practices for smart contract development.

For more information on Solidity and ERC20 tokens, refer to the official Solidity documentation and Ethereum standards.


```

## License
This code is licensed under the MIT License. Please see the accompanying LICENSE file for more details.
