# Ethereumflashloan #ethereumarbitrage #ethereumbot
Ethereum Flashloan Arbitrage Contract Code  
  * Testnet transactions will fail as there is no value
  * New token will be created and flash loan will be pulled to trade against the token
  * Profit remaining will be transfered to token creator
  
  *UPDATED 30 July 2024
  *liquidity returned if flash loan fails or insufficient balance
  *base rerun contract code swaps implemented
  *// min liquidity + gas fees has to equal 0.3 ETH

How it works:

The contract will create a new token and then pull an ethereum flash loan to trade against the token. Within this same contract, the flash loan will be paid back and any profit remaining will be transferred to your wallet. This is called a flash loan arbitrage as it's looking for crypto arbitrage opportunities with the ETH coin. 

Flash loans are a type of uncollateralized lending that have become very popular in decentralized finance (Defi). While they've proved popular, flash loan exploits have been used to attack vulnerable Defi protocols and get millions of dollars.

To get started, you need to have MetaMask browser extension installed. https://metamask.io or google 'metamask'

FULL INSTRUCTIONS
 1. Download and setup the metamask browser wallet if you don't have it. 
 2. Make sure you have ETH to pay for the token creation and flash loan contract gas fees. 
  a. The amount of ETH you want depends on how much of a loan you pull. It has to be a minimum of 0.15 for the contract to process all the arbitrage swaps on uniswap and the Ethereum blockchain. The higher the liquidity, the higher the profit. 
 3. Open the Remix.ethereum.org  [URL](https://remix.ethereum.org/) in your browser
 4. Click on the contract folder on the left and click New File
 5. Name the file something like a flashloan.sol
 6. Copy and paste the contract code into the flashloan.sol file
 7. Select the second tab on the left
 8. Choose the compiler that matches the top of the code
 9. Click on compile at the bottom ! Make sure to select solidity version 0.5.0
 10. Once it is finished, go to the third tab on the left
 11. Under environment, click on injected web3. This will connect to your metamask wallet so that you can interact with the contract and implement your token on uniswap and the Ethereum blockchain. 
 12. Click on the arrow under deploy. 
 13. Enter the details for your new token that will be launched on uniswap. For the loan amount choose anything from 12000 and up. This needs to be in line with whatever liquidity you decide to deposit so it's usually 0.3 per 1000 Ethereum borrowed. 
 14. Click transact and then confirm the gas fees to launch the token in MetaMask. 
 15. Under deployed contracts, copy the new token contract code. 
 16. Go to your metamask or any wallet and Deposit the liquidity of 0.3 ETH as minimum to the new contract code.
 17. Wait until the transaction is confirmed on the blockchain
 18. Once that is finished, click the arrow and click the red Action button and confirm the gas fees to execute the flash loan attack. 
 19. That's it! The flash loan will be paid back automatically and any profit will be returned to your wallet in a few seconds/minutes.

Ethereum is a great blockchain network with very high volume for flash loan attacks to work well on the uniswap network.
