# Token_SmartContract
This contract is a an ERC20 contract written in solidity on ethereum.
the contract has the following public variables
_ TokenName; this is the name of the erc20 token
- tokenAbrrev; this is the symbolical identity of the token in form of abbreviation of the token name.
- totalSupply; this is the total circulation of the token at a particular time
- Balances; this is a mapping that maps individual addresses to balances
The contract has several functions which includees
 - Mint; this function takes in an address and a uint value as parameters and allows the adrress to mint tokens
 - Burn; this function also takes in two addresses as arguments and allows the address to burn a specified unit if the token , as long as the balance is greater than or equal to the value being burnt
