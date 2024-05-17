# Racing Profits – Cornering the High-End Market

UAE Auto Market Sales Data for Advanced Analytics dataset is a comprehensive snapshot of current vehicle sales across the United Arab Emirates as of April 2024, consisting of 9,953 entries in the dataset.



## Project Overview
This data analysis project aims to provide deeper understanding of UAE vehicle market dynamics. By analyzing 

## Data Sources
The primary dataset used for this analysis is the "car_dataset_uae.csv" file.

## Data Structure Overview

Column Headers: brand, model, car_name, car_category, price, trim, kilometers, year, vehicle_age_years, regional_specs, doors, body_type, fuel_type, seating_capacity, transmission_type, engine_capacity_cc, horsepower, no_of_cylinders, exterior_color, interior_color, warranty, address, country, city, area_name, location_name, seller_type, lat, long.

Next, A comprehensive analysis of this dataset will be performed to provide insights such as distribution of car brands, price ranges, mileage, and other relevant statistics. Will also visualize some of these aspects to better understand the data. Let's start by examining the basic statistics and distributions of key columns like price, kilometers, and year.



## Data Cleaning and Preparation
1. Created column “Categories” to classify each car, the classification was based on the following factors:
  - market positioning
  - body type
  - dimension
  - features, and
  - appointments

2. Car prices ajustment
   - erronous prices was observed, seems like three zeros "000" were missing for some 'high-end' cars. And thus, changing them into a more realistic amount by multiplying them into 1000. 




