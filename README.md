# MINT NFT Collection

This project contains contract code to automatically generate a list of NFTs   

### **Welcome 👋**
You can run this program using: 

1. Run `npx hardhat run scripts/run.js` to run the project
2. Run `npx hardhat run scripts/deploy.js --network rinkeby` to deploy the contract

Once contract is deployed, you can see it on [Etherscan](https://etherscan.io/)

All the NFTs minted can be seen on [Rinkeby](https://rinkeby.rarible.com/user/0xe59c75bc2559b7cb088ea57deeaaf481942f863e/owned) 

# Setup
Complete setup for this project can be found at [Buildspace NFT Marketplace](https://app.buildspace.so/projects/CO961ddb5f-f428-4608-9949-a9a2f461eb3f)


# 🤑 Getting some fake $
We will need fake dollars to pay for the gas fees when we are minting different NFTs. Gas fees is the transaction fee paid out to Miners :)  

There are a few testnets out there and the one we'll be using is called "Rinkeby" which is run by the Ethereum foundation.
In order to deploy to Rinkeby, we need fake ETH. Why? Because if you were deploying to the actual Ethereum mainnet, you'd use real money! So, testnets copies how mainnet works, only difference is no real money is involved.
In order to get fake ETH, we have to ask the network for some. This fake ETH will only work on this specific testnet. You can grab some fake Ethereum for Rinkeby through a faucet. 


# Hardhat
* Hardhat compiles your smart contract from solidity to bytecode.
* Hardhat will spin up a "local blockchain" on your computer. It's like a mini, test version of Ethereum running on your computer to help you quickly test stuff!
* Hardhat will then "deploy" your compiled contract to your local blockchain. That's that address you see at the end there. It's our deployed contract, on our mini version of Ethereum.

```
npm init -y
npm install --save-dev hardhat
```


✈️ A note on contract redeploys

Let's say you want to change your contract. You'd need to do 3 things:

You  need to deploy it again.
You need to update the contract address on our frontend.
You need to update the abi file on our frontend.
