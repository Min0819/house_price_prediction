# House Sale Price Analysis and Prediction based on Regression Algorithm
## Conclusion
This project contains two parts including data analysis and house price prediction. Firstly, the distribution of house price was studied and hypothesis testing was proposed to verify the distribution. Then the project visualized data to explore the relationship between attributes of houses. Furthermore, 9 regression models were put forward to predict the SalePrice of house at first. Based on this, this report deigned an weight averaged model containing support vector regression and kernel ridge regression to get a result which is better than any individual model. To improve accuracy more, stacking strategy was applied to train models and improved cross validation accuracy up to 90%. Eventually, this model was used to predict the sale price of house in test data which realized root mean squared error 9.45%.

1. Applied log function to house sale price and drew a Quantile-Quantile plot to compare the shape of normal distribution and house price distribution using Seaborn.
2. Visualized the data to explore the relationship between features and house SalePrice using Matplotlib.
3. Used LabelEncoder to process categorical features and did Principal Component Analysis (PCA) to reduce data dimensionality.
4. Designed a weight averaged model using support vector regression and kernel ridge regression to predict house sale price which achieves accuracy up to 90%.
5. Utilized stacking strategy to build a model including ridge regression, lasso regression, support vector regression, elastic-net regression, Bayesian ridge regression and kernel ridge regression to predict house sale price and reduced root mean squared error to 9.45%.

