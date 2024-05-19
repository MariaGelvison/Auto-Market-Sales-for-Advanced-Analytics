# Racing Profits – Cornering the High-End Market

## Table of Contents

  - [Project Overview](#project-overview)
  - [Data Sources](#data-sources)
  - [Problem Statement](#problem-statement)
  - [Data Analysis](#data-analysis)
    



## Project Overview
UAE Auto Market Sales Data for Advanced Analytics dataset is a comprehensive snapshot of current vehicle sales across the United Arab Emirates as of April 2024.
Consists of 9,953 entries in the dataset, this analysis aims to provide deeper understanding of UAE vehicle market dynamics -- providing valuable insights into automotive market trends and consumer preferences.


### Why UAE?
The United Arab Emirates (UAE) is renowned for its lavish lifestyle and insatiable demand for high-end, luxury automobiles. As one of the world's wealthiest nations, the UAE boasts a thriving luxury car market that caters to the preferences of its affluent population.

### Why focus on Luxury Car Market?
  - Profit Margins
      - Expensive cars produces more profit from high-end cars compared to average car type.
  - Sustained Growth
      - The UAE luxury car market is poised for continued expansion, driven by the country's growing affluent population and their insatiable appetite for premium vehicles.
  - Increased Customization
      - Demand for personalized, bespoke luxury vehicles is expected to rise as UAE buyers seek to express their unique style and preferences through their car purchases.


### Data Sources
The primary dataset used for this analysis is the "car_dataset_uae.csv" file, cleaned data.
You can also download the main dataset from kaggle [Download here](https://www.kaggle.com/datasets/azharsaleem/uae-auto-market-sales-data-for-advanced-analytics)


### Data Structure Overview

Column Headers: brand, model, car_name, car_category, price, trim, kilometers, year, vehicle_age_years, regional_specs, doors, body_type, fuel_type, seating_capacity, transmission_type, engine_capacity_cc, horsepower, no_of_cylinders, exterior_color, interior_color, warranty, address, country, city, area_name, location_name, seller_type, lat, long.


## Problem Statement

1. Mapping a Vehicle Sales Strategy to Maximize Profits
2. Consumer Guide to Car Buying -- Using UAE Data as a Proxy to Global Car Sales



### Data Cleaning

Data Cleaning was mainly done using Excel which performed the ff tasks:
1. Data loading and inspection
2. Handling missing values
3. Treating outliers
4. Data Cleaning and formatting

### Data Preparation and Data Validation

1. Carefully created a column “Categories” and manually classified each car into the following factors:
    - market positioning
    - body type
    - dimension
    - features, and
    - appointments

  Different car models are made to cater to a wide variety of consumer wants and needs.


2. Car prices adjustment
   - Erronous data prices were observed, seems like three zeros "000" were missing for some 'high-end' car prices (might be a typo error). And thus, changing them into a more realistic amount by multiplying them into "1000" could create a more realistic analysis. Google seach helped to validate the data.



## Data Analysis
A comprehensive analysis of this dataset will be performed to provide insights such as distribution of car brands, price ranges, mileage, and other relevant statistics. Will also visualize some of these aspects to better understand the data. Let's start by examining the basic statistics and distributions of key columns like price, kilometers, and year.

### Comprehensive Analysis Report

### Basic Statistics

  - Count: There are 9,953 entries in the dataset.
  - Price: The average price of the cars is approximately 256,719 with a high standard deviation, indicating a wide range of prices.
  - Year: The average year of the cars is 2018, with cars ranging from newer models to older ones.
  - Vehicle Age: The average vehicle age is approximately 5.88 years.
  - Doors: Most cars have around 3.96 doors on average.
  - Seating Capacity: The average seating capacity is about 4.6.
  - Number of Cylinders: On average, cars have about 5.75 cylinders.


## Mapping a Vehicle Sales Strategy to Maximize Profits

### Market Preferences

  - Customer preferences based on brand, category, and price ranges.
  - Identify the percentage rate between the Premium car and the average affordable car based on price.
  - Determine the percentage of the Total Premium cars.



![image](https://github.com/MariaGelvison/AutoMarketSales_UAE/assets/170020192/1eaee97a-2435-44bd-a5ea-ad735a7f7b95)
#### On total unit sales with 57.2%, customers preferred the affordable cars pricing < 135,000 aed.
#### While, with 80% of sales on Brand new cars, customers preferred to buy Premium cars pricing > 135,000 aed.


![image](https://github.com/MariaGelvison/AutoMarketSales_UAE/assets/170020192/ebea0be7-d9e4-416b-bf54-b8fd54809cbf)

#### These 5 car categories were the top favorite categories of the customer in UAE. 

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE/assets/170020192/e48843fb-8ac7-4416-83e7-ab8d7da8f0ac)
#### SUV as the most popular categories in most of the cities in UAE.

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE/assets/170020192/efaad9a9-19fc-46a1-b42b-aed7b2001b1b)
#### Map shows that among UAE cities, Dubai is the home of Luxury Cars.

![image](https://github.com/MariaGelvison/AutoMarketSales_UAE/assets/170020192/c4ab0090-7e86-4da8-816f-d15d63385c23)
#### Mercedes-Benz with 15.4% of total numbers of Car brand sales lead the Market, followed by BMW and Nissan with 9% and 7% consiquently.
















