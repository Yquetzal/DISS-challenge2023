# ML Challenge DISS - 2023

## Challenge organization:
* 9:45 - 10:45: Exploration of the data, Cleaning
* 10:45 - 11:15: Quick Presentation by the teams of what they observed in the data, what they cleaned, etc.
* 11:15 - 12:30: Work on Price prediction
* 12:30 - 13:00: Computation of the best score and presentation by 3 top teams

## Content
You have access to 2 files: 
* challenge_train is a dataset that you can use for training. It contains both features and target
* challenge_test contains only features. You must upload on Discord a csv file in which you fill the Price Column for this data.

## Results
For each file I receive, I will compute the **RMSE** score of price prediction, by comparing with the hidden ground truth. The 3 teams with the highest scores win the right to explain their method to the class!

## Next step
If you want, later in the class, you can submit me new files to see if you manage to improve. I will maintain a leaderboard

## Summary of the features in the used car dataset

| **Feature**                | **Description**                                                                                     |
|----------------------------|-----------------------------------------------------------------------------------------------------|
| Price                    | Price in Dollars                                                     |
| Mileage                    | Represents the total miles driven by the car.                                                       |
| Age                        | The number of years since the car was manufactured.                                                 |
| Brand                      | Brand of the car, as a string                               |
| Horsepower                 | Engine power of the car.                                                                            |
| Accidents History          | Count of the number of accidents the car has been involved in.                                      |
| Last Service Date          | The date of the car's last service in the YYYY-MM-DD format.                                        |
| ID                         | An  identifier for each entry in the dataset.|


## Leaderboard

| **Score**                | **R2**                 |    **RMSE**     |
|----------------------------|--------------|----------------------------|
| Remy Theoretical Highest possible scores | 0.8766 | 2007 |
|Chassin2 |0.727|2636.55|
|Chassin1 |0.650 |2992.93 |
|Halilali|0.574|3298|
|Hoa_Linh |0.407|3891|
| RemyNaiveLinear | 0.112 | 4761.18 |
|Hamlili_Michaloudi |-0.770|6725|
|phin|

* *RemyNaiveLinear* is a naive linear regression on the numerical values, with naive imputation
* *Remy Theoretical Highest possible scores* is the score obtained by using the generative model itself as a predictor. Due to technical reasons, it might not be possible to actually achieve that score, or maybe to beat it: it is only an approximation...

