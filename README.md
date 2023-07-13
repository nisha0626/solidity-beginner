# TOKEN CREATION
This is a simple token creation project.In this we can understand how to creat our own token and see the perfomance of mint function and burn function.

## DESCRIPTION
The token creation contract has three public variable.
These are as follows:
1)tokenName:
It is a string data type reprents the token name.

2)tokenAbbre:
It is also an string data type which represents the abbrevation of token.

3)totalSupply:
It is  an unsigned integer which represents the total supply of token and we will take this so that our totalSupply can never be zero.

### MAPPING: 
This will help to map our addresses to balances:


#### HOW TO PERFORM
1)For Creation: For the token creation we create a mint function which has two parameters as address and value of token.
 This function will increases the total supply by that number and also increases the balance of the address by that amount.

2)For Destruction:
For the token destruction we create a function called as burn function which is opposite to the mint function and has same parameter required for  creating the token.It will take an address and value just like the mint functions.It will then deduct the value from the total supply and from the balance.

License
This project is licensed under the Solidity Assessment License - see the LICENSE.md file for details.

