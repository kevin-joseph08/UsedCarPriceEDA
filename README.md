### Used Car Price Prediction
![image](https://github.com/user-attachments/assets/0d714ce6-c619-46be-9b7d-bd551beceee1)


**Author**
Kevin Joseph

#### Executive summary

#### Rationale
Every day people across the world go to buy and sell used vehicles. As used cars take up a much larger portion of the market than new cars, we must accurately predict the price our vehicles will sell for. To best serve the growing customer base of the used car market, we will create multiple models to predict the cost of a vehicle. This will help customers understand what kind of vehicle they can afford and help people make better financial decisions.
 
#### Research Question
What drives the price of a used car, and can we create a model to accurately predict the cost of a vehicle given information about it?


#### Data Sources
[https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction]([url](https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction))
![download (2)](https://github.com/user-attachments/assets/0624604d-1220-4aa9-9d4d-1bcc7e78cbd3)
From here we can see a correlation matrix of all of the numerical columns. Horsepower and displacement seem to have the highest impact on price out of our numerical categories.

#### Methodology
To solve this issue we have created 4 different models. Using LinearRegression, DecisionTree, RandomForest, and XGBoost we found a model that can predict the price of a used car with the highest accuracy. To value our models we compared MSE and MAE values to determine which model had the lowest error.

#### Results
The results, pictured below show the differences in each model. We want to look for the model with the lowest MSE as this means we were able to predict the price with the lowest distribution of error. A higher MSE means our predicted prices were off by larger amounts on average while a smaller MSE shows that our model was accurate to a higher degree.

![download (1)](https://github.com/user-attachments/assets/a62e9ca4-7964-4a34-adf3-82312c20541b)

From here we can see that XGBoost performed the best, slightly beating out Random Forest in accuracy, but significantly in both train and test MSE. This however came at the cost of training time. XGBoost took a significantly longer time than any other model to train. It is up to the user whether to use Random Forest or XGBoost depending on what they value more.
#### Next steps
The models could use more training as well as tuning of hyperparameters. We also could use more data from different regions to help increase the accuracy of the models.
