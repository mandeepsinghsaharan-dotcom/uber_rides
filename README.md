# uber_rides
Uber Ride Analytics & End-to-End SQL Masterclass
Project Overview
This repository contains an end-to-end data analysis project leveraging a dataset of 50,000 Uber ride records. The primary goal of this project is to model real-world ride-hailing operational metrics, identify key performance indicators (KPIs), and demonstrate mastery over real-world SQL queries ranging from basic data aggregation to advanced analytical window functions.

The dataset covers ride telemetry, trip metrics, driver/rider interactions, dynamic pricing behavior, and operational outcomes across six major US metropolitan areas.

Key Dataset Highlights
50,000 Total Records: Real-time telemetry data across major U.S. cities (San Francisco, Boston, New York, Seattle, Chicago, Los Angeles).

Comprehensive Metrics: Includes geographic coordinates (lat/long), trip distance (km), ride durations, dynamic fare amounts, payment methods, and trip completion statuses (Completed, Cancelled, No-Show).

SQL Coverage & Technical Scope
This repository serves as a practical guide for solving industry-level analytical problems using SQL. Key techniques implemented include:

Data Aggregation & Filtering: Multi-dimensional GROUP BY and HAVING clauses for revenue and trip volume distribution.

Time-Series & Date Parsing: Extracting temporal patterns (hourly peak volume, daily trends) using date/time functions.

Window Functions: Ranking drivers, dynamic partitioning (DENSE_RANK, NTILE), and calculating cumulative revenue streams (SUM() OVER).

Advanced Analytics: Lead/lag analysis (LAG()) to measure driver idle intervals and operational downtime.

Conditional Aggregations: Complex dynamic grouping (CASE WHEN) for cancellation rate matrices and ride categorizations.

Self-Joins & Geolocation Logic: Proximity matching and concurrent trip detection.
