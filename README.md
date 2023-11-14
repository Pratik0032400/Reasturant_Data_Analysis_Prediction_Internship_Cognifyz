# Reasturant_Data_Analysis_Prediction_Internship_MeriSkill
## **Level_1**

Task 1 - **Data Overview:**

* The dataset includes restaurant details across various cities with 9,551 rows and 21 columns.
* Minimal null values (9) were found only in the 'Cuisines' column.
* No duplicates exist, and data type conversion wasn't needed.
* The 'Aggregate rating' distribution is well-balanced.

Task 2 -**Descriptive Insights:**

* Key statistical measures for numerical columns were identified.
* Country codes 1 and 216 have the most restaurants.
* New Delhi, Gurgaon, and Noida are top cities with the highest restaurant counts.
* North Indian and Chinese cuisines are most popular.

Task 3 - **Geospatial Analysis:**

* North America and Asia (mainly India) have the most number of restaurants.
* New Delhi leads in the number of restaurants, followed by Gurgaon, Noida, and Faridabad.
* Latitude and rating show no correlation, while longitude and rating are negatively correlated.

## **Level_2**

Task_1 - **Table Booking and Online Delivery:**

* Approximately 12.12% of restaurants offer table booking, while 25.66% provide online delivery services.
* Restaurants with table booking have a significantly higher average rating of 3.44, compared to 2.56 for those without this service.
* Online delivery is more prevalent in restaurants with medium-priced food products.

Task_2 - **Price Range Analysis:**

* The most common price range among restaurants is 1.
* Restaurants in price range 4 achieve the highest average rating at 3.818, followed by price ranges 3, 2, and 1.

Task_3 - **Feature Engineering:**

* Introduced two new columns, 'Restaurant Name Length' and 'Address Length,' based on the length of restaurant names and addresses.
* Additionally, i created two binary columns, 'Has Table Booking' and 'Has Online Delivery,' by encoding categorical variables.

## **Level_3**

Task_1 - **Predictive Modeling Insights:**

* Leveraging three regression models, Linear Regression, Decision Tree, and Random Forest, we successfully predicted restaurant aggregate ratings.
* Random Forest outperformed other models, showcasing the lowest Mean Squared Error (MSE) of approximately 0.1337 and the highest R-squared value of about 0.9413.

Task_2 - **Customer Preference Analysis Findings:**

* Certain cuisines like cafe, mughlai, north Indian, and fast food significantly impact restaurant ratings, with varying performance.
* North Indian and Chinese cuisines exhibit greater rating variability, while cafe and fast food cuisines maintain more consistent ratings.
* By the number of votes, North Indian, Mughlai, and Chinese cuisines emerged as the most popular.
* Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian cuisines received the highest average ratings.

Task_3 - **Data Visualization Highlights:**

* The restaurant ratings distribution is negatively skewed.
* Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian cuisines topped the charts based on the highest average ratings.
* Cities like Inner City, Quezon City, and Makati City were identified as the most popular based on the highest average rating.
* We observed a positive correlation between votes and restaurant ratings.

  
