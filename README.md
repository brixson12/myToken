# Brix Token Smart Contract

This is a basic Ethereum smart contract for a custom token named "Brix" (BRX). The contract allows the minting and burning of tokens.

## Contract Overview

The smart contract defines a custom token with the following properties:

- **Token Name:** "Brix"
- **Token Abbreviation:** "BRX"
- **Total Supply:** 0 (initially)

It uses a mapping variable to keep track of token balances for different addresses.

## Public Variables

- `tokenName`: A public string variable representing the name of the token, which is "Brix."
- `tokenAbbrv`: A public string variable representing the abbreviation of the token, which is "BRX."
- `totalSupply`: A public uint variable representing the total supply of the token, initially set to 0.

## Mapping Variable

- `balances`: A public mapping variable that associates Ethereum addresses with their token balances. It tracks how many tokens each address holds.

## Mint Function

- `mint(address _address, uint _value)`: This function allows the creation of new tokens and the addition of those tokens to a specified address. It increases the total supply and updates the balance of the specified address.

## Burn Function

- `burn(address _address, uint _value)`: This function allows the destruction (burning) of tokens held by a specified address. It checks if the address has enough tokens to burn and updates the total supply and address balance accordingly.

## Usage

To use this smart contract:

1. Deploy the contract on an Ethereum blockchain.
2. Interact with the contract using an Ethereum wallet or a DApp.
3. Mint new tokens by calling the `mint` function, specifying the recipient address and the number of tokens.
4. Burn tokens by calling the `burn` function, specifying the address and the number of tokens to destroy.

## License

This project is open-source and provided under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

- BRIXSON

