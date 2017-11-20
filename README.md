[![](https://discordapp.com/api/guilds/296098252900794369/widget.png)][1]
[![](https://img.shields.io/badge/discord-bot-invite-blue.svg)][2]

# About Botcoins
Botcoins is a discord chat bot designed to feed you with crypto information. The bot sources data from various places such as CoinMarketCap, Coinbase, Bitpay, Bitfinex and Bittrex (and more in the future.) We support most currencies that are listed on CoinMarketCap.

# How do I add Botcoins to my Discord Server/Guild?
[Click on this link][2]

## Helpful information
* [This page](https://botcoins.github.io/v2-docs)
* [Support Discord Server][1]
* I am always opened to suggestions! Shoot me a message on Discord or submit an [issues](https://github.com/Botcoins/v2-docs/pulls) here.

# Getting Started - Generic Cryptos
## See the price of a coin
![](https://i.imgur.com/Fba8rwt.png)

## See the price of a coin compared to another
![](https://i.imgur.com/HlaPC5h.png)

### > At a specific amount of the coin
![](https://i.imgur.com/PR0bPCu.png)

# Frequently Asked Questions (FAQ)
## How do I open the help menu?
Ahh the first step to helping yourself! Do `$chelp` for a list of commands and do `$chelp command` for the details.

![](https://i.imgur.com/4GVeq4q.png)

## How do I make Botcoins show a certain coin's prices in the nickname?
By default, Botcoins shows the `BTCUSD` pair, just do `$cconfig enablenickstatus` to activate this function.

* If you want to change `BTC` to another coin, for example Ethereum, do `$cconfig setcoin ETH`
* If you want to change `USD` to another fiat currency, such as the Euro, do `$cconfig setfiat EUR`

### Warning
This function creates a lot of audit log entries. ![like this](https://i.imgur.com/gay5Hra.png)

## How to I view the price chart?
Easy, just do `$cgraph BTC` if you're looking for `BTC`, otherwise replace it with something like `XMR` or `ETH`.

![](https://i.imgur.com/fGRzax5.png)

![](https://cdn.discordapp.com/attachments/296098470434045954/381377808934371328/botcoins-ohlc-chart-7d-monero-1678886.png)

# Migration
Old commands from botcoins prefixed with `btc.` are now prefixed with `$cbtc`

## Example: Old
![](https://i.imgur.com/BIy7HXd.png)

## Example: New
![](https://i.imgur.com/fiRxcan.png)

[1]: https://discord.gg/Rcp9sEJ
[2]: https://discordapp.com/oauth2/authorize?scope=bot&client_id=345450194613043201&permissions=67387456
