# Project Name
> Build a Linear Regression Model to predict the demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.

We need build the model for the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Train Dataset R2 : 0.839
- Test Dataset R2 : 0.806
- Train Dataset Adjusted R2 : 0.836
- Test Dataset Adjusted R2 : 0.7957

Below is the analysis obtained after reviewing:

-	Fall season has the greatest number of bookings and the booking count has significantly increased from 2018 to 2019.
-	As evident from the remaining columns, 2019 attracted a greater number of bookings as compared to the previous year. This shows a good overall progress in business
-	The highest number of bookings are made during may, june, july, aug, sep and oct, post that we can observe a dip which help us interpret that a smaller number of bookings are made at the year-end (being a festive season). Further to this the number of booking also increased for each month in 2019 as compared to 2018
-	People don't prefer booking bikes on a holiday.
-	Thursday, Friday, Saturday and Sunday record highest number of booking as compared to the start of week, in both the years. With higher booking counts recorded in 2019.
-	The bookings don't seem to be impacted by the working days as the number are fairly close. 
-	Clear weather attracts the greatest number of bookings. Booking numbers also increased in 2019.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - Version 3.11.x
- numpy
- Pandas
- matplotlib
- seaborn
- sklearn
- statsmodels
- jupyter notebook
- Anaconda

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was created as part of the Linear Regression Assignment : Modeling the Bike Sharing Demand, for IIIT Bangalore and UpGrad.


## Contact
Created by [@AnshulAwasthi21] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->