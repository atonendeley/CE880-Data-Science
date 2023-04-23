## [Overview](../README.md)

## [Data Description](../Data_Description/Data_Description.md)

# Exploratory Data Analysis

## [Summary Performance of the Model](../Models/Models.md)

## [Conclusion](../Conclusion/Conclusion.md)


This step is to understand the data before building the model.
First statistical graphs and visualisation techniques are adopted to find different patterns, missing data, outliers, and the presence of any anomalies in the data. EDA helps to ask the analytical questions and visualize the answer in relation to independent variables and the target variable.

### Data Collection
Collecting data is a starting point of exploratory data analysis. Data collection is the process of finding data from different public sites, or one can buy from private organizations and load data into the system. in this case the data was provided for the study.
fig, ax = plt.subplots()
ax.axis('off')
ax.table(cellText=data.head().values,colLabels=data.columns,loc='center')


* October is the busiest month for the hotel followed by September.
* 14.7% of the bookings were made in October.
