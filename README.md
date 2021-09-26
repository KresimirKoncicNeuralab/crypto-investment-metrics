# crypto-investment-metrics

Stocks, bonds and similar traditional (CeFi) asset classes have tremendous amounts of metrics or tools at their disposal. On the other hand, it is fairly difficult to grasp valuation, price predictability and various ratios in the crypto world. 

The goal of this repo is to analyze and watch over possible cryptocurrency metrics and to shed a light on undervaluation and overvaluation on chosen tokens.

## Market Caps (MC or FDMC)
A fairly standard metric that is used both in CeFi and DeFi world. You can calculate it by multiplying the current price of the asset with the current circulating supply. The trouble starts when you want to calculate the fully diluted market cap (__FDMC__) which takes total possible supply into account. As you guessed, this is fairly straightforward for BTC which is 21M, but rather complex for ETH where there are several current analyses given the EIP-1599 and the future 2022 merge. One of them is Justin Drake's ETH suply analysis which predicts peak supply to roughly 120M. Keep note that ETH supply could go to lower numbers as per the burning fees process.

[![Justin Drake's updated ETH sdupply projections](https://github.com/KresimirKoncicNeuralab/crypto-investment-metrics/blob/main/eth-120M-Total-Supply.png)](https://twitter.com/drakefjustin/status/1424039388548321283?s=20)

Here are some MC and FDMC metrics on 26th of Sep 2021

| Token         | Price (USD)   | Market Cap (MC) | Fully Diluted Market Cap (FDMC) |
| ------------- |:-------------:| ---------------:|---------------:|
| BTC           | $ 43,217      | $ 813B          |   $  907B          |
| ETH           | $ 3008        | $ 352B          |   $  361B          |
| ADA           | $ 2.26        | $  72B          |   $  102B          |

_Sources for analysing MarketCap_

https://www.tradingview.com/markets/cryptocurrencies/global-charts/

https://coinmarketcap.com/


## Market Cap by Value Settled (MC/VS)
Stocks have an important P/E ratio which is basically a price of stock divided by earnings per one stock. You can get the same ratio if you divide the market cap with total earnings. P/E ratio is traditionally used to anaylze the undervaluation or overvaluation of one asset. A high P/E ratio means that a stock is overvalued (or that investors are expecting high growth rates in the future).

This kind of analysis is not possible with crypto tokens as blockchain systems do not have earnings, but I will argue here that value settled on-chain is the closest metric for probing the economic value on one blockchain system. I think this is a fair analogy to an operating company's earnings, which unlike revenue, show the real health of one organization

Problem with value settlement is that it is difficult to calculate in the crypto world as not all chains have smart contracts and DeFi layers. Nonetheless, it is the closest metric to the important P/E ratio.

_Sources for analyzing Value Settled_

https://money-movers.info/ 

TODO
Fees
MC/Fees
Volatility
Pos ratio
Stakers
