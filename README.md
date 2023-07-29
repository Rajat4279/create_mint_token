# Create_Mint_Token

This Solidity program helps to create ERC20tokens which can be minted only by the owner of the contract. The tokens can be transferred on the behalf of the owner by someoneelse, the contract ownership can be transferred to someoneelse and the tokens can be burnt by anyone who owns the tokens. 

## Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. Firstly, the 'ERC20' and 'Ownable' contract from 'OpenZepplin' is imported so that their methods can be used to develop the token. The name of the token and the token symbol is passed inside the ERC20 constructor. The "functionMintTokens()" function calls the "_mint()" function to create tokens, taking the address the tokens have to be minted to as well as the amount that has to be minted. The "functionBurnTokens()" function calls the "_burn" function and destroys a specified amount of tokens.


## Technologies Used 
- Remix - an online Solidity IDE  
- ethers.js - Library for interacting with Ethereum smart contracts

  
## Authors
- Rajat Srivastava


## License

This project is licensed under the MIT License - see [MIT LICENSE] for details
