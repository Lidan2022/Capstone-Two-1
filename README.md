                                                    ![BUY OY NOT?](https://images.app.goo.gl/mVuAVwnfpqNrdSEeA)                                                   

#                                                              How to predict a single stock buying signal 
### The Stock market process is full of uncertainty. The price is affected by many factors. However, the Stock market prediction is one of the important factors in finance and business.The goal of this project is to analyze the google company historical stock data in Python, build a machine learning model to predict the google stock buying signal. The model can be an indicator for the investor to decide whether to buy or not. It is beneficial for companies and individuals to make proper investment decisions
## 1.Data Collecting
### Kaggle is the world's largest data science community with powerful tools and resources. From Kaggle, We collected this sufficient size of dataset to build a good predictor model. Here is the link of the data source: https://www.kaggle.com/datasets/dgawlik/nyse
## 2.Data Cleaning
### Capstone Two New-Data Wrangling.ipynb For data wrangling, we checked the basic information about the dataset. Handled the missing and duplicated values. Rename some column names to make them more readable. Capstone Two New-Data Wrangling.ipynb
## 3.EDA
### Capstone Two New-EDA.ipynb  For Data exploratory analysis, We visualized the 'open' and 'close' columns have incresing trend. Discovered there are three peaks from 'open', 'high', 'low' and 'close' dates. the 'Volume' column data is a little bit left-skewed and contains outliers. We added quarter column and grouped them by year.We can tell the stock price had an increasing trend since 2010 to 2016 from the histgrams.Then we added some columns for feature columns and separate our target value. From the heatmap, we can see that there is a high correlation between ''open','close','low', and 'high' columns. The added features are not highly correlated with each other or previously provided features. This means we are good to go and build our model.
## 4.Algorithms & Machine Learning
### Capstone Two New-Modeling.ipynb  Now we started to build our machine learning model. After preprocessing and transforming our data, we evaluated three different models. The RandomForest model perform the best. So we targeted on this model and did the parameter tunning. However, The accuracy achieved by the model is less than 48%.
## 5.Conclusion & Future improvement
### The reasons caused low accuracy might be the lack of data or using a very simple model to perform such a complex task as Stock Market prediction. So we need more data and more powerful model to predict a single stock buying signal.
