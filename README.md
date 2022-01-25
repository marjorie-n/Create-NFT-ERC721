# 👊 Deploy NFT with Truffle, IPFS OpenSea & Polygon (Mumbai)
## Visit for see my NFT: [Opensea Link](https://testnets.opensea.io/assets/mumbai/0xf0ae167c87bd404d00893bf2da2b87d7483b00f1/1/) .
### Prerequisite programming in node.js would be beneficial.

# 🚀 Getting started 
Clone this repo. 
Run `npm install` in terminal.
* Place Matic RPC node key and Wallet Mnemonic in new .env file
* Upload some nft metadata to an api. I used IPFS.
* Place link to NFT Collection.json in contractURI method, under GameItem.sol. 
* Deploy the contracts with `truffle develop` then `migrate --network mumbai` in the terminal, then copy the contract address.
* Add your account address, contract address and token json link to the mint script.
* Enter `node scripts/mint.js` into the console to mint.
* For security reasons my files with my private keys have been deleted as well as the hashes of my images and my json files.


## 💡 This is inspired by opensea's tutorial
* [Doc Opensea](https://docs.opensea.io/docs/getting-started)
* [Doc OpenZeppelin](https://docs.openzeppelin.com/contracts/4.x/erc721)


### A simple way to create NFT smart contracts and deploy on OpenSea to make our digital asset visible.
 ### Good work!🙂
