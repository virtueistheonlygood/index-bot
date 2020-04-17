Index Bot
=========

[VIX Index](http://www.cboe.com/products/vix-index-volatility/volatility-indexes) Telegram bot notifier.

This bot will inform you via Telegram, when a certain threshold limit is reached on the VIX volatility market index (on NYSE).

* [More info about VIX](https://www.veb.net/artikel/06263/7-vragen-over-de-vix-index) (Dutch)

Requirements
------------

* [Node.js](https://nodejs.org/en/download/)
* npm

Usage
-----

Follow the steps:

1. Copy the config template to `config.yml`: `cp configTemplate.yml config.yml`
2. Adjust the configuration settings (optionally), webhook domain and API keys
3. Install depedencies via: `npm install` (once needed)
4. Start the bot using: `npm start`

TODO
----

MACD or PPO with fast: 12, slow 26 and smoothing (signal length) of 9.
Use S&P 500 index, weekly chart and trigger on MACD signal crosses (downtrend and uptrend).

