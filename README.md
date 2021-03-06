
# Election - DAPP 



Follow the steps below to download, install, and run this project.

## Dependencies 
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
https://github.com/choudhary805/EthereumVoting.git

## Step 2. Install dependencies
```
$ cd election
$ npm install

## Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.


## Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Configure Metamask

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000



