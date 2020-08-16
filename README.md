# Team Noobot - Cryptotrading Bot 
A trading bot used to monitor the moving average of the current price, bid price and ask price to facilitate trading across a trading exchange platform. 

## Our Trading Bot 
We created a cryptocurrency trading bot by the name of Noobot that helps to facilitate trading on Luno, a trading platform that enables us to successfully buy and trade Bitcoin, Ethereum, XRP and Litecoin. Before starting on our bot, we had to first choose a trading strategy that we wanted to implement in the bot which will be explained in the next section [see below](#Our Bot Strategy).

## Our Bot Strategy 
For our trading strategy, we have decided to make use of the moving average line to calculate the best price to trade at. This includes calculating the Moving Average of the current price (MA middle), the bid price (MA low) and the ask price (MA high) at every 15-minute intervals. 

From here, our bot will monitor the buy-sell process by buying in when 

### How does our bot work? 
We ran our code on the online Google colab server continuously across a span of a few weeks. Our bot would conduct trades in small amounts at post limit orders. We had created a total of 6 different trading bots for each type of currency that is currently being traded on the Luno platform. 

### Link to our different currencies:
1. Trading with currency pair [(BTC-GBP)](./BTCGBP.ipynb)
2. Trading with currency pair [(ETH-GBP)](./ETHGBP.ipynb)
3. Trading with currency pair [(BCH-BTC)](./BCHXBT.ipynb)
4. Trading with currency pair [(ETH-BTC)](./ETHBTC.ipynb)
5. Trading with currency pair [(XRP-BTC)](./XRPBTC.ipynb)
6. Trading with currency pair [(LTC-BTC)](./LTCBTC.ipynb)
