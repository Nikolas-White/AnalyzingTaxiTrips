# Analyzing NYC Taxi Trip Data

## Project Overview

This project aims to analyze and optimize NYC taxi operations using exploratory data analysis (EDA). By understanding trip durations, passenger counts, and temporal patterns, we can derive insights and make data-driven recommendations to improve taxi services. This project involves data cleaning, exploratory data analysis, and visualization.

## Dataset

The dataset used in this project is the NYC Taxi Trip Duration dataset from Kaggle. It includes various features about taxi trips, such as pickup and dropoff times, trip duration, passenger count, and geographic coordinates. You can download the dataset here: [NYC Taxi Trip Duration Dataset](https://www.kaggle.com/datasets/yasserh/nyc-taxi-trip-duration).

## Key Takeaways

- **Peak Hours for Taxi Trips**: The highest volume of trips occurs in the late afternoon and early evening (5 PM to 7 PM). Conversely, the lowest volume occurs in the early morning hours (4 AM to 5 AM).
- **Average Trip Duration by Time of Day**: Trip durations are shorter during early morning hours and tend to increase during the day, peaking in the evening. This pattern suggests potential congestion during peak hours.
- **Trip Duration Characteristics**: The majority of NYC taxi trips are short, with a right-skewed distribution of trip durations.
- **Passenger Count Distribution**: Most trips are taken by single passengers, with the frequency decreasing as the passenger count increases. Trips with more passengers tend to have slightly longer durations, especially for two or three passengers.

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Usage

1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter notebooks or Python scripts in the `notebooks/` or `src/` directories to see the data analysis and model building process.
4. View the results and visualizations saved in the `results/` directory.

## Acknowledgements

This project uses the NYC Taxi Trip Duration dataset from Kaggle.
