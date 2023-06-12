# BollingerZscoreCandleStrategy: High-Frequency Trading Algorithm
Welcome to BollingerZscoreCandleStrategy - a comprehensive trading algorithm, designed for investors pursuing high-frequency trading. This repository contains a unique trading strategy that combines the principles of Bollinger Bands, Z-score, and Consecutive Candles. It targets small but frequent profits on shorter time scales, making it ideal for high-frequency trading scenarios.

Repository Contents
This repository holds the code of a combined trading strategy that integrates the tactics of Bollinger Bands, Z-score, and Consecutive Candles. The code is set up to operate with an initial capital of $100,000, but it can be easily adjusted to suit your trading capital and risk tolerance.

Strategy Overview
Bollinger Bands Strategy: This approach uses the Moving Average Length, Standard Deviation Multiplier, Z-Score Threshold, and Stop Loss Percentage to define entry and exit conditions.
Consecutive Candles Strategy: This strategy, dictated by the number of Consecutive Candles and Risk Percent per Trade, identifies supply and demand zones based on the occurrence of consecutive bullish or bearish candles.
The combined strategy takes long or short positions as indicated by either the Bollinger Bands or the Consecutive Candles strategy, provided no existing position conflicts. Exit conditions and stop losses are also defined for both long and short positions.

Application
This trading strategy is designed for high-frequency trading, exploiting minute fluctuations in the market to extract small but consistent profits. It operates effectively on a shorter time scale, making multiple trades within a very short time frame.

Important Note
This trading strategy, like all trading strategies, should be used as part of a well-rounded risk management framework. Always perform your due diligence and testing before deploying any trading algorithm in a live environment.
