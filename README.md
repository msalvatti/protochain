# Blockchain Prototype Application

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Setup](#project-setup)

## Overview

Welcome to the blockchain prototype application!

This project aims to create a blockchain with miners and wallets.

This application was taken from the LuizTools Web23 training, it was developed for study and uses cryptography resources, an architecture similar to the Bitcoin blockchain.

The class structure with typescript, node.js and tests using Jest were used.

## Features

This application includes the following features:

- Server using API endpoints to process requests from miners and wallets
- Miners who validate blocks and receive rewards for doing so
- Wallets for checking balance and making/search transactions

## Project Setup

To get started with this project, follow these instructions:

1. Clone the repository:

git clone https://github.com/msalvatti/protochain.git

2. Navigate to the project directory:

cd protochain

3. Install dependencies:

npm install

4. Configure .env file:

Use the .env.example file to create .env file, fill the variables according the variables descriptions.

To generate a valid wallet address, run the app wallet with command [npm run wallet] and choose option 1 [Create Wallet].
Copy the private key to use in the .env variable.

5. Run tests:

npm test

6. Run applications:

To run the blockchain server, execute the following command:

npm run blockchain

To run the blockchain miner, execute the following command:

npm run miner

To run the blockchain wallet, execute the following command:

npm run wallet