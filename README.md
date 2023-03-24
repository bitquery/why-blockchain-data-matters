# Why Blockchain Data Matters

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

* [https://ide.bitquery.io/Query-max-tx-hash-value_1](Bitcoin TX fees by date)
* [https://ide.bitquery.io/Query-max-transfers-in-ETH-today](Query max transfers in ETH today)



