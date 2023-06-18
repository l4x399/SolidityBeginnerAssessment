# SolidityBeginnerAssessment

This repository is for a project output for ETH PROOF: Beginner EVM Course in Metacrafters. Remix Ethereum IDE is used for this project.

## Description

`myToken.sol` fulfills the requirements for creating a contract with the following Solidity syntax features used:
- Public variables that store information about the coin. These variables are the following: `tokenName`, `tokenAbbrv`, and `
- A public mapping variable named `balances` to map addresses to balances. The address is of the `address` data type, and the balance is of `uint` data type, or unsigned integer.
    - Unsigned integers are integers that cannot have a negative value.
- There are two functions, `mint` and `burn`. Both of these functions take two arguments, an address and a value.
- The `mint` function increases the balance of the address by the value given, and increases the total supply.
- The `burn` function is the opposite: it decreases the balance of the address by the value given, and decreases the total supply.

## Getting Started

### Installing

* There is only one file for this project, `myToken.sol`, which can be downloaded and imported to the Remix Ethereum IDE.

### Executing program

* Go to the Remix Ethereum IDE in here: https://remix.ethereum.org/
* To run the program, download `myToken.sol` and import it into Remix by clicking Open File. This should add the file into the workspace.
* Open `myToken.sol` and go to the Solidity Compiler at the left side of the page. Click Auto-compile and Compile script.
* Go to Deploy and run transactions, and click Deploy. The contract is then deployed as it can be seen in the Deployed Contracts section.
* The functions can now be tested, and variable values can now be checked within the deployed contract.

## Authors

l4x399 at GitHub

## License

This project is licensed under the MIT License - see the LICENSE file for details
