---
title: Bachelor's Thesis
category: Research
tags: [University, Computational Finance, Trading, Python]
date: 2024-05-01
---

My Bachelor’s Thesis is titled "Inventory Forecasting in the Crude Oil Market with Machine Learning", it involves taking the U.S. Crude Oil Inventories weekly announcement and forecasting both the inventory value itself as well as the market movement following the event using a neural network that takes multiple features including natural language such as breaking financial news headlines into account to improve forecasting accuracy of U.S. Supply levels of Crude Oil.

![EIA Release Numbers & Market Movement on October 18th 2023.](../images/post-images/eia-release.png)

Energy Information Administration (EIA) or the American Petroleum Institute (API) are the main organisations that release weekly data surrounding oil supply. This research will use the EIA’s weekly reports on crude oil inventories, which offer insights into U.S. oil supply levels on a weekly basis. We will also leverage the preliminary report, the API’s weekly reports. The API report provides an early indication of inventory changes that can influence market expectations and assist investors in gauging the balance between supply and demand in the crude oil market.

By using modern neural network-based models, such as Transformers and Long Short-Term Memory (LSTM) models we will aim to forecast future crude oil supply release numbers using features stemming from time series data, the API report and breaking financial news headlines to assist in calculating the predicted supply levels.