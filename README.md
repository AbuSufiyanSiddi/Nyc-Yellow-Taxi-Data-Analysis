# Nyc-Yellow-Taxi-Data-Analysis
• NYC Yellow Taxi Trip Analysis: cleaned and explored 3.5M+ trip records in Python (Pandas, NumPy, Matplotlib, Seaborn) to study demand patterns, peak hours, and popular routes.
Objective

Understand trip activity, time patterns, distance, duration, passenger behavior, locations, routes, payment types, vendors, and rate codes.

**Dataset**
Source: NYC Taxi & Limousine Commission (TLC) Trip Record Data
File: yellow_tripdata_2025-01.parquet
Size: about 3.5M records, 22 columns
Note: the dataset has no fare, tip, revenue, customer ID, or driver ID, so the analysis makes no financial claims.

**Tools**
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

**Workflow**
Data understanding and data-quality assessment (missing values, duplicates, data types, category profiling)
Cleaning in a separate clean_df: removed negative distances and passenger counts, trips with drop-off before pickup, and zero-duration trips
Outlier investigation using IQR for distance, duration, and speed (investigated, not blindly deleted)
Feature engineering: trip_duration_minutes, pickup_hour, day_of_week, is_weekend, average_speed_mph, distance_category, duration_category, route
Statistical analysis with NumPy: mean, median, variance, standard deviation, percentiles
Exploratory analysis and 20 visualizations (hourly and daily trips, demand heatmap, distributions, boxplots, top routes, peak vs off-peak, vendors, payment types, rate codes)

**Limitations**
Covers January 2025 only, so it may not represent other months or seasons
Location IDs are Taxi Zone IDs, not neighborhood names, without a lookup table
Correlation shows association, not causation
Traffic, weather, and events are not in the data
Files
notebook.ipynb: full analysis
report.pdf: final project report

Author
**Abu Sufiyan Siddi**
