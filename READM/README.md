# Eth_Avax_intermediate_Project-3
Write a smart contract to create your own token on a local HardHat network. Once you have your contract, you should be able to use remix to interact with it. From remix, the contract owner should be able to mint tokens to a provided address. Any user should be able to burn and transfer tokens.
## MyToken Solidity Contract

This Solidity contract represents a token called MyToken. It allows the contract owner to mint new tokens, burn existing tokens, and transfer tokens between addresses.

## Contract Details

- Solidity Version: 0.8.18
- License: MIT

## Contract Address

The deployed contract address on the Ethereum blockchain will be provided here.

## Functionality

### Constructor

The constructor function sets the contract owner as the address that deployed the contract.

### `mint`

Mints new tokens and assigns them to the specified address. Only the contract owner can call this function.

### `burn`

Burns existing tokens from the specified address. The total supply and the balance of the address will be reduced by the specified value.

### `transfer`

Transfers tokens from one address to another. The sender's address balance will be reduced by the specified value, and the receiver's address balance will be increased by the same value.

## Usage

1. Open terminal in your system.
2. Deploy local hardhat network using *npx hardhat node*.
3. Deploy the contract on Remix.
4. Set the environment to dev-Hardhat provider.
5. Set the contract owner as the desired address.
6. Call the `mint` function to create new tokens and assign them to an address.
7. Call the `burn` function to burn existing tokens from an address.
8. Call the `transfer` function to transfer tokens from one address to another.

## License

This contract is licensed under the MIT License. See the [LICENSE] file for more details.
