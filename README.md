# Upper-Confidence-Bound-UCB-for-Ad-Selection
This project implements the UCB algorithm, another approach to solving the MAB problem. UCB is a popular algorithm used to balance exploration and exploitation by selecting actions based on the upper confidence bounds of their expected rewards. This ensures that actions with high uncertainty, potentially high rewards are explored more frequently.

KEY FEATURES

Data Import: The dataset used contains click-through data for 10 different ads. Each row represents a user interaction with one of the ads, and the reward indicates whether the user clicked the ad (1 for clicked, 0 for not).

UCB Algorithm: The algorithm calculates the upper confidence bound for each ad and selects the ad with the highest upper bound. It dynamically adjusts the selection process by balancing the exploration of ads with high uncertainty and exploiting ads with high average rewards.

Visualization: A histogram is generated to visualize the number of times each of the 10 ads was selected during the 10,000 trials, showing how the algorithm converges towards the best-performing ads over time.
