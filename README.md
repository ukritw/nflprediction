# NFL Games Prediction using Machine Learning

Inspired by [Can You Beat FiveThirtyEight’s NFL Forecasts?](https://projects.fivethirtyeight.com/2018-nfl-forecasting-game/), I wanted to use machine learning with publicly available data to make a **probabilistic forecast** for each NFL game. 

More specifically, these forecast can be used to bet on NFL games and make a consistent profit. We will be focusing on the **line bet** by simply selecting the winners (different from betting on the spreads). 

It is important that the models give us a confidence probability of the winners so that we can decide whether to use the prediction or not. For example, if the model predicts for a particular game that the Minnesota Vikings have a 52% chance of winning, we might not want to place a bet on this. On the other hand, if the model is 90% confident that the Minnesota Vikings will win, we should consider placing a bet (given that the overall performance of the model is "good").

### Data Sources
* Elo Data - https://github.com/fivethirtyeight/data/tree/master/nfl-elo
* NFL historic game and betting info - https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data/home
