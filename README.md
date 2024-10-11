# Maximizing Revenue for Taxi Drivers through Payment Type Analysis

## Project Overview

This project involves analyzing taxi trip data to gain insights into fare amounts, payment methods, and passenger counts. The primary goal is to understand the factors influencing fare amounts and the distribution of payment types among different passenger counts. This analysis will help taxi service providers optimize their services and pricing strategies.

## Dataset 
Get the dataset here: https://catalog.data.gov/dataset/2020-yellow-taxi-trip-data-january-june

The dataset used for this analysis is sourced from a CSV file named `taxi_trip.csv`, which contains the following key columns:

- `tpep_pickup_datetime`: Pickup date and time
- `tpep_dropoff_datetime`: Dropoff date and time
- `passenger_count`: Number of passengers in the trip
- `payment_type`: Payment method (1 for Card, 2 for Cash)
- `fare_amount`: Amount charged for the trip
- `trip_distance`: Distance of the trip

## Key Findings

- The average fare amount for card payments is higher than for cash payments.
- The distribution of payment types varies based on passenger counts, with specific trends identified.
- Statistical tests (t-tests) indicate significant differences in fare amounts based on payment methods.

## Analysis Steps

1. **Data Cleaning**: Remove invalid rows and duplicates, convert datetime fields, and calculate trip durations.
2. **Exploratory Data Analysis (EDA)**: Visualize fare amounts, trip distances, and payment type distributions using box plots and histograms.
3. **Statistical Analysis**: Perform hypothesis testing to determine if there are significant differences between fare amounts based on payment types.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Hypothesis Testing (t-test)
