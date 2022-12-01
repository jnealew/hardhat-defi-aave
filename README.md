# Hardhat DeFi Project

I learned all of these skills from Free Code Camp with Patrick Collins as the instructor. I highly recommend checking them out if you are interested in learning about and partaking in this amazing ecosystem as well.  

The purpose of this project has been to fimiliarise myself with Defi. In short, when running this contract, you will be deposited WETH (a wrapped token of Ethereum), you will then deposit the WETH into a lending pool. After depositing, you will earning a small yeild on your deposited amount, then you will be repaid. The amount you are able to lend, borrow, and then the amount you are repaid will be printed in the terminal. Non of this is done on the mainnet, is done via a fork of the mainnet.

This project took some time to learn, and its fair share of obsticals to overcome. But all and all it was a great next step in my learning about blockchain applications.  

Now, onto the project

The focus here has been how to fork the mainnet. 


*This repo has been revamped to work with Goerli. Due to AaveV2 not being deployed on Goerli, it may not work as intended. Please use a mainnet-fork or local network instead of a testnet.*

# Getting Started

## Requirements

- `git --version`
- `node --version`
- `yarn --version`

## Quickstart

```
git clone https://github.com/PatrickAlphaC/hardhat-defi-fcc
cd hardhat-defi-fcc
yarn
```

# Usage

This requires a mainnet rpc provider, but don't worry! You won't need to spend any real money. We are `forking` the mainnet, its a simulation of actually working with the main blockchain. 

In your `.env` file you will need
- `MAINNET_RPC_URL`. You can get setup with one for free[here:](https://alchemy.com/?a=673c802981)

Run:

```
yarn hardhat run scripts/aaveBorrow.js
```

# Running on a testnet or mainnet

1. Setup environment variabltes

You'll want to set your `GOERLI_RPC_URL` and `PRIVATE_KEY` as environment variables. You can add them to a `.env` file, similar to what you see in `.env.example`.

2. Run

```
yarn hardhat run scripts/aaveBorrow.js --network goerli
```# hardhat-defi-aave
# hardhat-defi-aave
# hardhat-defi-aave
# hardhat-defi-aave
