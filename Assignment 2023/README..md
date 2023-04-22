# Hotel Booking Cancellations 
This project is based on Predicting the cancellation of hotel booking?
# Overview of the Business Problem

## Introduction 
The rate of cancellation for bookings in the hospitality industry is quite alarming as it is high in the competitive market offering no deposit for bookings. Once the booking has been cancelled, there is almost nothing the hotel can do.
This kind of setting creates issues and monetary losses for many hotels and creates a demand to take prior precautions for high number of cancellations. 
Therefore, predicting bookings that can be cancelled and preventing these cancellations will create value for the hospitality industry. This project aims to ascertain how future cancelled hotel bookings can be predicted in advance with the help of machine learning methods. Includimg the measures and steps that can be implemented to reduce their impact on the industry’s revenue.

## Poject Objectives 
The aim of the project is to predict whether a booking made in a hotel can be cancelled in future or not. Machine models have been developed for this to help identify and flag bookings with probability of high cancellation rates by analysing the trends and features associated with it.
In order to prevent the resulting income losses, hotels can take action on these bookings. With the aid of this form of prediction, hotels can adopt better net demand projections, better overbooking/cancellation policies, and more forceful pricing and inventory allocation tactics.
Additionally hotels can use this technique to determine which of their regular clients never cancel their reservations and are eligible for loyalty rewards.

## Data  
The dataset used in this report contains 36,275 hotel booking details with 18 corresponding features, including cancellation and non-cancellation status of the booking.
Some key variables were selected as the predictor to test and train the prediction model, by applying some machine learning algorithms. 
After preprocessing the raw data which involves standardising, scaling, checking for missing data and recording some variables was conducted before the prediction. 

## Data Description
The data contains different attributes of reservation details of customers'. 
Below is a detailed data dictionary.

## Data Dictionary
•	Booking_ID: unique identifier of each booking
•	no_of_adults: Number of adults
•	no_of_children: Number of Children
•	no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
•	no_of_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
•	type_of_meal_plan: Type of meal plan booked by the customer:
•	required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
•	room_type_reserved: Type of room reserved by the customer. The values are ciphered (encoded) by the Hotel.
•	lead_time: Number of days between the date of booking and the arrival date
•	arrival_year: Year of arrival date
•	arrival_month: Month of arrival date
•	arrival_date: Date of the month
•	market_segment_type: Market segment designation.
•	repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
•	no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
•	no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking

## References
Zeytinci, E. (2019, December 30). Predicting Hotel Cancellations with Machine Learning online
Antonio, N., Almeida, A. D., & Nunes, L. (2019). Hotel booking demand datasets. Data in Brief, 22, 41–49. doi: 10.1016/j.dib.2018.11.126
Mostipak, J. (2020, February 13). Hotel booking demand online
Marcuswingen. (2020, March 6). EDA of bookings and ML to predict cancelations Online

## Libraries Used
Python

Python Standard Library: Built in python modules.
Numpy: Scientific computing with python.
Pandas: Data analysis tools.
matplotlib: Static, animated, and interactive visualizations.
Seaborn: Python data visualization library.

