# polkado_nft_marketplace
A TypeScript-based NFT marketplace built on the Polkadot blockchain.

## What it does
This project allows users to create, buy, and sell NFTs on the Polkadot network. It provides a simple and intuitive interface for interacting with the blockchain, making it easy for developers to build their own NFT marketplaces.

## Installation
To get started, make sure you have Node.js and npm installed. Then, clone this repository and install the dependencies:
```bash
git clone https://github.com/your-username/polkado_nft_marketplace.git
cd polkado_nft_marketplace
npm install
```
## Running the project
To start the development server, run:
```bash
npm run start
```
This will launch the marketplace interface in your default web browser.

## Example usage
Here's a quick example of how to create a new NFT:
```typescript
import { createNFT } from './nft-utils';

const nftData = {
  name: 'My NFT',
  description: 'This is my NFT',
  image: 'https://example.com/image.png',
};

createNFT(nftData).then((nftId) => {
  console.log(`NFT created with ID: ${nftId}`);
});
```
Check out the [wiki](https://github.com/your-username/polkado_nft_marketplace/wiki) for more documentation and guides.