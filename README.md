# Sniper-Alpha (Telegram Solana Sniper bot)

This project is for sniping tokens on Raydium, Moonshot.
It tracks the migration transaction on Raydium from Pump.fun, Moonshot, and send buy transaction as soon as it's tracked.
It also tracks marketcap using bitquery and if it hits the condition, it will buy & send a message to telegram.
Then do auto-sell according to the marketcap of that token.

## Screenshots

- Token [A6Ny11mGgW5ar5hKStdytBPFJgfNLFY5RY9jW2e5pump](https://solscan.io/token/A6Ny11mGgW5ar5hKStdytBPFJgfNLFY5RY9jW2e5pump)

- Buy Txn:  [3zHC4TPqYKTsp4vuQ6j5MrrTxZsWhN3FNX8ARdYeYEuRBcGgKYQKBPHjLN7MHa68JrMx4ojtuE3PwR9BtinHXLfv](https://solscan.io/tx/3zHC4TPqYKTsp4vuQ6j5MrrTxZsWhN3FNX8ARdYeYEuRBcGgKYQKBPHjLN7MHa68JrMx4ojtuE3PwR9BtinHXLfv)

- Sell Txn: [YjAaqzTw499DJnvbcJhYyrmyDT5LQGX9tewDNpuvfTUadDbpR3RgRQcF89VbCJPQDE4TdcxWNiBfAEHeocWPty8](https://solscan.io/tx/YjAaqzTw499DJnvbcJhYyrmyDT5LQGX9tewDNpuvfTUadDbpR3RgRQcF89VbCJPQDE4TdcxWNiBfAEHeocWPty8)

![image](https://github.com/user-attachments/assets/c7fe7344-e831-454b-a445-d113ea5ada9c)
![image](https://github.com/user-attachments/assets/2f9c7044-7d48-4ffa-a669-660097a57ba1)



## Main features

- Tracking migration transaction on Raydium, Moonshot
- Auto-buy & sell according to the marketcap
- Send message to telegram(Users can set their own configurations via Telegram)

## Tech stack

- Node.js
- Typescript
- Solana/web3.js
- Raydium SDK
- Bitquery API
- Telegram API
- Jito
- Redis

## How to use

1. Clone the repository from github

```sh
git clone https://github.com/btcoin23/Sniper-Alpha.git
```

2. Install dependencies

```sh
yarn install
```

3. Create .env file and edit it.
You need to add `REDIS_URI`, `RPC_URL`, `WSS_URL`, `BOT_TOKEN`, `BOT_ID`, `PRIVATE_KEY`

`.env` file
```sh
REDIS_URI=
RPC_URL=
WSS_URL=
BOT_TOKEN=
BOT_ID=
PRIVATE_KEY=
```
4. Run the project

```sh
yarn start
```
## Author
- [**Github**](https://github.com/btcoin23)

- [**Telegram**](https://t.me/BTC0in23)

