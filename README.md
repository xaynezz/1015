# SC1015 Mini Project - Understanding Happiness
![image](https://user-images.githubusercontent.com/91424179/164943113-e92d4941-3fa7-42ba-8e4b-9ecf50e5da0f.png)



## About
SC1015 Lab Group SC14 Mini-Project focusing on "World Happiness" datasets from the years 2015-2021.

## Practical Motivation
Our aim is to help countries increase the well-being of their citizens. One way they can do this is by making use of "The World Happiness Report", a publication of the United Nations Sustainable Development Solutions Network. It contains rankings of national happiness, based on respondents' ratings of their own lives, which also correlates with various quality of life factors. 

## Problem Definition
In order to create good policies in the present, how can countries predict and use their world happiness statistics in the future?

## Navigation
1.Download the required files and folders from this repo: `notebooks`, `uncleaned_data`, `plotly` and `requirements.txt`.

2.Run the command `pip install -r requirements.txt` in your jupyter environment.

3.Explore `eda.ipynb`. This notebook includes:
  - Exploratory Data Analysis
  - Machine Learning (Part 1) 
  
4.Explore `cleaning.ipynb`. This notebook includes:
  - Data preprocessing
  - Data cleaning
  - Data exporting
  
5.Explore `machine_learning.ipynb`. This notebook includes:
  - Machine Learning (Part 2)
  - Recommendations

## Conclusion

Overall, we have learnt a lot from this project. We discovered and utilised many new concepts that were not taught to us in labs. We managed to conclude that Autoregression(AR) on Score is the best model for forecasting. However, we also realised that we may have used the wrong approach by trying to utilise time series forecasting, which is not as effective when used on yearly data. This experience has been fruitful, and we will remember these new concepts for other data science projects going forward.

## Libraries Used
- ipython 8.2.0
- matplotlib 3.4.3
- numpy 1.21.2
- pandas 1.3.3
- plotly 5.7.0
- scikit_learn 1.0.2
- scipy 1.8.0
- seaborn 0.11.2
- statsmodels 0.13.2

## Models Used
- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression
- Ridge Regression
- Huber Regression
- Autoregression
- Autoregressive Integrated Moving Average on Score (ARIMA)
- Vector Autoregression (VAR)

## What did we learn from this project?
- Adapting and using concepts taught in lab
  - Correlation Matrix
  - Pair Plot
  - Diagnostic Plot
- Data cleaning concepts
  - Creating 136 datasets after merging 7 datasets
  - Converting dataset from non-time series to time series 
- Representing numeric data as a geographic map in plotly
- New machine learning models and concepts
  - K-Fold Cross Validation
  - Random Forest Regression
  - Gradient Boosting Regression
  - Ridge Regression
  - Huber Regression
- Time Series Forecasting
  - Autoregression
  - Autoregressive Integrated Moving Average on Score (ARIMA)
  - Vector Autoregression (VAR)


## Contributors
Andrew Oak Soe Khant @xaynezz 
  - Code Refactoring, Exploratory Data Analysis, Data Cleaning, Regression Models, Time Series Models, Slides, Video Editing

Oza Tirth Tusharbhai  @Tirth3033 
  - Exploratory Data Analysis, Slides, Presentation

Sisodia Anushka @anushkasisodia  
  - Exploratory Data Analysis, Slides, Presentation

## Acknowledgements
Thanks to Dr Sourav Sen Gupta and TA Song Nan for their teaching and guidance.

## References
- <https://www.kaggle.com/datasets/mathurinache/world-happiness-report>
- <https://plotly.com/python/choropleth-maps/>
- <https://machinelearningmastery.com/k-fold-cross-validation/>
- <https://www.analyticsvidhya.com/blog/2016/02/complete-guide-parameter-tuning-gradient-boosting-gbm-python/>
- <https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/>
- <https://www.machinelearningplus.com/time-series/vector-autoregression-examples-python/>
- <https://towardsdatascience.com/regression-in-the-face-of-messy-outliers-try-huber-regressor-3a54ddc12516>
- <https://towardsdatascience.com/ridge-and-lasso-regression-a-complete-guide-with-python-scikit-learn-e20e34bcbf0b>
- <https://towardsdatascience.com/machine-learning-basics-random-forest-regression-be3e1e3bb91a>
