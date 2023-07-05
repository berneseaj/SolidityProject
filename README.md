# Solidity Final Project
To run this program, first, we need to have a public variable. So I wrote string public tokenName = "PROJECT," and for the token abbreviation string public tokenAbbrv = "PROJ," the total supply is uint public totalSupply = 0. 

For the second step, our contract will have a mapping of addresses to balances so that we will be mapping address to uint. 

In the third step, we will have a mint function that takes two parameters, an address, and a value. 
 
Our burn function will deduct the value from the total supply and the balance of the address and should have conditionals to ensure the balance of the account is greater than or equal to the amount that is supposed to be burned.

You can deploy the token.sol from the contract tab. When it is deployed, the output shows a green check, indicating that it is operational. Click the "deployed contracts" option below, then paste the address you previously copied into the "burn" and "mint" sections. You can click "transact" after adding value.

# AUTHOR
Alessandra Bernese
