# Cricket Match Win Prediction
(American Express Campus Bowl Challenge)

## About
This project predicts the winner of future T20 cricket matches based on the previous statistics given. For previous stats, we have used three datasets - Match data, Batsman data and Bowler data. Using these, we have done Feature Engineering to create the features that impact the result of the match. Also, we have used SHAP feature importance tool to segregate the best features that give the highest accuracy to predicting the match winner.

## Model Used
We were allowed to use only Boosting algorithms - XGBoost, Catboost, LGBM, GBM. We used all the four and also a combination of ensemble models. We found that Catboost model was giving the best accuracy in our test split of the data.
