# Cryptocurrencies

## Overview

The client - Accountability Accounting - is interested in offering a new cryptocurrency investment portfolio for its customers and has requested a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

We will use unsupervised learning since there is no known outputs for these data. Specifically, we will use a clustering algorithm to group the varios cryptocurrencies being evaluated. 

## Results

Five hundred and thirty two tradable cryptocurrencies were evaluated. Using an Elbow Curve to determine the best K value, we decided that four was the appropriate number of clusters to create. The K-Means model returned the following groupings for our cryptocurrencies:

- Group 0:    285
- Group 1:      6
- Group 2:      1
- Group 3:    240

## Summary

These results make clear that their two groups hold the vast majority of cryptocurrencies and the other two groups are comprised of outliers. The two main groups are divided nearly evenly. 