# Uber Fare Prediction

![uber](https://user-images.githubusercontent.com/103409242/174770398-2a5bc539-ed14-4a23-af0c-e7b25198ae44.jpeg)

<b>Author: Aswathi Sasikumar</b>

The project is about the world's largest taxi company Uber inc. Uber delivers service to lakhs of customers daily. 
In this project I have created a multiple regression model which can predict fare for future transactions.

The datset contains the following fields:
* key - a unique identifier for each trip
* fare_amount - the cost of each trip in usd
* pickup_datetime - date and time when the meter was engaged
* passenger_count - the number of passengers in the vehicle (driver entered value)
* pickup_longitude - the longitude where the meter was engaged
* pickup_latitude - the latitude where the meter was engaged
* dropoff_longitude - the longitude where the meter was disengaged
* dropoff_latitude - the latitude where the meter was disengaged

<b>Business Problem</b>
Real-estate agency needs to provide advice to homeowners on what factors can increase the estimated value of their homes.The regression model developed in the project predicts the price of the house and identifies the parameters that can affect the price of the house.

<b>Data</b>
This project uses the Uber data set from kaggle.It has 200000 data records

<b>Methods</b>
Exploratory data analysis was used to analyse the data and to draw conclusions about the fare amount.Invalid data was found in the dataset like fare_Amount<=0,distance >130kms which was practically impossible.
The dataset had lot of outliers and most of the variables were not normally distributed which was challenge in the project.The data set had only latitudes and longitudes 
from which distance was calculated.After cleaning the data ,Multiple regression using OLS statsmodels was used to develop a model with fare_amount as dependent variable.

</b>Assumptions of Linear Regression:</b>
Linearity
Normality (Residuals)
Homoscedasticity

<b>Results</b>
It was found that fare_Amount increases with distance which is obvious.It was found that fare_Amount tends to increase during non-peak hours.

<b>Future work</b>
Modeling the data with other types of regression analysis techniques like logistic regression might give more accurate model.

<b>For More Information</b>
Please review our full analysis in our Jupyter Notebook or our presentation.
For any additional questions, please contact ** Aswathi Sasikumar at kukkuaswathi@gmail.com


## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── Uber_fare_prediction.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── Uber_fare_prediction_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
