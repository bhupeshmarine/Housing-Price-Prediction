# Housing Price Prediction 
# Description
In this project I analysed and predicted housing value in a volatile market over a four years window. The dataset is from kaggle.com, including the characteristics of sold houses and the microeconomics indexes. While cleaning the data, we use ggplot to plot variables, making 24 graphs (including one interactive plot). We use Multivariate Imputation by Chained Equations (mice), for missing variables imputation. Finally we run a random search XGBoost with 1000 draws to find the best model, which outperforms simple regression by about 50 percent.
