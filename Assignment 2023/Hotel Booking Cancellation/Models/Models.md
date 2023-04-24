
## [Overview](../README.md)

## [Data Description](../Data_Description/Data_Description.md)

## [Exploratory Data Analysis](../Exploratory_Data_Analysis/Exploratory_Data_Analysis.md)

# Summary Performance of the Model

## [Conclusion](../Conclusion/Conclusion.md)


#### Summary Performance of the Model
Before discussing the summary a quick overview of the models used will be explained briefly

* Split the data into training and test sets.
* Fit the models and evaluate performance

### Models 

Fit the models and evaluate performance

### Logistic Regression
Logistic regression comes under the most popular Supervised Machine Learning algorithms. Logistic regression predicts the categorical dependent variable using a given set of independent variables. The categorical dependent variable should be either Yes or No, 0 or 1, true or false, etc. Logistic regression is much comparable to Linear Regression only implementation is different. Linear Regression solves the Regression problems, and Logistic regression is used for solving the classification problems. Instead of fitting the regression line, In logistic regression, we fit the sigmoid S function, which predicts two maximum values(0,1). The curve from the logistic function indicates the likelihood of something such as whether rain comes or not based on weather conditions.

### Logistic Function (Sigmoid Function)
To map the predicted values to probabilities sigmoid function is used. It maps the values between the range of 0 and 1. The threshold value is used in the logistic regression to compute the S Shape. The threshold value defines the probability of either 0 or 1. The value above the threshold tends to be 1, and the values below the threshold tend to 0.

### Assumptions for Logistic Regression
The data must follow a normal distribution.
The dependent variable must be categorical.
The independent variable should not have multi-collinearity

### Decision Tree Classification Algorithm
The Decision Tree algorithm belongs to the family of non-parametric, supervised learning algorithms. It allows for solving regression and classification problems

#### Summary 

* Analysis to predict whether a booking will be cancelled or not from the information provided.

* F1 Score will be used as the performance metric for the model on the following basis:

* If we predict that a booking will not be cancelled and the booking gets cancelled, then the hotel will lose resources and will have to bear additional costs from the distribution channels. 

* If we predict that a booking will get cancelled and the booking does not the hotel might not be able to provide satisfactory services to the customer on the assumption that the booking will be cancelled. This might be detrimental to the brand’s equity, based on recognition of the brand, customer loyalty, and customer satisfaction.

* F1 score will minimise both false positives and false negatives.

* Indication from the Logistic Regression and Decision Tree models shows the most significant predictors of booking status are:

* Lead Time

* Number of special requests

* Average price per room
