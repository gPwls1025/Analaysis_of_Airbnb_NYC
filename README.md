# Analysis_of_Airbnb_NYC
Intro to Data Science Final Project - Analysis of Airbnb in New York City

The dataset for this project was obtained from Kaggle New York City Airbnb Open Data (https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). The dataset is a collection of information on Airbnb listings in New York City during the year 2019. It has 48,895 observations with 16 variables and is a mix of categorical and numeric values.

The columns of the dataset that contribute to our analysis are as follows: 

1. neighbourhood_group: Categorical variable with 5 Boroughs (Manhattan, Brooklyn, Queens, Bronx, Staten Island). 
2. latitude: Indicates latitude coordinates. 
3. longitude: Indicates longitude coordinates. 
4. room_type: Categorical variable with 3 room types (Entire home/apt, Private room, Shared room). 
5. price: Numerical variable that indicates Airbnb price in dollars for a night. This variable was removed after creating logPrice variable a. logPrice: price variable transformed by log scaled. 
6. minimum_nights: Numerical variable that indicates minimum night stays. 
7. number_of_reviews: Numerical variable that indicates a number of reviews for each airbnb listing. 
8. reviews_per_month: Numerical variable that indicates number of reviews per month. 
9. calculated_host_listings_count: Numeric variable that indicates number of airbnb listings per host. 
10. availability_365: Numerical variable that indicates number of days when listing is available for booking.

Following questions were answered during analysis: 

- Is there a relationship between the number of reviews for a unit and the borough the unit is located in, or the room type?

- Can we create a model that can help us predict the price for a unit in NYC?

- Can we classify whether a unit is in Manhattan or not given other features?
 
