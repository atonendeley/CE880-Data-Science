## [Overview](../README.md)

# Data Description

## [Exploratory Data Analysis](.../Exploratory_Data_Analysis/Exploratory_Data_Analysis.md)

## [Summary Performance of the Model](.../Models/Models.md)

## [Conclusion](.../Conclusion/Conclusion.md)

#### The data contains information about 36275 booking records.
* The characteristics include number of adults, number of children, average price per room, type of meal plan selected, number of special requests from a customer and more.
* Some columns (like average price per room, number of children) have some extreme and irregular values, which warrants an anomaly check.
* The values in the average price per room column which were greater than or equal to 500 were capped to the upper whisker value using the IQR method.
* In the no of children column, there were high values like 9 and 10, which were replaced with 3. 
* There were quite a few outliers in some other columns of the data. However, they were not treated since they are proper values.
