# Corners Predictions

In this project, a Random Forest Regressor was trained on data from football matches to predict whether there would be over or under a set amount of corners in a certain match. One could then place a stake on the match. 341 matches were predicted, and 341 units were available to stake.

A Poisson distribution was used to estimate the number of corners in a game, and the over/under probabilities. These were then compared to the implied probabilities set by the hypothetical bookmaker in this case, and the Kelly Criterion was used to size the stake. 
