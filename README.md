# How Data Tells the Story of Blockchain

*Materials for the meetup*

## Installation

Project runs under Jupyter notebook and python 3.8.

Refer to https://jupyter.org/install for instructions.

In addition, you will need to install packages:

* pip install wordcloud
* pip install pandas
* pip install python-dotenv

Next, you need API keys to get data from 2 sources: Bitquery and Cryprorank.


Create .env file in the project root with the variables:

```
BITQUERY_API_KEY=...
CRYPTORANK_API_KEY=...
```

Get Bitquery API key from https://ide.bitquery.io/

Get Cryptorank API key from https://cryptorank.io/api


After run 
```
jupyter-lab
```

from the project root.


## Some query examples

* [Bitcoin TX fees by date](https://ide.bitquery.io/Query-max-tx-hash-value_1)
* [Query max transfers in ETH today](https://ide.bitquery.io/Query-max-transfers-in-ETH-today)
* [Upbit hacker money flow](https://explorer.bitquery.io/ethereum/address/0xa09871aeadf4994ca12f5c0b6056bbd1d343c029/graph?from=2017-03-01&till=2023-03-23)
* [USDT live trades](https://explorer.bitquery.io/ethereum/token/0xdac17f958d2ee523a2206206994597c13d831ec7/token_dex_trades)

