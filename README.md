# SolidityBeginnerAssessment

This repository is for a project output for ETH PROOF: Beginner EVM Course in Metacrafters. Remix Ethereum IDE is used for this project.

`myToken.sol` fulfills the requirements for creating a contract with:
- Public variables that store information about the coin. These variables are the following: `tokenName`, `tokenAbbrv`, and `
- A public mapping variable named `balances` to map addresses to balances. The address is of the `address` data type, and the balance is of `uint` data type, or unsigned integer.
    - Unsigned integers are integers that cannot have a negative value.
- There are two functions, `mint` and `burn`. Both of these functions take two arguments, an address and a value.
- The `mint` function increases the balance of the address by the value given, and increases the total supply.
- The `burn` function is the opposite: it decreases the balance of the address by the value given, and decreases the total supply.
