## [Overview](../README.md)

# Data Description

## [Exploratory Data Analysis](../Exploratory_Data_Analysis/Exploratory_Data_Analysis.md)

## [Summary Performance of the Model](../Models/Models.md)

## [Conclusion](../Conclusion/Conclusion.md)

#### The data contains information about 36275 booking records.
* The characteristics include number of adults, number of children, average price per room, type of meal plan selected, number of special requests from a customer and more.
* Some columns (like average price per room, number of children) have some extreme and irregular values, which warrants an anomaly check.
* The values in the average price per room column which were greater than or equal to 500 were capped to the upper whisker value using the IQR method.
* In the no of children column, there were high values like 9 and 10, which were replaced with 3. 
* There were quite a few outliers in some other columns of the data. However, they were not treated since they are proper values.

#### Data Dictionary
##### Booking_ID: unique identifier of each booking
* no_of_adults: Number of adults.
* no_of_children: Number of Children
* no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
* no_of_week_nights: Number of weeknights (Monday to Friday) the guest stayed or booked to stay at the hotel
* type_of_meal_plan: Type of meal plan booked by the customer:
* required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
* room_type_reserved: Type of room reserved by the customer. The values are ciphered (encoded) by the Hotel.
* lead_time: Number of days between the date of booking and the arrival date
* arrival_year: Year of arrival date
* arrival_month: Month of arrival date
* arrival_date: Date of the month
* market_segment_type: Market segment designation.
* repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
* no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking.
* no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking.
* avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)
* no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)
* booking_status: Flag indicating if the booking was canceled or not.

