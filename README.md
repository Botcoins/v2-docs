[![](https://discordapp.com/api/guilds/296098252900794369/widget.png)][1]
[![](https://img.shields.io/badge/discord-bot%20invite-blue.svg)][2]

# About Botcoins
Botcoins is a discord chat bot designed to feed you with crypto information. The bot sources data from various places such as CoinMarketCap, Coinbase, Bitpay, Bitfinex and Bittrex (and more in the future.) We support most currencies that are listed on CoinMarketCap.

# How do I add Botcoins to my Discord Server/Guild?
[Click on this link][2]

## Helpful information
* [This page](https://botcoins.github.io/v2-docs)
* [Support Discord Server][1]
* I am always opened to suggestions! Shoot me a message on Discord or submit a [suggestion here!](https://botcoins.github.io/issue-tracker)

# Getting Started - Generic Cryptos
## See the price of a coin
![botcoins.p](https://i.imgur.com/Fba8rwt.png)

### > In a reduced IRC-styled line
![botcoins.f](https://i.imgur.com/717LzEC.png)

## See the price of a coin compared to another
![botcoins.c](https://i.imgur.com/HlaPC5h.png)

### > At a specific amount of the coin
![botcoins.c amt](https://i.imgur.com/PR0bPCu.png)

# Frequently Asked Questions (FAQ)
## How do I open the help menu?
Ahh the first step to helping yourself! Do `$chelp` for a list of commands and do `$chelp command` for the details.

![botcoins.h](https://i.imgur.com/4GVeq4q.png)

## How do I make Botcoins show a certain coin's prices in the nickname?
By default, Botcoins shows the `BTCUSD` pair, just do `$cconfig enablenickstatus` to activate this function.

* If you want to change `BTC` to another coin, for example Ethereum, do `$cconfig setcoin ETH`
* If you want to change `USD` to another fiat currency, such as the Euro, do `$cconfig setfiat EUR`

### Warning
This function creates a lot of audit log entries. ![like this](https://i.imgur.com/gay5Hra.png)

## How to I view the price chart?
Easy, just do `$cgraph BTC` if you're looking for `BTC`, otherwise replace it with something like `XMR` or `ETH`.

![botcoins.g](https://i.imgur.com/fGRzax5.png)

![example graph output](https://cdn.discordapp.com/attachments/296098470434045954/381960738102706177/botcoins-ohlc-chart-7d-monero-1679041.png)

# Migration
Old commands from botcoins prefixed with `btc.` are now prefixed with `$cbtc`

## Example: Old
![migration.example.old](https://i.imgur.com/BIy7HXd.png)

## Example: New
![migration.example.new](https://i.imgur.com/fiRxcan.png)

[1]: https://discord.gg/Rcp9sEJ
[2]: https://discordapp.com/oauth2/authorize?scope=bot&client_id=345450194613043201&permissions=67387456
