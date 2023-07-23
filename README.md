# inventory-management
Implementation of Baseline, Machine Learning (LGBM) and Deep Reinforcement Learning (DQN) in a Inventory Management Problem

In our study it is simplified and assumed that a superstore is selling only one type of product. The superstore has its warehouse with inventory capacity of certain units. Two options are available for the superstore to restock the products: One is pre-order from central warehouse and this would take several days to be delivered; the other is emergency order from a third-party supplier, which will be delivered on the next day. Cost of emergency order will be expensive than pre-order. In the situation that pre-order or emergency order delivery exceeds the capacity of inventory, all of the excess inventory has to be returned and a penalty will be charged to the superstore. On the other hand, if the superstore runs out of inventory stock, the store has to be closed and no revenue can be earned.

The supervised learning approach will use LGBM forecast result to manage inventory and order by proposed algorithm, while reinforcement learning approach aims to create an agent to manage inventory automatically given the environment and stages.
