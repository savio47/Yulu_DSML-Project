# Yulu_DSML-Project
Yulu - Demand for Shared Electric Cycles
This project investigates factors influencing the demand for Yulu's shared electric cycles in the Indian market.

Business Problem
Yulu has experienced revenue dips and seeks to understand factors impacting the demand for their shared electric cycles. This project aims to identify key variables affecting rental numbers and utilize those insights to optimize service offerings.

Dataset
The project utilizes a dataset named yulu_data.csv containing information for each rental, including:

datetime: Date and time of the rental season: Season (1: spring, 2: summer, 3: fall, 4: winter) holiday: Whether it's a holiday (0: not a holiday, 1: holiday) workingday: Whether it's a workday (0: weekend/holiday, 1: workday) weather: Weather category (1: Clear, 2: Mist, 3: Light Rain/Snow, 4: Heavy Rain/Snow) temp: Temperature in Celsius atemp: Feeling temperature in Celsius humidity: Humidity percentage windspeed: Wind speed casual: Number of rentals by casual users registered: Number of rentals by registered users count: Total number of rentals (casual + registered)

Project Structure
The casestudy covers the following:

Performs initial data exploration, checking structure and characteristics. Handles potential missing values and outliers (optional). Establishes relationships between the dependent variable (count) and independent variables (workingday, weather, season). Conducts statistical tests (t-test, ANOVA, Chi-square) to assess the impact of different factors on rental demand. Analyzes results and provides actionable insights for Yulu.

Outcome
Key Demand Factors: Identification of variables significantly affecting the demand for shared electric cycles. Statistical Analysis: Results from hypothesis testing to understand the influence of working days, seasons, weather, and potential relationships between these factors. Actionable Insights: Recommendations for Yulu to optimize service offerings based on factors influencing demand.
