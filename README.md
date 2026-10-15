# Flight Delay Analysis Using Python

## Project Overview
This project analyzes flight delays, cancellations, airline performance, route-level arrival delays, and the relationship between flight distance and airtime using Python.

## Objectives
- Analyze departure and arrival delay patterns.
- Compare average delays across airlines.
- Identify weekdays with higher average delays.
- Examine flight cancellation rates.
- Identify routes with high average arrival delays.
- Investigate relationships between departure delays, arrival delays, distance, and airtime.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings
- AirAsia India recorded the highest average departure and arrival delays in the analyzed dataset.
- Wednesday had the highest average arrival delay among the weekdays analyzed.
- Delhi–Hyderabad had the highest average arrival delay among routes with at least five recorded flights.
- Departure delay and arrival delay showed a strong positive correlation of approximately 0.951.
- Flight distance and airtime showed an almost perfect positive correlation of approximately 0.999969.
- The overall flight cancellation rate was approximately 2.63%.

## Project Workflow
1. Data loading and exploration
2. Data cleaning and missing-value assessment
3. Exploratory data analysis
4. Statistical summaries and correlation analysis
5. Data visualization
6. Business insights and conclusions

## Limitations
The analysis identifies patterns in the available dataset. It does not establish the causes of flight delays, and route-level findings are based on a limited number of observations.

## How to Run
1. Download or clone this repository.
2. Install the required libraries: `pandas`, `numpy`, `matplotlib`, and `seaborn`.
3. Open `Flight_Delay_Analysis.ipynb` in Jupyter Notebook.
4. Ensure the dataset is available at the file path specified in the notebook.
5. Run the cells in order.
