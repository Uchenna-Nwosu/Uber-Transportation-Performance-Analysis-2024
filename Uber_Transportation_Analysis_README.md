# Uber Transportation Company Performance Analysis, 2024

## Project Overview
This project analyzes 150,000 Uber ride-order records from 2024 to understand booking activity, ride completion, cancellations, incomplete rides, payment preferences, customer ratings, and operational patterns.

The analysis was developed in Microsoft Excel using data cleaning, PivotTables, calculated fields, slicers, and an interactive dashboard.

## Business Objective
The goal of the analysis was to identify patterns that can support better operational decisions around:

- Ride-order trends
- Customer cancellations
- Driver cancellations
- Incomplete rides
- Payment preferences
- Customer ratings
- Time-based booking behavior

## Dataset
The dataset contains 150,000 ride-order records with fields including:

- Date and time
- Booking ID
- Booking status
- Customer ID
- Vehicle type
- Pickup and drop locations
- Average vehicle arrival time
- Average customer arrival time
- Customer cancellation details
- Driver cancellation details
- Incomplete ride details
- Booking value
- Ride distance
- Driver rating
- Customer rating
- Payment method

## Tools Used
- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel formulas
- Dashboard design and data visualization

## Key Performance Indicators
- Total ride orders: **150,000**
- Completed rides: **93,000**
- Completion rate: **62%**
- Customer cancellations: **10,500 (7%)**
- Driver cancellations: **27,000 (18%)**
- No driver found: **10,500 (7%)**
- Incomplete rides: **9,000 (6%)**

## Key Findings

### 1. Ride Order Trend
Ride demand remained relatively stable throughout 2024.

- Highest monthly ride orders: **July — 12,897**
- Lowest monthly ride orders: **February — 11,927**

The relatively narrow gap between the highest and lowest months suggests steady demand throughout the year.

### 2. Customer Cancellation Pattern by Time
Customer cancellations increased during the daytime and evening periods.

- Peak customer cancellation hour: **6 PM**
- Share of customer cancellations at 6 PM: **8.47%**
- Other high periods included **7 PM (7.83%)** and **5 PM (7.10%)**

This indicates that cancellation activity is concentrated around evening travel periods.

### 3. Incomplete Ride Analysis
The 9,000 incomplete rides were almost evenly distributed across three causes:

- Customer Demand: **3,040**
- Vehicle Breakdown: **3,012**
- Other Issue: **2,948**

This suggests that incomplete rides are not driven by one single operational issue.

### 4. Payment Method Preference
Payment information was available for 102,000 completed or incomplete rides.

- UPI: **45,909**
- Cash: **25,367**
- Uber Wallet: **12,276**
- Credit Card: **10,209**
- Debit Card: **8,239**

UPI was the most frequently used payment method.

### 5. Customer Rating Records by Vehicle Type
Auto accounted for the largest share of rides with recorded customer ratings, followed by Go Mini and Go Sedan.

- Auto: approximately **24.9%**
- Go Mini: approximately **20.0%**
- Go Sedan: approximately **17.9%**
- Bike: approximately **15.1%**
- Premier Sedan: approximately **12.1%**
- eBike: approximately **7.0%**
- Uber XL: approximately **3.0%**

## Recommendations
1. Increase operational attention around the evening peak, particularly between 5 PM and 7 PM, when customer cancellations are highest.
2. Investigate driver-side cancellation causes because driver cancellations account for a larger share of ride orders than customer cancellations.
3. Improve vehicle reliability and ride-fulfillment processes to reduce incomplete rides.
4. Maintain strong digital-payment support, especially for UPI, while keeping alternative payment options accessible.
5. Track cancellation patterns by vehicle type, pickup location, drop location, and time period to identify recurring operational hotspots.

## Dashboard
The interactive Excel dashboard includes:

- Ride Orders Trend Analysis
- Customer Cancellation Rate by Time of Order
- Cancellation Analysis by Pickup Location
- Cancellation Analysis by Drop Location
- Driver Rating Analysis
- Customer Rating Analysis by Vehicle Type
- Incomplete Ride Analysis
- Payment Method Preference
- Interactive slicers for vehicle type, payment method, month, date, and time

## Conclusion
The analysis shows that Uber experienced steady ride demand throughout 2024, but ride fulfillment presents opportunities for improvement. While 62% of orders were completed, driver cancellations represented 18% of all ride orders and customer cancellations represented another 7%. Evening periods recorded the strongest customer-cancellation activity, while incomplete rides were distributed almost equally among customer demand, vehicle breakdown, and other issues.

The dashboard provides an interactive view of these patterns and allows users to explore performance across multiple dimensions.
