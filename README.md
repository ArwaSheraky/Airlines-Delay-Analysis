# Airlines-Delay-Analysis
Final project of CEBD 1260 - Big Data Analysis
By: Arwa Sheraky & Tiffany Eversley

## About the Dataset
This 2015 dataset summarizes US airline flight delay and cancellation information as collected and published by the DOT's Bureau of Transportation Statistic.

Drawing airport and airline information from two additional datasets helped expand the original source file by pulling from, and merging , relevant attributes. The dataset is now characterized by 28 representative features and includes over a million instances. Features include airport origin, time of the flight (YMD), actual and scheduled departure times, arrival times, flight number, as well as cancellation and delay reason.
____________
## Project Structre

- Code (Jupyter notebooks of the following):
    1. Data Cleaning and Exploration.
    2. Supervised Learning (Classification - Regression).
    3. Unsupervised Learning (Clustering).

- Docs:
    1. Data Blogpost.
    2. Data Story.

- Data (not uploaded due to large size):
    - [Flights, Airlines and Airports](https://www.kaggle.com/usdot/flight-delays).
    - [US 2015 Weather](https://data.world/mattwinter225/2015-usa-weather-avg-max-min).
    - [Cleaned Merged Data](https://www.kaggle.com/arwasheraky/final_merged_flights_2015)(Ready for prediction).

- Presentation:
    - `CEBD final presentation.pdf`.
___________
## Problem Definition:
Predict the average expected delay for a flight, according to specified features.

## Regression Model:
[Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/ensemble.html#gradient-boosting)(100).

## Evaluation:
The model predicted average delays, with `RMSE = 20.3`.
_________
## Prediction APP
A simple UI application was implemented to predict average delay for a flight, according to some required inputs from user. The application can be downloaded from the repository [here](https://github.com/ArwaSheraky/Flight-Delay-Prediction).
