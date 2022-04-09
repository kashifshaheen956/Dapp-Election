# Election - DAPP Tutorial

Build your first decentralized application, or Dapp, on the Ethereum Network with this tutorial!

## 2022 Updated Code

out-of-the-box for use!

Fix several issues, check CHANGELOG for detail.

## Dependencies

Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## Step 1. Clone the project

`git clone https://github.com/kashifshaheen956/Dapp-Election`

## Step 2. Install dependencies

```
$ cd Dapp-Election
$ npm install
```

## Step 3. Start Ganache

Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

## Step 4. Compile & Deploy Election Smart Contract

`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask

- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application

`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

## Notes

1. Use `web3.eth.getAccounts()` to get accounts now
2. To bootstrap sample truffle project, use command `truffle unbox pet-shop`
