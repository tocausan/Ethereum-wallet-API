# Ethereum wallet API

## Description
Ethereum wallet API using the (ethersJs)[https://docs.ethers.io/ethers.js/html/] library and
 (express-es6-rest-api)[https://github.com/developit/express-es6-rest-api] API boilerplate.

## Routes
```text
GET     /                                   Redirect to /api
GET     /api                                Get API infos
GET     /api/createWallet                   Create a random wallet
GET     /api/getBalance/[wallet address]    Get wallet's address balance
POST    /api/transaction                    Create a transaction, requires {privateKey, destination, amount}
```

## installation
```text
# clone this repo
git clone git@github.com:tocausan/Ethereum-wallet-API.git

# install modules
npm install

# start server
npm start
```

## Licence
MIT
