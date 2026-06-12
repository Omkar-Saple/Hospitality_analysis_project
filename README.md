
# Hospitality Analysis using Python & Pandas

## Project Overview

This project analyzes hotel booking and revenue data to generate business insights for a hospitality company. The analysis focuses on occupancy rates, revenue performance, hotel capacity utilization, customer ratings, and city-wise hotel performance.

The project demonstrates the complete Data Analytics workflow including:

* Data Import
* Data Exploration
* Data Cleaning
* Data Transformation
* Data Visualization
* Business Insights Generation

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Dataset Information

The project uses the following datasets:

* `fact_bookings.csv`
* `fact_aggregated_bookings.csv`
* `dim_hotels.csv`
* `dim_rooms.csv`
* `dim_date.csv`
* `new_data_august.csv`

---

## Project Workflow

### 1. Data Exploration

Performed exploratory analysis on booking data including:

* Dataset dimensions
* Unique room categories
* Booking platforms
* Descriptive statistics
* Hotel categories and cities

### 2. Data Cleaning

Data quality issues handled:

* Removed records with invalid guest counts
* Detected and removed revenue outliers
* Analyzed missing values
* Validated booking and capacity data

### 3. Data Transformation

Created new business metrics such as:

* Occupancy Percentage

Formula:

Occupancy % = (Successful Bookings / Capacity) × 100

### 4. Data Analysis & Insights

Generated business insights including:

#### Occupancy Analysis

* Average occupancy rate by room category
* Average occupancy rate by city
* Weekday vs Weekend occupancy comparison
* Monthly occupancy trends

#### Revenue Analysis

* Revenue realized per city
* Month-wise revenue performance
* Revenue by hotel type
* Revenue by booking platform

#### Booking Analysis

* Total bookings per property
* Capacity utilization analysis
* Overbooked property detection
* Property-wise performance evaluation

---

## Key Questions Solved

* Which room category has the highest occupancy?
* Which city performs best in terms of occupancy?
* Are weekends more occupied than weekdays?
* Which booking platform generates the highest revenue?
* Which properties exceed their capacity?
* What is the monthly revenue trend?

---

## Sample Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Transformation
* Data Visualization
* Business Analytics
* Pandas Data Manipulation
* Real-world Dataset Analysis

---

## Learning Outcomes

Through this project I learned:

* Working with multiple datasets
* Merging and joining dataframes
* Handling missing values and outliers
* Creating derived metrics
* Performing business-focused analysis
* Visualizing insights using charts
* Building an end-to-end data analytics project


