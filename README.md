# EDA-PROJECT-1
🍽️ Zomato Data Analysis & Exploratory Data Analysis (EDA)
This project focuses on a comprehensive Exploratory Data Analysis (EDA) of a Zomato restaurant dataset. The goal is to uncover key insights into global restaurant distribution, rating patterns, service availability, and essential business metrics across different countries.

Project Overview and Methodology
The analysis was performed using Python and standard data science libraries, primarily Pandas for data manipulation and Matplotlib/Seaborn for visualization (as suggested by the eda-feature-engineering.ipynb filename).

1. Data Integration and Preparation
Dataset Merge: The primary zomato.csv file was merged with the Country-Code.xlsx - Sheet1.csv file using the country code to enrich the data with actual country names, facilitating geographical analysis.

Initial Cleaning: Data quality checks were performed to handle missing values and inconsistencies (implied by the EDA process).

2. Geographical and Business Insights
Global Presence: Identification of the top contributing countries with the highest number of restaurant listings (e.g., India, United States, and United Kingdom were found to be the leaders).

Currency Mapping: Analysis of the local currency used by each country present in the dataset, which is crucial for potential financial analysis.

Online Services: A critical finding was the limited availability of advanced services, with only India and UAE offering the online delivery option.

3. Rating and Score Distribution Analysis
Aggregate Rating: A deep dive into the distribution of aggregate ratings, including an analysis of the correlation between the rating value, the associated color, and the rating text (e.g., 'Excellent', 'Good', 'Poor').

"Not Rated" Restaurants: Focused analysis on restaurants with a 0.0 rating (i.e., "Not rated"). A significant discovery was the high count of "Not rated" listings in certain countries, most prominently in India, indicating areas for data completeness or business focus.

4. City-Level Distribution
Exploration of the top 5 most frequent cities in the dataset to understand where Zomato's listings are most heavily concentrated.

Key Tools Used
Python

Jupyter Notebook (eda-feature-engineering.ipynb)

Pandas

Matplotlib/Seaborn (implied for visualization)
