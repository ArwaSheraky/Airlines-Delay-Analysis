# Airlines-Delay-Analysis

## ABOUT THE DATASET
This 2015 dataset summarizes US airline flight delay and cancellation information as collected and published by the DOT's Bureau of Transportation Statistic. 

Drawing airport and airline information from two additional datasets helped expand the original dataset by pulling from, and merging , relevant attributes. The dataset is now characterized by 28 representative features and includes over a million instances. Features include airport origin, time of the flight (YMD), actual and scheduled departure times, arrival times, flight number, as well as cancellation and delay reason.

## Attributes (28)
```
DATE, MONTH, FLIGHT_NUMBER, TAIL_NUMBER, ORIGIN_AC, DESTINATION_AC, ORIGIN_AIRPORT, DESTINATION_AIRPORT, SCHEDULED_DEPARTURE, DEPARTURE_TIME, DEPARTURE_DELAY, SCHEDULED_TIME, ELAPSED_TIME, AIR_TIME, DISTANCE, SCHEDULED_ARRIVAL, ARRIVAL_TIME, ARRIVAL_DELAY, DIVERTED, CANCELLED, CANCELLATION_REASON, AIR_SYSTEM_DELAY, SECURITY_DELAY, AIRLINE_DELAY, LATE_AIRCRAFT_DELAY, WEATHER_DELAY, AIRLINE_CODE, AIRLINE_NAME.
```
## Data Cleaning
To make the data more reliable, a cleaning phase was processed. This phase included: removing outliers, fill the missing values, rename the columns, remove the duplicated and unused columns, change types and finally merge the datasets.

## Data Visualization
To explore and understand the data, different charts were generated as well as some analysis, based on individual attributes or the correlation between multiple ones. We'll discuss and share some of them below.

* Individual Variables:
    * Arrival Delays
    * Departure Delays
    * Cancellation Reasons

* Multiple Variables:
    * Months X Delays
    * Airlines X Delays
    * Airports X Delays

## Business Questions
* 
* 
* 
* 

## REFERENCES
* [Dataset Source](https://www.kaggle.com/usdot/flight-delays#airlines.csv).
* [Bureau of Transportation](https://www.bts.gov/topics/airlines-and-airports-0).
