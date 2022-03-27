# Tradingview Webhook Crypto Bot

trading-view-webhook-crypto-bot is a trading pot that allows users to place trades using Tradingview's webhook alerts. 
There is also a simple dashboard to help you monitor your recent trades.

<img src="img/preview.PNG" alt="preview" width="470"/>

## Quickstart Using Python

This process assumes you have Python (3) installed.

```
# if you don't already have virtualenv installed
pip install virtualenv

# initialize the virtual environment
python -m virtualenv env

# your activate script may be in a slightly different location
source env/Scripts/activate

# install dependencies
pip install -r requirements.txt
```

After installing the pre-requisites, start the app on default port `localhost:500`

```
python app.py
```

After the app starts, navigate to the URL identified by your console.
