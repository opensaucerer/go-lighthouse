# Lighthouse

Lighthouse is a permanent decentralized file storage protocol that allows the ability to pay once and store forever. While traditionally, users need to repeatedly keep track and pay for their storage after every fixed amount of time, Lighthouse manages this for them and makes sure that user files are stored forever. The aim is to move users from a rent-based cost model where they are renting their own files on cloud storage to a permanent ownership model. It is built on top of IPFS, Filecoin, and Polygon. It uses the existing miner network and storage capacity of the filecoin network.

## Installation

```bash
go get github.com/sampe/go-lighthouse
```

## Basic Usage Example

```javascript
const lighthouse = require('@lighthouse-web3/sdk');

// Create wallet
const wallet = await lighthouse.createWallet('Password for wallet encryption');

// Get wallet balance
const balance = await lighthouse.getBalance(publicKey);

// Deploy File
const deploy = await lighthouse.deploy(
  '/home/cosmos/Desktop/wow.jpg',
  api - key
);
```

For the full documentation, refer to [GitBook](https://lighthouse-storage.gitbook.io/lighthouse/)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change and please make sure to update tests as appropriate.
