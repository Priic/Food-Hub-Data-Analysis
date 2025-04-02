# Food-Hub-Data-Analysis

![foodHub](https://github.com/user-attachments/assets/b2685ad9-28bc-4701-b7a4-4985f627aafb)
Image by Freepik

### Context

The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. <br>

The **`Food hub`** is a **`food aggregator company`** which provides **`online food delivery services`** through their smartphone app. The app has **`access to multiple restaurants`** and help their millions of customers to place order from their favorite restaurant and have them at their doorsteps in no time.
The dataset we have analyzed here, provides information about the different orders made by registered customers through their online portal from multiple restaurants.
The data contains information about approx. **`2k different orders from 178 restaurants`** providing varieties of flavorful good foods from **`14 different cuisines`**. The data also contains details about food preparation time and the time taken to deliver food to its customer on weekday & weekend.

### Objective
The **`food hub`** has stored the data of the different orders made by the registered customers in their **`online portal`**. The main idea here is to understand the demand of different restaurants based on customers preferences as in what they order, when they order, and from where they order most often. This will also help them in enhancing their customer experience and boost company's revenue.

### Analysis Approach
As a Data Scientist, I explored the dataset to understand its **`shape, size, data types, missing values, duplicates, and statistical summary`**. Conducted **`Exploratory Data Analysis (EDA)`** to identify patterns and extract actionable insights, focusing on restaurant demand based on customer preferences.

I've used below Python libraries-
  1. Data manipulation  - **`numpy & pandas`**
  2. Data visualization - **`matplotlib and seaborn`**

The data contains the different data related to a food order. The detailed data dictionary is given below.

### Data Dictionary

* `order_id:` Unique ID of the order
* `customer_id:` ID of the customer who ordered the food
* `restaurant_name:` Name of the restaurant
* `cuisine_type:` Cuisine ordered by the customer
* `cost_of_the_order:` Cost of the order
* `day_of_the_week:` Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
* `rating:` Rating given by the customer out of 5
* `food_preparation_time:` Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
* `delivery_time:` Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
