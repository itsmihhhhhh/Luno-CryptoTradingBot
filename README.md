# Team Noobot - Cryptotrading Bot 
A trading bot used to monitor the moving average of the current price, bid price and ask price to facilitate trading across a trading exchange platform. 


# Content 
1. Our Trading Bot [(See here)](#Our-Trading-Bot)
2. Our Bot Strategy [(See here)](#Our-Bot-Strategy)
3. Limitations of Our Bot Strategy [(See here)](#Limitations-of-Our-Bot-Strategy)
4. How does our bot work? [(See here)](#How-does-our-bot-work?)
5. Links to different currency pairs traded wih [(See here)](#Link-to-our-different-currency-pairs:)


## Our Trading Bot 
We created a cryptocurrency trading bot by the name of Noobot that helps to facilitate trading on Luno, a trading platform that enables us to successfully buy and trade Bitcoin, Ethereum, XRP and Litecoin. Before starting on our bot, we had to first choose a trading strategy that we wanted to implement in the bot which will be explained in the next section [see below](#Our-Bot-Strategy).


## Our Bot Strategy 
For our trading strategy, we have decided to make use of the moving average line to calculate the best price to trade at. This includes calculating the Moving Average of the current price (MA middle), the bid price (MA low) and the ask price (MA high) at every 15-minute intervals. 

From here, we have devised our bot so that it would be able to monitor the buy-sell process by buying in when there are many people selling such that the current market price is lower and selling at a higher price when there are more people buying in. This is based on the demand and supply of the market where when demand increases for a fixed market supply, price increases and when demand decreases for a fixed amount of market supply, the price would decrease. 

Since the cryptocurrency market is always fluctuating and ever-changing, we have decided to make use of the fact that no matter how high the price goes up, it is bound to decrease and come back down to maintain the level of equilibrium in the market. 

Hence, for our bot strategy, it is stimulated from the three lines in the Bollinger Band indicator (the Upper, Middle and Lower bands) besides our bid price and ask price which would make our bot buysell at a more accurate price. However, as compared to the bollinger band strategy which uses data from the current price, we have also used past data to compare and contrast with. 


## Limitations of Our Bot Strategy
On the downside, though our strategy ensures that the bot buys at a low price and sells at a higher price than bought, because of the frequent fluctuations in price, this might cause the price sold to be slightly lesser than the price bot and might incur small amounts of losses. Therefore, to reduce risk of losses, we decided to trade in small amounts(volumes) and by increasing the trading frequency to a every 15 minute interval.


### How does our bot work? 
We ran our code on the online Google Colab hosted runtime server continuously across a span of a few weeks. Our bot would conduct trades in small amounts in GBP using post limit orders. You may also use post market orders to place an order right away but we feel that the best way to trade for this bot would be to use post limit orders. We had created a total of 6 different trading bots for each type of currency that is currently being traded on the Luno platform. 


### Link to our different currency pairs:
We have successfully traded with the following currency pairs in Luno trading platform by deploying our bot on Google Colab.

1. Trading with currency pair [(BTC-GBP)](./BTCGBP.ipynb)
2. Trading with currency pair [(ETH-GBP)](./ETHGBP.ipynb)
3. Trading with currency pair [(BCH-BTC)](./BCHXBT.ipynb)
4. Trading with currency pair [(ETH-BTC)](./ETHBTC.ipynb)
5. Trading with currency pair [(XRP-BTC)](./XRPBTC.ipynb)
6. Trading with currency pair [(LTC-BTC)](./LTCBTC.ipynb)
