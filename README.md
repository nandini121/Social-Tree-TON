# Social-Tree-TON
# TON Telegram Bot

This project is a Telegram bot that allows users to interact with a smart contract on the TON Blockchain to manage a counter. Users can view and increment the counter directly from Telegram.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Setup and Installation](#setup-and-installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Demo](#demo)
- [Challenges and Solutions](#challenges-and-solutions)
- [Future Work](#future-work)
- [Contributors](#contributors)

## Introduction

This project demonstrates the integration of a Telegram bot with the TON Blockchain. The bot allows users to view and increment a counter stored on the blockchain.

## Features

- Fetch the current counter value from the blockchain.
- Increment the counter value.
- Interact with the smart contract through Telegram.

## Prerequisites

- Node.js and npm
- Docker Desktop
- TON Client SDK
- Telegram account

## Setup and Installation

### Step 1: Clone the Repository

```sh
git clone https://github.com/your-username/ton-telegram-bot.git
cd ton-telegram-bot
###Step 2: Install Dependencies
npm install
Step 3 :Set up Docker
## Download and install Docker Desktop from the official website. After installation, ensure Docker is running.
###Step 4:Set Up TON OS SE
sh
git clone https://github.com/tonlabs/tonos-se.git
cd tonos-se
docker-compose up
###Step 5:Create a Telegram Bot
1.Open Telegram and search for BotFather.
2.Start a conversation with BotFather and follow the instructions to create a new bot.
3.Note down the API token provided by BotFather.
###Step 6: Configure the Bot
###Create a .env file in the root directory of the project and add the following:
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
TON_CONTRACT_ADDRESS=your_smart_contract_address
TON_CONTRACT_ABI=path_to_your_contract_abi.json
###Step 7:Start the Bot
npm start
