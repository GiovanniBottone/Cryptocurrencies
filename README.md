# Cryptocurrencies

## Overview
Fictional investment bank, Accountability Accounting, is interested in offering a new cryptocurrency investment portfolio to its clients; however, the company needs help classifying the various cryptocurrencies to identify which they should offer. Senior management has requested a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system.

The current data from Accountability Accounting needs to be cleaned to fit the machine learning models, and since there isn't a known output for what this investment bank is looking for, we'll focus on unsupervised machine learning. The cryptocurrencies will be grouped using a clustering algorithm and the data will be visualized to simplify the findings for board members who are unfamiliar with cryptocurrencies.

## Results
Once the data had been cleaned, 532 tradable crypotcurrencies were been identified. In order to find the best value for K-Means clustering algorithm, an elbow curve was created to determine the number of clusters that should be used. According to our elbow curve, K = 4.

![Elbow Curve](https://user-images.githubusercontent.com/95371617/167268972-bfbae513-9464-4446-9664-ade8fe6d2538.png)


The below 3D scatter chart shows the 532 cryptocurrency dataset, broken into 4 classes or clusters.

![3D Scatter](https://user-images.githubusercontent.com/95371617/167268999-74b683e7-f8f3-4cbb-82d7-30d4239eb12f.png)


The below 2D scatter chart shows each cryptocurrency in comparison to the total coins mined and total coin supply.

![Total Coins Mined](https://user-images.githubusercontent.com/95371617/167269018-a86bd9a7-d43d-400b-876e-4179ef97496b.png)
