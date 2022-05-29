# 3aaN9FpvrSIEpTzs
This repository aims to establish a robust intelligent system to aid the company's value investing efforts using stock market data. 
The work contains two main steps. The first step is to build a model to forecast prices. The second step is to build a recommender system to recommend to the company either to Buy, Sell or to Hold.
The methodoly that I worked with was as followed:
* Read and explored the data
* Visulized data with multi plots techniques
* Preprocessed the data
* Used 4 main models for the modeling part:
* 2 statistical models(Arima and Arimax)
* 2 deep learning models (LSTM and GRU). I also tunned their hyperparamters with two techniques (the classical one and using Hyperopt method)
* Compared forecasting results
* Used Bollinguer Bands thecnique to visualize my forecasting prices
* Build a recommender system to recommend to the company either to Buy, Sell or Hold actions.
* Labeled the data set based on the cross points in the forecasting plot
* Balanced the dataset using SmoteTomek method
* Used 4 tree based models (RandomForest, XGBoost, LightGBM, CatBoost models) as well as the stacking ensembling method.
* Used Hyperopt to optimize their hyperparams
* Compared all resuls using classification reports, based on the accuracy score.

## Results:

From my results, the best model for the forecasting step was ARIMAX with an MAPE= 0.009074110787921856, compared to other used models. That means that it's about 91% aaccurate. Also for the recommendation step, The CatBoot model was the best with an accuracy equal to 69.96 %, compared to other used models.

I should notice that the statistical model ARIMAX outperformed deep learning models. This improve that neural networks are not always good for all tasks. We should have enought data to use them.
