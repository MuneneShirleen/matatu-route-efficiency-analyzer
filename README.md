
# Matatu Route Efficiency Analyzer

## About the Project

I built this project to explore how data analysis can help us understand the performance of public transport routes.

Using Python, I created a simulated dataset of 300 matatu trips across six routes in Nairobi. I then analyzed the data to find out which routes generated the most revenue, where passenger demand was highest, when trips were busiest, and which routes experienced the longest delays.

The aim was to turn raw trip records into useful information that could help with operational decisions.

## What I Wanted to Find Out

I focused on a few practical questions:

- Which route generated the highest total revenue?
- Which route carried the most passengers?
- At what time of day was passenger demand highest?
- Which route experienced the longest average delays?
- How effectively were vehicles using their available capacity?
- Which route generated the most revenue per scheduled operating hour?

## About the Dataset

The dataset contains 300 simulated trips covering six Nairobi routes:

- CBD-Rongai
- CBD-Thika
- CBD-Ruiru
- CBD-Ngong
- CBD-Kikuyu
- CBD-Githurai

Each record includes details such as the route, departure hour, number of passengers, vehicle capacity, fare, distance, scheduled travel time, actual travel time, delay, and revenue.

**A note about the data:** These records were generated for this project. They are simulated examples, not actual matatu operator records or verified transport statistics.

## Tools I Used

- Python – for the analysis
- Pandas – for working with and analyzing the dataset
- NumPy – for generating simulated data
- Matplotlib and Seaborn – for creating charts
- Google Colab – as my working environment

## How I Approached the Analysis

I worked through the project in stages:

1. Generated a dataset containing 300 simulated matatu trips.
2. Inspected the data to understand its structure and identify potential quality issues.
3. Checked for missing values, duplicate records, invalid travel durations, and other inconsistencies.
4. Used Pandas to group the records by route and departure hour.
5. Calculated revenue, passenger demand, average delays, capacity utilization, and revenue per operating hour.
6. Created charts to make the results easier to compare and understand.
7. Exported the analysis into CSV reports for further use.

## What I Found

A few results stood out from the analysis:

- **CBD-Thika generated the highest total revenue**, bringing in KSh 73,131.
- **CBD-Thika also recorded the highest passenger demand**, with 570 passengers.
- **CBD-Kikuyu had the highest revenue per scheduled operating hour**, at KSh 1,250.51.
- **CBD-Ruiru had the highest average delay**, at 25.66 minutes.
- **CBD-Ngong recorded the highest capacity utilization**, at 73.38%.

One interesting finding was that the route with the highest total revenue was not necessarily the most productive in terms of revenue per scheduled operating hour.

This helped me understand why it is important to look at different performance measures rather than relying on total revenue alone.

## Project Structure

```text
matatu-route-efficiency-analyzer/
|
|-- data/
|   |-- matatu_trips.csv
|
|-- images/
|   |-- revenue_by_route.png
|   |-- passenger_demand_by_route.png
|   |-- hourly_passenger_demand.png
|   |-- average_delay_by_route.png
|
|-- reports/
|   |-- revenue_analysis.csv
|   |-- passenger_demand_analysis.csv
|   |-- hourly_demand_analysis.csv
|   |-- delay_analysis.csv
|   |-- route_efficiency_analysis.csv
|
|-- notebooks/
|   |-- Matatu_Route_Efficiency_Analysis.ipynb
|
|-- README.md
```

## A Few Limitations

There are some things worth keeping in mind when interpreting the results:

- The dataset is simulated, so the findings should not be treated as actual transport statistics.
- The results depend on the assumptions used when generating the data.
- Revenue is not the same as profit. Expenses such as fuel, wages, and vehicle maintenance were not included.
- For this analysis, a trip was classified as on time if its delay was 10 minutes or less. This was a project assumption, not an official transport industry standard.

## What This Project Helped Me Practise

Through this project, I got practical experience with:

- Generating and working with structured datasets.
- Inspecting data and carrying out quality checks.
- Using Pandas for grouping, calculations, and aggregation.
- Exploring patterns in operational data.
- Calculating and comparing performance indicators.
- Creating charts to communicate findings.
- Organizing analysis results into reusable reports.

## Author

**Shirleen Munene**

GitHub: [MuneneShirleen](https://github.com/MuneneShirleen)
