# Decentralized Dropbox

Saves files on IPFS and stores the respective hash on a blockchain.

## Front End
![deposit](https://github.com/igibliss00/decentralized-dropbox/blob/master/images/frontend.png)


## 🔧 Project Diagram:
![Project Diagram](https://i.gyazo.com/2738ea6743a40036756b1b5714ab9fa8.png)


## Installing

First, install Truffle globally.
```
npm i -g truffle@nodeLTS
```
Install the relevant packages:

```
git clone https://github.com/igibliss00/real_estate_erc721_dapp.git
npm install
```

## Running the tests

To run all tests:

```
truffle test
```

## Running the website

1. Download and install Ganache from [here](https://www.trufflesuite.com/ganache).

2. Download and install the MetaMask browser extension from your browser's extension store or from [here](https://metamask.io/download).

3. Migrate the smart contracts to the Ganache's blockchain with `truffle migrate`.

4. Import a MetaMask account by using the private key of one of the Ganache's test accounts.

5. Link your MetaMask to Ganache by registering Ganache's RPC Server and the Network ID to MetaMask's Custom RPC.

6. Start the React app with `npm start`.

7. Now you should be able to upload your files!

In the case that the Web3 is unable to call the smart contract functions, perform `truffle migrate --reset` or disconnect/re-connect the localhost from/to your MetaMask and try again.

## Uploaded to IPFS

https://bafybeic6qrg4dnxx6oa6b46qzwiaxirw6lhflqwqutv5hv224bzqrrxtju.ipfs.infura-ipfs.io/