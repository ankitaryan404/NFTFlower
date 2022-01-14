# Basic Hardhat Project of NFT

This project demonstrates the deployment of Nft using Hardhat. It comes with a sample contract, a test for that contract, a script for deploy for the contract. All the information about NFT is written in nft-metadata.json file. The image file is uploaded in Pinata (IPFS).

To install the packages write 
```
npm install
```

To compile the project run
```
npx hardhat compile
```
To deploy the project
```

node scripts/deploy.js
```

File can be seen in 
[Deplyed Image in Pinata](https://gateway.pinata.cloud/ipfs/QmRZuG3FWhadwSuP98xAvGvP6qw5y1sTmK1QRn31ykZyMe)


### Make and .env file in root directory  write the following code

```
API_URL=Enter Api Url From Alchemy or Infura
PRIVATE_KEY=Enter your test network Private Key
PUBLIC_KEY=Enter your account public key
```
