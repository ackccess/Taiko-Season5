# Taiko Auto Swapper Bot for TRAILBLAZERS SEASON 5 

This is an automated token swapping bot built with Node.js, designed to simulate daily, randomized on-chain activity on the Taiko network. It wraps ETH to WETH, swaps to USDC, and back to ETH in an automated loop, mimicking organic wallet behavior.

<img width="720" height="360" alt="image" src="https://github.com/user-attachments/assets/397ccfdd-1a7e-40ec-a9fa-3fc590507308" />


## Features
- Daily automated transactions with randomized frequency and timing ( Like Human )
- ETH ↔ WETH ↔ USDC swaps using on-chain in DEX IceCreamSwap
- Dynamic delay and transaction range per day (configured via .env)

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Espenzuyderwyk/Taiko-Season5.git
```
```bash
cd Taiko-Season5
```
```bash
npm install
```

## Environment Setup
Create a .env file in the project root:
```bash
nano .env
```
Fill in your wallet details and configure your preferred settings:
```bash
PRIVATE_KEY=0xYour_PrivateKey
TAIKO_RPC=https://rpc.taiko.xyz

# you can change
MIN_TX_PER_DAY=20
MAX_TX_PER_DAY=50

# you can change
MIN_DELAY_MINUTES=1
MAX_DELAY_MINUTES=9

# you can change
MIN_ETH_AMOUNT=0.0001
MAX_ETH_AMOUNT=0.0009
```

## ▶️ Running the Bot
To start the bot:
```bash
node index.js
```

## Goal
Maximize your engagement with the Taiko ecosystem and boost your chances of earning more rewards from trailblazers Season 5 — automatically.

## Disclaimer

This script is created for educational and personal experimentation purposes. It is not to be used for illegal activities, spam, or violations of GitHub rules.

- Use of this script is entirely the responsibility of the user.
- Do not use it to violate GitHub's Terms of Service.

## Tags
#trailblazers #airdrop #swap #bot #crypto #web3 #automation #trading #taiko
