
Deployment Guide – ERC20 Token on BNB Smart Chain

1. Requirements
- MetaMask browser wallet (connected to BNB Chain Testnet or Mainnet)
- Some BNB in your wallet (for gas fees)
- Remix IDE: https://remix.ethereum.org

2. Add BNB Network to MetaMask

Testnet
Network Name: BNB Smart Chain Testnet
RPC URL: https://data-seed-prebsc-1-s1.binance.org:8545/
Chain ID: 97
Symbol: tBNB
Explorer: https://testnet.bscscan.com

Mainnet
Network Name: BNB Smart Chain Mainnet
RPC URL: https://bsc-dataseed.binance.org/
Chain ID: 56
Symbol: BNB
Explorer: https://bscscan.com

3. Write the Contract
- Open Remix
- Create a new file, for example: MyBNBToken.sol
- Paste the ERC20 code

4. Compile the Contract
- Go to Solidity Compiler tab
- Select compiler version 0.8.30
- Click Compile MyBNBToken.sol

5. Deploy the Contract
- Go to Deploy & Run Transactions tab
- Environment: select Injected Web3 (MetaMask)
- Connect MetaMask to BSC Testnet or Mainnet
- If constructor version: enter Token Name (example: MyBNBToken) and Symbol (example: MBT)
- Click Deploy
- Confirm transaction in MetaMask

6. Verify the Contract on BscScan
- Copy your deployed contract address
- Open BscScan Verify & Publish (mainnet or testnet)
- Select Solidity (Single file)
- Compiler: 0.8.30
- License: MIT
- Paste your contract code
- If imports fail, flatten the code in Remix (right click → Flatten)
- Click Verify and Publish

7. Add Token to Wallet
- Copy token contract address
- Open MetaMask → Import Tokens → paste the address
- Your balance (1,000,000 tokens) will appear

Done! You now have a verified ERC20 token on BNB Smart Chain.
