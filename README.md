Easybot
=======

### Introduction

Easybot is a trading tool able to load, save and draw candles from various sources. At today it supports fetching trades from Bitcoincharts.com and Btce.com as well as loading previous calculated candles from CSV files. Additionally I've added the possibility to backtest an EMA crossing strategy and the possibility to search for best EMAs combination.

This software was mainly inspired by this two projects:

[Gekko Trading Bot](https://github.com/askmike/gekko)

[tAPIbot](https://github.com/askmike/gekko)

While I was trying to understand some issues with this softwares, I found myself in need of some visual aid. While it's functional to understand some aspects of trading bots, the source code is quite messy as it was written in a few days.

![easybot screenshot](https://raw.github.com/codingdna2/easybot/master/easybot/images/Screenshot01.png "Easybot")

### Source Code

Easybot was developed using C# and Visual Studio 2012. Project uses some external references including:

[migrap/BitcoinCharts](https://github.com/migrap/BitcoinCharts)

[DmT021/BtceApi](https://github.com/DmT021/BtceApi)

[TA-Lib](http://ta-lib.org/)

### Installation

Find the latest release from [here](https://github.com/codingdna2/easybot/blob/master/release/EasyBot_v1.0.zip?raw=true). Unzip the latest version wherever you prefer and run easybot.exe.

### Setup

Please find configuration file named easybot.exe.conf in executable folder

### Known issues

Not all pairs are supported. Due to the usage of BitcoinCharts, pairs availables on BTC-e but not on this one won't be working. I've successfully tested BTC/EUR, BTC/USD and BTC/RUR.
