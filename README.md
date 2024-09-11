### Used Car Price Prediction

**Author**
Kevin Joseph

#### Executive summary

#### Rationale
Every day people across the world go to buy and sell used vehicles. As used cars take up a much larger portion of the market than new cars, we must accurately predict the price our vehicles will sell for. To best serve the growing customer base of the used car market, we will create multiple models to predict the cost of a vehicle. This will help customers understand what kind of vehicle they can afford and help people make better financial decisions.
 
#### Research Question
What drives the price of a used car, and can we create a model to accurately predict the cost of a vehicle given information about it?


#### Data Sources
[https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction]([url](https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction))

#### Methodology
To solve this issue we have created 4 different models. Using LinearRegression, DecisionTree, RandomForest, and XGBoost we found a model that can predict the price of a used car with the highest accuracy. To value our models we compared MSE and MAE values to determine which model had the lowest error.

#### Results
The XGBoost Model performed the best with the lowest MAE and MSE.

#### Next steps
The models could use more training as well as tuning of hyperparameters. We also could use more data from different regions to help increase the accuracy of the models.
