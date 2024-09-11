# Customer_Prediction_British_Airways

## Business needs
British Airways aims to identify the factors that influence customers to complete their booking process.

## Steps Taken to Address the Business Needs
1) Conducted **exploratory data analysis (EDA)** to uncover general patterns and detect anomalies in the data.
2) Developed a **predictive model** to analyse and understand the factors driving customer booking behaviour.

## The findings
With over 40,000 booking process started, only 7,474 booking processes were completed. Why did this happen?
To find out, I made a machine learning model to take the feature importance, the results are:
https://res.cloudinary.com/dbkz3bebu/image/upload/v1726049059/buwswmj0cz7ogsrs4kmd.png 

The 3 main features that affect whether the booking will be completed are:

- **purchase_lead** (the number of days between travel date and booking date)
- **flight_hour** (hour of flight departure)
- **length_of_stay** (number of days spent at destination)

## Insights
- Bookings tend to happen more frequently closer to the travel date
- Travellers tend to prefer to book flights between 5 am and 3 pm.
- Travellers are more likely to book more for shorter trips.
  
## Suggestions
- Provide cheaper rates if travellers book 30 days in advance. Customers can also add a flexibility package for a small fee, allowing them to change the date and time if needed.
- Offer cheaper rates for people who travel in the late afternoon and evenings.
- Work in partnership with hotels to offer packages and deals for longer vacations.
