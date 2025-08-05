# Flight Delay Prediction Project
Objective
We are a travel app development company looking to introduce a new feature that helps users identify on-time flights and avoid those that are frequently delayed. This project aims to analyze flight data and build a predictive model to classify flights as likely to be on time or delayed.

# Dataset Description
The dataset includes flight information from 2017 to 2018, focusing on arrival and departure times for non-cancelled and non-diverted flights.

# Columns Overview

Column Name	Description

Year	Year of the flight
Quarter	Quarter of the year
Month	Month of the flight
DayofMonth	Day of the month
DayOfWeek	Day of the week
FL_DATE	Date of the flight
UNIQUE_CARRIER	Unique marketing carrier code
ORIGIN	Origin airport code
ORIGIN_CITY_NAME	Origin airport city name
ORIGIN_STATE_ABR	Origin state abbreviation
DEST	Destination airport code
DEST_CITY_NAME	Destination city name
DEST_STATE_ABR	Destination state abbreviation
DEP_TIME	Actual departure time (local time in hhmm)
ARR_TIME	Actual arrival time (local time in hhmm)
ARR_DELAY	Arrival delay in minutes (negative = early arrival)
AIR_TIME	Total air time in minutes
DISTANCE	Distance between origin and destination in miles
DISTANCE_GROUP	Distance intervals (every 250 miles)

# Task Overview
✅ Task 1: Exploratory Data Analysis (EDA)

Perform in-depth analysis using Python.

Understand delay patterns, distribution of delays, and other important insights.

Provide visualizations and commentary.

✅ Task 2: Flight Delay Prediction

Build and evaluate at least two models to predict if a flight will be delayed.

Define your own labeling strategy. For example:

On-Time if arrival delay ≤ 15 minutes

Delayed if arrival delay > 15 minutes

# Suggested Modeling Techniques
- Logistic Regression

- Random Forest

- XGBoost
