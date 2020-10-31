# CMU-Africa: Fighting Fire with Data
### Competition held on _Oct. 31, 2020_

## Brief summary
The task consisted in predicting the percentage of area burnt for over specific periods of month using the dataset provided. To solve the regression problem, I essentially did some feature engineering, combining some features together and applying functions to others to draw more insights (exp, log, x^2, etc.). By proceeding like that, I was able to get a RMSE of 0.23 on the public leaderboard with the RidgeCV algorithm.

A series of boosting algorithms have then been tried and then stacked with the linear regression model to achieve the final position on the leaderboard. 

A few more feature engineering would certainly have yielded positive results along with hyperparameter tuning that I could not finish on time due to time constraints.
