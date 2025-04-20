# Data-UBER: Uber Driver Trip Analysis Project

## Overview

This project analyzes An Uber driver trip data to uncover patterns in profitability, efficiency, and route popularity. The goal is to help the driver optimize schedules, maximize earnings, and improve service quality. The analysis covers data cleaning, transformation, and interactive visualization using Tableau.

**Interactive Dashboard:**  

[View the Tableau Public Dashboard](https://public.tableau.com/views/UberTripAnalysisdashboard/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Key Business Questions

- **Most Profitable Hours:** When are the peak earning periods?
- **High-Workload Hours:** What hours did I work the most?
- **Most Profitable Routes:** Which routes generate the most revenue?
- **Efficient Time Allocation:** How can I maximize earnings and minimize downtime?
- **Most Frequent Routes:** What are the most commonly traveled routes?
- **Average Speed:** What is the average speed across trips?

---

## Data Cleaning Log

- Cleaned the revenue column to standardize amount received.
- Converted hour data to 24-hour format.
- Transformed duration and distance fields into integer numbers (no decimals).
- Standardized and cleaned pick-up locations: removed accents, special characters, and harmonized neighborhood names.
- Repeated the cleaning process for drop-off locations.
- Created a new column combining pick-up and drop-off into a single "route" field.
- Filtered out duplicate records.
- Identified and standardized 102 unique neighborhoods, enabling route and neighborhood analysis.
- Created a "time of day" column to group trips into morning, afternoon, and night for richer analysis.
- Retained a seasonal category to track trends across different periods (e.g., season one vs. season two).
- Final cleaning steps included double-checking neighborhood consistency and preparing the data for route mapping and heatmaps.

---

## Tableau Dashboard Development

- Designed the dashboard layout to reflect Uber's quality standards.
- Created calculated fields for key KPIs:
  - Total bookings
  - Total booking amount
  - Average booking amount
  - Total trip distance
  - Average trip distance
  - Average trip time
- Added filters for drop-off locations and selected charts to answer core business questions.
- Beautified the dashboard for clarity and impact.

---

## Expected Outcomes

- **Identify trends** in bookings and revenue generation.
- **Analyze trip efficiency** (distance and duration).
- **Compare booking values and trip patterns** across different times of day and seasons.
- **Provide actionable insights** to:
  - Schedule work for maximum profitability.
  - Reduce wasted time and operational costs.
  - Improve customer satisfaction.

