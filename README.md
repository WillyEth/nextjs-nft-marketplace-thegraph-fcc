

# NextJS NFT Marketplace with TheGraph

## 1. Git clone the contracts repo

In it's own terminal / command line, run: 

```
git clone https://github.com/WillyEth/hardhat-nft-marketplace-fcc
cd hardhat-nextjs-nft-marketplace-fcc
yarn
```
 
## 2. Deploy to rinkeby 

After installing dependencies, deploy your contracts to rinkeby:

```
yarn hardhat deploy --network rinkeby
```

## 3. Deploy your subgraph

```
cd ..
git clone https://github.com/WillyEth/graph-nft-marketplace-fcc
cd graph-nft-marketplace-fcc
yarn
```

Follow the instructions of the [README](https://github.com/WillyEth/graph-nft-marketplace-fcc/blob/main/README.md) of that repo. 

Then, make a `.env` file and place your temporary query URL into it as `NEXT_PUBLIC_SUBGRAPH_URL`.


## 4. Start your UI

Make sure that:
- In your `networkMapping.json` you have an entry for `NftMarketplace` on the rinkeby network. 
- You have a `NEXT_PUBLIC_SUBGRAPH_URL` in your `.env` file. 

```
yarn dev
```
