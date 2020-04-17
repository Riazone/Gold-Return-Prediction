# Gold-Return-Prediction
I have been a student of financial market for over a decade and have been studying different asset classes and their behavior in different economic conditions. There are very few asset classes which have as polarized opinions as Gold. There people who love it, then few who hate, and more often than not, they remain in the same camp. Since Gold has very little fundamentals of its own (again source of polarization), in this multi-part series I will try to a predict Gold Price returns using several Machine Learning Techniques. Listed below is how I (currently) envisage the series to be:

***Part I   : Defining the approach, gathering and preparing data***
***Part II : Regression modelling using PyCaret***
***Part III: Classification modelling using PyCaret***
***Part IV: Time Series modelling using Prophet (Facebook)***
***Part V : Evaluating integration of approaches***

##Approach

In the series we will take different approaches to predict return from Gold prices using Machine learning. We will use supervised learning methods of regression and classification. We will then use Time Series methods. And then finally we will try to integrate them to see if their predictive powers increases due to integration.

First we will go the regression route to predict future returns of Gold over next 2 weeks and 3 weeks period. We will do this by using historical returns of different instruments which I believe impact the outlook towards Gold. The fundamental reason is, I term Gold as a 'reactionary' asset. It has little fundamentals of its own and movement in prices often is a derivative of how investors view other asset classes (equities, commodities etc.)

##Importing Data

For this and subsequent exercises we will need closing price of several instruments for past 10 years . There are various paid (Reuters, Bloomberg) and free resources (IEX, Quandl, Yahoofinance, Google finance) that we can use to import data. Since this project needed different type of asset classes (Equities, Commodities, Debt and precious metals) I found the 'yahoofinancials' package to be very helpful and straight forward.

Kindly refer to the the notebooks in the repository for complete code and results.
