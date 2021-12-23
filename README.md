# MINT NFT Collection

This project contains contract code to automatically generate a list of NFTs   


# Setup
Complete setup for this project can be found at [Buildspace NFT Marketplace](https://app.buildspace.so/projects/CO961ddb5f-f428-4608-9949-a9a2f461eb3f)


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
