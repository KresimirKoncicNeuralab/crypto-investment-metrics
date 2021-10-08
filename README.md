# crypto-investment-metrics

Stocks, bonds and similar traditional (CeFi) asset classes have tremendous amounts of metrics or tools at their disposal. On the other hand, it is fairly difficult to grasp valuation, price predictability and various ratios in the crypto world. 

The goal of this repo is to analyze and watch over possible cryptocurrency metrics and to shed a light on undervaluation and overvaluation on chosen tokens. For example, I will analyze possible ETH value based on similar token's metrics.

## Market Caps (MC or FDMC)
A fairly standard metric that is used both in CeFi and DeFi world. You can calculate it by multiplying the current price of the asset with the current circulating supply. The trouble starts when you want to calculate the fully diluted market cap (__FDMC__) which takes total possible supply into account. As you guessed, this is fairly straightforward for BTC which is 21M, but rather complex for ETH where there are several current analyses given the EIP-1559 and the future 2022 merge. One of these papers is Justin Drake's ETH suply analysis which predicts peak supply to roughly 120M. Keep note that ETH supply could go to lower numbers as per the burning fees process.

[![Justin Drake's updated ETH sdupply projections](https://github.com/KresimirKoncicNeuralab/crypto-investment-metrics/blob/main/eth-120M-Total-Supply.png)](https://twitter.com/drakefjustin/status/1424039388548321283?s=20)

Here are some MC and FDMC metrics on 26th of Sep 2021

| Token         | Price (USD)   | Market Cap (MC) | Fully Diluted Market Cap (FDMC) |
| ------------- |:-------------:| ---------------:|---------------:|
| BTC           | $ 43,217      | $ 813 B          |   $  907 B          |
| ETH           | $ 3008        | $ 352 B          |   $  361 B          |
| ADA           | $ 2.26        | $  72 B          |   $  102 B          |

_Sources for analysing MarketCap_

https://www.tradingview.com/markets/cryptocurrencies/global-charts/

https://coinmarketcap.com/


## Market Cap by Value Settled (MC/VS)
Stocks have an important P/E ratio which is basically a price of stock divided by earnings per one stock. You can get the same ratio if you divide the market cap with total earnings. P/E ratio is traditionally used to anaylze the undervaluation or overvaluation of one asset. A high P/E ratio means that a stock is overvalued (or that investors are expecting high growth rates in the future).

This kind of analysis is not possible with crypto tokens as blockchain systems do not have earnings, but I will argue here that value settled on-chain is the closest metric for probing the economic value on one blockchain system. I think this is a fair analogy to an operating company's earnings, which unlike revenue, show the real health of one organization

Problem with value settlement is that it is difficult to calculate in the crypto world as not all chains have smart contracts and DeFi layers. Nonetheless, it is the closest metric to the important P/E ratio.

| Token         | Value settled (USD) / Day   | Market Cap (MC) | MC / VS |
| ------------- |:-------------:| ---------------:|---------------:|
| BTC           | $ 11.6 B     | $ 813 B          |   70         |
| ETH           | $ 28.7 B        | $ 352 B          |   12.26         |
| XRP           | $ 0.96 B        | $  44 B          |   45.83          |

Basically, this ratio states that ETH has a potential to grow to **17,174 USD** in market value if it reaches BTC's MC/VS of 70. In other terms this is (70/12.26) * 352B = 2T USD of MC ETH value.

_Sources for analyzing Value Settled_

https://money-movers.info/ 


## Market Cap by Fees Settled (MC/FS)
Fees are an indication of economic activity and they can be used to analyze usage of various blockchains. Total fees can be a strong indicator for which protocols have actual economic activity behind them. i.e. *"Which blockchains are people actually paying to use?"*

Problem with fees settlement is that fees and their part in DeFi layers are complex and not-streightfoward topics. You should take this ratio as more of an experimentation than actual objective metric.

| Token         | Fees settled (USD, 7 day avg)   | Market Cap (MC) | MC / FS |
| ------------- |:-------------:| ---------------:|---------------:|
| BTC           | $ 0.817 M     | $ 0.813 T          |   0.9951         |
| ETH           | $ 37 M        | $ 0.352 T          |   0.00951         |
| ADA           | $ 0.038 M        | $  0.072 T          |   1.8947          |



**TODO**

Lindy effect

Gini coefficient

Fees

MC/Fees

Volatility

Pos ratio

Stakers

Price / Sales
