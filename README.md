# 🚀 Twitter Keyword-Triggered Token Buyer Bot

### 1️⃣ Install Dependencies

```
npm install
```

At the moment, npm is already installed, so don’t worry about it.

### 2️⃣ Configure Environment Variables

Create a .env file:

```
WALLET_PRIVATE_KEY =

QUICKNODE_RPC_URL =
JUPITER_API_BASE =

RAPID_HOST_NAME =
RAPID_API_KEYS =

ASTRALANE_URL =
ASTRALANE_API_KEY =

PUSHOVER_API_TOKEN =
PUSHOVER_USER_KEY =

MONITOR_USER1 = 'elonmusk'
MONITOR_KEYWORD1 = 'coin'
MONITOR_CA1 = 'EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v'
MONITOR_BUY_AMOUNT1 = 0.0002

MONITOR_USER2 = 'elonmusk'
MONITOR_KEYWORD2 = 'solana'
MONITOR_CA2 = 'EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v'
MONITOR_BUY_AMOUNT2 = 0.0001

SLIPPAGE_TOLERANCE = 100    # 1%

LOOP_TIME = 100
```

If you want to trigger more accounts, you can add the user, keyword, token CA, and buy amount in the .env file as shown above, increasing the index number accordingly.

### 3️⃣ Run the Bot

```
npm start
```

### 4️⃣ Stop the Bot

In the terminal, pressing `Ctrl + C` will instantly stop the bot.

## 📲 Example Pushover Notification

You can receive notifications through your Pushover app.

```
🚀 Trade Executed!
Account: @elonmusk
Keyword: launch
Token: $YOURTOKEN_CA
Amount: 1.5 SOL
Transaction: https://solscan.io/tx/xxxxxxxx
```
