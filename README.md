# Swisstronik Challenge LearnWeb3DAO #1

Swisstronik is a layer 1 solution built on the Cosmos SDK framework. It aims to combine the benefits of the Ethereum Virtual Machine (EVM) with the underlying infrastructure provided by the Cosmos SDK. This integration allows Swisstronik to offer Ethereum compatibility while providing additional features such as private EVM execution using Intel SGX.

This straightforward Hardhat project is designed to guide you in creating a basic smart contract for message setting and retrieval. Dive into deploying your contract and interact with it using scripts & SwisstronikJS.

## Initialization
```
npm install --save-dev hardhat
npx hardhat
npm install --save-dev @nomicfoundation/hardhat-toolbox
npx hardhat run scripts/deploy.js --network swisstronik
npm i @swisstronik/swisstronik.js
npx hardhat run scripts/setMessage.js --network swisstronik
npx hardhat run scripts/getMessage.js --network swisstronik
```

## Faucet
```
https://faucet.testnet.swisstronik.com
```

## Material
Node JS :  [Download](https://nodejs.org/en/download)

## Result
Smart Contract
```0x6e0A04c80f281238832C2B005bedc1faCceB3BD3```