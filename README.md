# 🏨 Hotel Booking Data Analysis Project
In this project, the dataset of 'hotel_booking.csv' is being cleaned and analysed. This dataset contains booking information for city hotel and resort hotel. It includes information such as when the booking was done, length of stay, number of members, phone number, booking canceled or not and other related information. 

Exploratory data analysis with the help of python will be performed to get insight from this data.

![AestheticMyViewGIF (2)](https://github.com/CodePrin/HotelBooking_DataAnalysis_Project/assets/89415614/6f43a7d0-2da1-449f-b363-c40074a1ac48)


## Table Of Content
* Problem Statement
* Questions To Be Answered
* Tools
* Files
* Dataset Features
* Results
* Suggestions
* Dataset Information
* Acknowledgements


## Problem Statement
In recent years, City Hotel and Resort Hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a result, including fewer revenues and less hotel rooms are in use than the ideal ones. Consequently, lowering cancellation rates is the primary goal of both the hotels in order to increase their efficiency in generating revenue, and for us to offer thorough business advice to address this problem.
The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue generation are the main topics of this report.


## Questions To Be Answered
1. What are the variables that affect hotel reservation cancellations?
2. How can we make hotel reservations cancellations better?
3. How will hotels be assisted in making pricing and promotional decisions?


## Tools 
Used Python 3.11.1 for this project and below given packages:
* Pandas
* Matplotlib
* Seaborn


## Files
This repository contains four files other than README.md file, which are as follows:

* **HotelBooking.ipynb:** It is a Jupyter Notebook file containing all the python code, documentation and visualization.  
* **hotel_booking.csv:** Dataset file in csv format.
* **HotelBooking_Dataset.zip:** Zip file to extract the main dataset file.
* **package_requirements:** It is a text file containing all the packages installed during the project.


## Dataset Features
**This dataset consist of following features:**
1. hotel
2. is_canceled
3. lead_time
4. arrival_date_year
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_week_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellations
19. previous_bookings_not_canceled
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent
25. company
26. days_in_waiting_list
27. customer_type
28. adr
29. required_car_parking_spaces
30. total_of_special_requests
31. reservation_status
32. reservation_status_date


## Results
1. 37% of clients who canceled their reservation, gave a significant impact on the hotel's earnings.
2. In comparison to resort hotels, city hotels have more bookings.
3. It is possible that resort hotels are more expensive than those in cities.
4. Weekends and holidays may see a rise in resort hotel rates.
5. January is the month with the most canceled reservations.
6. The cost of the accommodation is solely responsible for the cancellation.
7. Portugal has the highest number of cancellations.
8. Around 46% of the clients come from online travel agencies, whereas 27% come from groups. Only 4% of client book hotels directly by visiting them and making reservations.


## Suggestions
1. Cancellation rates rise as the price does. In order to prevent cancellations of reservations, hotels could work on their pricing strategies and try to lower the rates for specific hotels based on locations. They can also provide some discounts to the consumers.
2. As the ratio of the cancellation and non-cancellation of the resort hotel is higher than the city hotels. So the hotels should provide a reasonble discount on the room prices on weekends or on holidays.
3. In the month of January, hotels can start campaigns or marketing with a reasonable amount to increase their revenue as the cancellation is the highest in this month.
4. They can also increase the quality of their hotels and their services mainly in Portugal to reduce the cancellation rate.


## Dataset Information  
This "Hotel Booking" dataset was posted on Kaggle by Mojtaba.
Download link for this dataset is given below:
https://www.kaggle.com/datasets/mojtaba142/hotel-booking


## Acknowledgements
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

