# ALGOPACK-Extra-Market-Data
Extra Market Data from MOEX for RUSSIA Stocks

Here is the link to kaggle dataset [ALGOPACK Extra Market Data](https://www.kaggle.com/datasets/olegshpagin/algopack-extra-market-data) (quarterly updates by requests in comments)

**Super Candles - 5 minute super candles, 50+ parameters.** History since 2020

DESCRIPTION OF THE DATASET
Class|Metrics|Des (all metrics are calculated over a period of 5 minutes)
| --- | --- | --- |
reference|secid|at the instrument
reference|ts|date and time
trades|pr_open|opening price
trades|pr_high|maximum price for the period
trades|pr_low|minimum price for the period
trades|pr_close|last price for the period
trades|pr_vwap|weighted average price
trades|pr_change|price change over the period, %
trades|trades|number of transactions
trades|vol|volume in lots
trades|val|volume in rubles
trades|disb|ratio of purchases and sales
trades|pr_std|standard deviation of price
trades|pr_vwap_b|weighted average purchase price
trades|pr_vwap_s|weighted average selling price
trades|trades_b|number of purchase transactions
trades|trades_s|number of transactions for sale
trades|vol_b|volume of purchases in lots
trades|vol_s|sales volume in lots
trades|val_b|volume of purchases in rubles
trades|false|sales volume in rubles
orders|put_orders|number of placed orders per glass
orders|cancel_orders|number of canceled applications
orders|put_vol|volume of wafers placed in a glass
orders|put_val|volume of wafers placed in a glass (rub)
orders|cancel_vol|volume of withdrawn orders
orders|cancel_val|volume of withdrawn orders (RUB)
orders|put_orders_b|number of submitted orders (purchase)
orders|put_orders_s|number of submitted orders (sale)
orders|cancel_orders_b|number of canceled orders (purchase)
orders|cancel_orders_s|number of canceled orders (sale)
orders|put_vol_b|volume of wafers placed in a glass (purchase)
orders|put_vol_s|volume of drinks placed in a glass (sale)
orders|cancel_vol_b|volume of withdrawn orders (purchase)
orders|cancel_vol_s|volume of withdrawn orders (sale)
orders|put_val_b|volume of wafers placed in a glass (purchase, rub)
orders|put_val_s|volume of wafers placed in a glass (sale, rubles)
orders|cancel_val_b|volume of withdrawn orders (purchase, rub)
orders|cancel_val_s|volume of withdrawn orders (sale, rub)
orders|cancel_vwap_b|Weighted average price of canceled orders (purchase)
orders|cancel_vwap_s|Weighted average price of canceled orders (sale)
orders|put_vwap_b|Weighted average bid price (purchase)
orders|put_vwap_s|Weighted average bid price (sale)
orderbook|spread_bbo|spread between best bid and ask price
orderbook|spread_lvl10|spread between the 10th level of bid and ask prices
orderbook|spread_1mio|spread of 1 million rubles
orderbook|levels_b|number of price levels in the order book (purchase)
orderbook|levels_s|number of price levels in the order book (selling)
orderbook|vol_b|total volume of orders in the order book at all levels (buy)
orderbook|vol_s|total volume of orders in the order book at all levels (sale)
orderbook|val_b|total volume of orders in the order book at all levels (buy), RUB
orderbook|false|total volume of orders in the order book at all levels (sale), rub
orderbook|imbalance_vol_bbo|volume imbalance at best prices
orderbook|imbalance_val_bbo|volume imbalance (RUB) at the best prices
orderbook|imbalance_vol|volume imbalance on the entire glass (all levels)
orderbook|imbalance_val|volume imbalance (rub) on the entire glass (all levels)
orderbook|vwap_b|weighted average purchase price in glass
orderbook|vwap_s|weighted average selling price in glass
orderbook|vwap_b_1mio|purchase price of an asset for 1 million rubles
orderbook|vwap_s_1mio|asset sale price for 1 million rubles
