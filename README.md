# Yes-bank-stock-closing-price-prediction

## **Project Summary -**

Yes Bank is a banking company that was founded in 2004 that offers a wide range of differentiated products for its corporate and retail customers through retail banking and asset management services. It is also a publically traded company. That provides an opportunity for anyone to invest in Yes bank and become a shareholder. But at the same time, it means that the valuation of the company is now in the hands of investors and speculators as share prices are often heavily impacted by public opinion. We have used yes bank stock price data set. This dataset contains 5 different features that can be used for predicting close price prediction using machine learning. We have built machine learning regression model for price prediction. We have used some of best models.

## **Problem Statement**

Yes Bank, a prominent institution in the Indian financial sector, gained attention in the media since 2018 due to the fraud case linked to Rana Kapoor. Given this context, it becomes intriguing to analyze the influence of this incident on the bank's stock prices and evaluate the efficacy of time series models or other predictive models in capturing such complex situations. The dataset at hand encompasses monthly stock prices of Yes Bank since its establishment, featuring details like monthly closing, opening, highest, and lowest stock prices.

## **Conclusion**

By leveraging data visualization techniques on our target variable, we discerned a noticeable impact on stock prices during the period of the 2018 fraud case involving Rana Kapoor, where a significant and dramatic decline is evident. Upon loading our dataset, a thorough examination revealed an absence of null values and duplicate entries, ensuring the data's integrity. While outliers were identified in our features, the limited size of the dataset prompted caution against their removal to prevent information loss. The positive skewness observed in the distribution of all variables led us to apply power transformations, enhancing the suitability of the data for modeling purposes.

The strong correlation between the dependent and independent variables signals a dependency that facilitates accurate predictions of the dependent variable based on the features. However, we noted a substantial correlation among independent variables, indicative of multicollinearity. Given the small dataset, addressing this multicollinearity proves challenging yet inevitable. Several models were implemented to predict the closing price, and notably, all models exhibited commendable performance. The Ridge regressor stood out as the top-performing model, achieving an impressive R2 score of 0.994383. Its prowess extends to consistently high scores across various evaluation metrics, underscoring its effectiveness in capturing the underlying patterns within the dataset.
