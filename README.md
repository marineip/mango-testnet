# MANGO TESTNET BOT

## Table Of Contents
- [MANGO TESTNET BOT](#mango-testnet-bot)
  - [Table Of Contents](#table-of-contents)
  - [Prerequisite](#prerequisite)
  - [Join My Telegram Channel](#join-my-telegram-channel)
  - [Initverse Incentive Testnet Airdrop](#initverse-incentive-testnet-airdrop)
  - [BOT FEATURE](#bot-feature)
  - [Setup \& Configure BOT](#setup--configure-bot)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Update Bot](#update-bot)
  - [IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)](#important-note-read-it-this-is-not-decoration)
  - [CONTRIBUTE](#contribute)
  - [SUPPORT](#support)

## Prerequisite
- Git
- Node JS (v22)
- Register Mango Testnet Using Creator Reff Code
- Funded Mango Wallet With ETH SEPOLIA and TESTNET BNB

                      
## Initverse Incentive Testnet Airdrop
#New

Mango Testnet 

➡️ Register : [HERE](https://task.testnet.mangonetwork.io/?invite=zqMGvJ)
- Download Mango Wallet (https://chromewebstore.google.com/detail/mango-wallet/jiiigigdinhhgjflhljdkcelcjfmplnd) (Extension)
- Backup Phrase
- Claim Faucet on your wallet extension
- Go To [Web](https://task.testnet.mangonetwork.io/?invite=zqMGvJ) 
- Complete Bind Social Media Accounts and JOIN NOW
- Go to [Event Page](https://task.testnet.mangonetwork.io/events)
- Complete Task on the Task List ( Swap , Bridge )
- Login Daily
- Done

Bot ? Maybe

**LFG**

## BOT FEATURE
- Multi Account 
- Proxy Support
- Daily Claim Faucet
- Daily Mango Swap 
- Daily BeingDex Beta DAPP
- Daily Check In
- Daily Bridge (USDT)

## Setup & Configure BOT

### Linux
1. Clone project repo
   ```
   git clone https://github.com/Widiskel/mango-testnet-bot.git && cd mango-testnet-bot
   ```
2. Run
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. Read the [Note](#important-note-read-it-this-is-not-decoration)
5. Configure the bot config and proxy
    ```
   nano config/config.js
   nano config/proxy_list.js
    ```
6. To run Auto TX
   ```
   npm run start
   ```
   
### Windows
1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repo
   ```
   git clone https://github.com/Widiskel/mango-testnet-bot.git
   ```
   and cd to project dir
   ```
   cd mango-testnet-bot
   ```
3. Run 
   ```
   npm install && npm run setup
   ```
5. Navigate to `mango-testnet-bot` directory. 
6. Navigate to `accounts` directory.
7. Now open `acccounts.js` and setup your accounts. 
8. Now Back to `mango-testnet-bot` directory
9. Read the [Note](#important-note-read-it-this-is-not-decoration)
10. Navigate to `config` directory and adjust the `config.js` and `proxy_list.js` as needed.
11. Back to `mango-testnet-bot` directory.
12. To start the app open your `Command Prompt` or `Power Shell`
13. To run auto Tx Bot
    ```
    npm run start
    ```

## Update Bot

To update bot follow this step :
1. run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. run
   ```
   npm update
   ```
3. start the bot
4. if any eror happen check `log/app.log`


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.

How to get BRIDGE RAW DATA ? 

- Do manual Native Token Bridge (ETH or BNB) from ETH to MANGO WITH SMALL AMOUNT , EX : 0.00001 Token
- Approve Token Spend
- Approve Bridge Tx
- Go to explorer and search for your tx hash showed on your wallet history

ETH SEPOLIA EXPLORER : https://sepolia.etherscan.io/
BSC TESTNET EXPLORER : https://testnet.bscscan.com/
and copy the Input Data as HEX. Or you can just copy paste from wallet confirmation approval on input / data section.

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks.

## SUPPORT

want to support me for creating another bot ?
**star** my repo or buy me a coffee on

EVM : `0x1f0ea6e0b3590e1ab6c12ea0a24d3d0d9bf7707d`

SOLANA : `3tE3Hs7P2wuRyVxyMD7JSf8JTAmEekdNsQWqAnayE1CN`
