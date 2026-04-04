# NYC Airbnb Exploratory Data Analysis (EDA) Project

This repository contains an Exploratory Data Analysis (EDA) of the 2019 New York City Airbnb dataset. The goal of this project is to clean the data and uncover insights regarding pricing, location density, and rental trends.

# Dataset Description

# Dataset source
The dataset used in this project is the New York City Airbnb Open Data for 2019 from Kaggle.com ( https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data ). It is a public dataset originally sourced from Inside Airbnb, an independent project that provides data about how the platform is being used in cities globally.

# Number of Rows and Columns
* **Rows:** 48,895
* **Columns:** 16

# Description of features (columns)
| Column Name | Description |
| :--- | :--- |
| `id` | Unique ID for the listing |
| `name` | Name of the listing |
| `host_id` | Unique ID for the host |
| `neighbourhood_group` | The five boroughs of NYC |
| `room_type` | Type of listing (Private, Entire Home, Shared) |
| `price` | Price per night |
| `number_of_reviews` | Total reviews received |
| `availability_365` | Days available per year |

# Purpose of using this dataset
The purpose of this analysis is to:
* Identify the most popular and expensive areas in NYC.
* Perform data cleaning (handling missing values in `reviews_per_month` and removing `$0` price outliers).
* Visualize trends, such as the geographic distribution of listings and monthly seasonality.

