# MyToken Solidity Contract

This is a simple ERC-20 token contract built using Solidity and OpenZeppelin's ERC20 implementation. It allows the creation of custom tokens with an initial supply that is assigned to the contract deployer's address.

## Features

- **ERC-20 Compliant**: Implements all necessary methods defined by the ERC-20 standard.
- **Minting**: The contract allows minting tokens at deployment.
- **Initial Supply**: A configurable initial supply can be set when the contract is deployed.
- **Secure and Audited**:The MyToken contract is built on top of the well-established     OpenZeppelin ERC-20 implementation, ensuring a high level of security and reliability.
- **Scalable**: The contract is designed to handle a large number of token transfers and balances, making it suitable for projects with growing user bases.

## Requirements

To compile and deploy the contract, you'll need:

- [Node.js](https://nodejs.org/) (version 16 or higher)
- [Hardhat](https://hardhat.org/) - A development environment to compile, deploy, test, and debug your Solidity code.
- [OpenZeppelin Contracts](https://openzeppelin.com/contracts/) - A library of secure and reusable smart contracts.

## Installation

### Prerequisites

Ensure you have the following installed:

- **Node.js** (version 16 or above)
- **npm** (Node package manager)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Kilonzo88/MyToken.git
   cd MyToken
   ```
2. Install the required dependencies:
    ```bash
    npm install
    ```
3. Deploy the contract using Hardhat or Remix.


## Contract Overview
This contract implements an ERC-20 token using OpenZeppelin's ERC20 contract, with the following functionality:

### Constructor
initialSupply: The number of tokens to mint when the contract is deployed. This is passed as a parameter during deployment.
ERC20 Constructor: The constructor of the ERC20 contract is called with "MyToken" as the token's name and "MTK" as its symbol.
### Functions
name(): Returns the name of the token ("MyToken").
symbol(): Returns the symbol of the token ("MTK").
decimals(): Returns the decimals used by the token (default is 18).
totalSupply(): Returns the total supply of the token.
balanceOf(address account): Returns the balance of a given address.
transfer(address to, uint256 value): Transfers tokens to another address.
approve(address spender, uint256 value): Approves another address to spend tokens on behalf of the owner.
allowance(address owner, address spender): Checks the allowance of a spender on the owner’s behalf.
transferFrom(address from, address to, uint256 value): Transfers tokens on behalf of another address, using an allowance.

## Contributing
We welcome contributions to the MyToken project! If you find any issues or have suggestions for improvements, please feel free to open a new issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgements
OpenZeppelin Contracts for the ERC20 implementation.

    
