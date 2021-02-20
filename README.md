# DQN_PairTrading

Algorithmic Trading of Stock Pairs using Deep Reinforcement Learning.

Two stocks (preferrably in the same sector/industry) are used in this Deep Q network model for simpilicty.

We have a five day moving average period whose value is used to determine whether to perform trade actions such as buying and selling.
Rewards are based on how each action affects our portfolio value.

Note that this doesn't take transaction costs into account.
