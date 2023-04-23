## [Overview](../README.md)

## [Data Description](../Data_Description/Data_Description.md)

# Exploratory Data Analysis

## [Summary Performance of the Model](../Models/Models.md)

## [Conclusion](../Conclusion/Conclusion.md)


This step is to understand the data before building the model.
First statistical graphs and visualisation techniques are adopted to find different patterns, missing data, outliers, and the presence of any anomalies in the data. EDA helps to ask the analytical questions and visualize the answer in relation to independent variables and the target variable.

### Data Collection
Collecting data is a starting point of exploratory data analysis. Data collection is the process of finding data from different public sites, or one can buy from private organizations and load data into the system. in this case the data was provided for the study.

#### After evaluating it shows the following
#### Import Libraries
After collecting data we have to import the necessary libraries to build machine learning models. Numpy, Pandas, Matploilib, Seaborn are the known libraries used in the machine learning model.

#### Numpy: NumPy is a Numerical Python Library that helps perform mathematical operations.
#### Pandas: Panda is an open-source library that helps understand relational or labelled data.
### Matplotlib: Matplotlip is a Python visualization library that helps visualize 2D array plots.
### Seaborn: Seaborn is a data visualization library built on top of matplotlib.

#Import Libraries to read and manipulate data
import pandas as pd
import numpy as np

#### Libaries for data visualization
import matplotlib.pyplot as plt
import seaborn as sns

#### Removes the limit for the number of displayed columns
pd.set_option("display.max_columns", None)
#### Sets the limit for the number of displayed rows
pd.set_option("display.max_rows", 200)
#### setting the precision of floating numbers to 5 decimal points
pd.set_option("display.float_format", lambda x: "%.5f" % x)

#### Library to split data
from sklearn.model_selection import train_test_split

#### To build model for prediction
import statsmodels.stats.api as sms
from statsmodels.stats.outliers_influence import variance_inflation_factor
import statsmodels.api as sm
from statsmodels.tools.tools import add_constant
from sklearn.tree import DecisionTreeClassifier
from sklearn import tree

#### To tune different models
from sklearn.model_selection import GridSearchCV

#### Apply different metric Scores
from sklearn.metrics import roc_curve
from sklearn.metrics import auc
from sklearn.metrics import precision_recall_curve
from sklearn.metrics import fbeta_score, make_scorer

The data shown below represents the Hotel booking cancellation dataset provided for the study.
hotel = pd.read_excel("/content/HotelCancelation.xls")
#### copying data to avoid changes to original data
data = hotel.copy()
data.head()


* October is the busiest month for the hotel followed by September.
* 14.7% of the bookings were made in October.
