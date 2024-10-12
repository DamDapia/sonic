# Soniclabs Arcade Testnet BOT

About Sonic Labs (Prev Fantom)

- Register: [https://airdrop.soniclabs.com/](https://airdrop.soniclabs.com/?ref=kfpbi7 )
- Connect Wallet to Sonic Testnet
- Enter Access Code: `kfpbi7`
- Get Faucet : <https://testnet.soniclabs.com/account>

## Features

- Support multi accounts.
- Support private key and mnemonic.
- Support Proxy for each account.
- Auto play games daily.

## Prerequisite

- Git v2.13 or later
- Node.js v18 or later

## Steps

- Get faucet $S token from <https://testnet.soniclabs.com/account>
- After you get token, play all game at least once!!!

> [Warning]
> REMEMBER TO CLAIM FAUCET WEEKLY

## Installation

### For Linux

1. Open your `Terminal`.

1. clone the repo and install dependencies

   ```bash
   git clone https://github.com/web3bothub/soniclabs-arcade-bot.git
   cd soniclabs-arcade-bot
   npm install
   ```

1. configure your accounts

   ```bash
   cp .env.example .env
   vim .env
   ```

1. start the bot

    ```bash
    npm run start
    ```

### For Windows

1. Open your `Command Prompt` or `Power Shell`.
1. clone the repo and install dependencies

   ```bash
   git clone https://github.com/web3bothub/soniclabs-arcade-bot.git
   cd soniclabs-arcade-bot
   npm install
   ```

1. Navigate to `soniclabs-arcade-bot` directory.
1. cp `.env.example` to file `.env`
1. Now open `.env` and config your account private key or mnemonic, and optionally you can add proxy for each account.
1. Back to `soniclabs-arcade-bot` directory.
1. In your `Command Prompt` or `Power Shell`, run the bot:

    ```bash
    node src/index.js
    ```

## Keep bot up to date

To update bot, you need to pull the latest code from this repo and update the dependencies

1. pull the latest code

   ```bash
   cd soniclabs-arcade-bot
   git pull
   # or
   git pull --rebase
   ```

   if you got conflict, you can stash your changes and pull again:

   ```bash
   git stash && git pull
   ```

1. update dependencies

   ```bash
   npm update
   ```

1. restart the bot

   ```bash
   npm run start
   ```

## Note

- Run this bot will update your referrer code to my invite code if you don't have one.
- Run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purpose only.

## Contribution

Feel free to contribute to this project by creating a pull request.

## Support Me

if you want to support me, you can donate to my address:

- EVM : `0xa2f5b8d9689d20d452c5340745a9a2c0104c40de`
- SOLANA : `HCbbrqD9Xvfqx7nWjNPaejYDtXFp4iY8PT7F4i8PpE5K`
- TON : `UQBD-ms1jA9cmoo8O39BXI6jqh8zwRSoBMUAl4yjEPKD6ata`
