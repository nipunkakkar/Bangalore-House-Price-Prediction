# Bangalore-House-Price-Prediction

A data science problem to predict price for houses in different areas of Bangalore given on certain features like no. of rooms, square feet area, name of area etc.

# Problem Statement

The problem here is to predict approximate prices of houses in city of bangalore. The price of houses will be predicted on different factors like number of rooms, square of feet, area in which house is built etc.

This is similar problem which are present in websites like 99acres.com, magicbricks.com etc

# Dataset

The dataset is taken from Kaggle https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data

# Conclusion

Comparing accuracies of different models

* XGBoost

Mean Accuracy 0.8334473137886329 Test Accuracy 0.8350460196516805 Mean Squared Error 576.3929532231713

* CatBoost

Mean Accuracy 0.8777337309577747 Test Accuracy 0.8797642508573706 Mean Squared Error 420.13559409102515

* Random Forest

Mean Accuracy 0.838524714336093 Test Accuracy 0.8553647557037809 Mean Squared Error 505.39390091717706

* Lasso

Mean Accuracy 0.726466276094449 Test Accuracy 0.7237578391437439 Mean Squared Error 965.2633696044655

As can be seen catboost is a clear winner in detecting the prices of houses in different areas of banglore given by factors like size, bathrooms, square feet and aread. The accuracy of our final model is 88% approx.
