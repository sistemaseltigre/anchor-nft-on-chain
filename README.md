# On-Chain NFT Creation with Anchor/Rust

This repository contains a Rust program developed using the Anchor framework that allows you to create an NFT (Non-Fungible Token) entirely on-chain. The provided code demonstrates how to mint a single NFT, including creating metadata and a master edition. An example JSON metadata file and an image are included to showcase the process.

## Prerequisites

Before using this code, make sure you have the following set up:

- Rust
- Anchor 
- Solana Playground

## How to Use

1. ## Clone this repository:

   ```
   git clone https://github.com/sistemaseltigre/anchor-nft-on-chain.git
   cd anchor-nft-on-chain
   ```
2. ## Quicknode Services

We utilize QuickNode's RPC and IPFS services to power the NFT creation process:

RPC Service: We use QuickNode's RPC service to interact with the Solana blockchain network efficiently. QuickNode provides reliable and fast access to blockchain data and functionalities.

IPFS Service: QuickNode's IPFS service allows us to store the NFT metadata JSON file and image on the InterPlanetary File System (IPFS). This ensures the metadata is decentralized and easily accessible.

Using QuickNode's IPFS Service
If you'd like to use QuickNode's IPFS service, you can take advantage of a discount with the following code:

Discount Code: BUILD-AMB-5

This code gives you a one-month free trial ($49 value) to explore and test QuickNode's IPFS service.

## Example NFT Metadata

Check out an example NFT metadata and image that we use in this repository:

![Example NFT](https://quicknode.myfilebase.com/ipfs/QmP76NJ7cbPgLNRL2iTcvXdoCuS7z47Ke8ap2YXsJAttNf)

3. ### Go to https://www.quicknode.com/

First, create an account on quicknode.com. Then, create an RPC for the Solana Devnet. After that, go to Storage/Files and upload your JSON file and PNG image. You can use the examples we have here in the repo.

5. ### Go to https://beta.solpg.io/

Now, in SolPG, you can create a new project and set up your wallet. In the configuration, set up a custom RPC and enter your QuickNode RPC URL. Next, you can go to the bottom section and enter these commands to deploy your contract on the Solana Devnet.

PD: You need to have enough Solana tokens on the Devnet to deploy this contract. You should have at least around 10 Solana tokens for this. You can use the SolFaucet website, ask your friends to send you Solana tokens, or you can also use a VPN to request a bit more Solana tokens.

https://solfaucet.com/

Deploying:

```
solana airdrop 3
```
```
build
```
```
deploy
```

6. ### Test

Once you have your program deployed and everything is set up correctly, you should go to the 'Test' option in SolPG to perform the tests. I won't go into detail about how to do the testing here, as you can watch the YouTube video where we explain everything in detail. I'll provide the link to our YouTube channel, and you can search for the corresponding video.

https://youtube.com/c/simplepanas


## License
This project is licensed under the MIT License.

Feel free to explore the code and create your own NFTs on the Solana blockchain using Anchor and QuickNode's services!

For any questions or assistance, please create an issue in this repository.

## Links
https://quicknode.myfilebase.com/ipfs/<CID>
https://docs.metaplex.com/developer-tools/sugar/guides/preparing-assets#-metadata-0json
https://beta.solpg.io/
https://solfaucet.com/
https://explorer.solana.com/address/metaqbxxUerdq28cj1RbAWkYQm3ybzjb6a8bt518x1s