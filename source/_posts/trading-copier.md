---
title: Trading Copier
category: Project
tags: [Computational Finance, Trading, Python]
date: 2023-08-01
---

![Trading Copier Thumbnail](../images/post-images/telegram-trading-copier-thumbnail.png)

The Telegram Trading copier was a project built using Python, where **trading signals were extracted from various Telegram channels using the Telegram API, and translated into real trades with a take profit and stop loss**, sending the packet of information to a broker with an API call, making a market or limit order. 

It then keeps track of every trade using an SQL database and decides the next correct move using streams of tick data, processing information every tick for all instruments that currently have a pending order or open position using REST and Streaming APIs. Includes over 10000 lines of code and upwards of 10 active Telegram channels.I've also built a framework for this project to backtest signals using 5s historical candle data.