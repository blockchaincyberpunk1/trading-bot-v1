# Ethereum DEX Auto-Swapper

This is a Node.js script that automates the swapping of Ethereum (ETH) for DAI tokens on a decentralized exchange (DEX) using Web3.js and Ethereum smart contracts. The script continuously monitors the price of ETH against DAI and performs a swap when the price meets a predefined threshold.

## Features

- Monitors the price of ETH against DAI on a decentralized exchange.
- Automatically performs a swap from ETH to DAI when the price threshold is met.
- Supports custom polling intervals for price monitoring.

## Requirements

- Node.js (version 12 or higher)
- Web3.js
- Ethereum wallet with sufficient ETH balance
- DAI token in the wallet

## Setup

1. Clone this repository.
2. Install dependencies with `npm install`.
3. Set up your Ethereum wallet and ensure it has ETH and DAI tokens.
4. Configure your Ethereum wallet address in the `.env` file.
5. Run the script with `npm start`.

## Configuration

- Set your Ethereum wallet address in the `.env` file.
- Adjust the `ETH_SELL_PRICE` variable to set the desired price threshold for the swap.

## Usage

Run the script using `npm start`. It will continuously monitor the price of ETH against DAI and perform a swap when the price falls below the specified threshold.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

