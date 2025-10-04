# Salla Company SQL Analysis  

This repository contains a set of SQL queries created to analyze call center performance data for **Salla Company**.  
The main data source used is a table called `Salla_Data`, which stores daily call center metrics for different agents.

## Overview  

The queries in this project were written to:
- Retrieve and filter agent-level records.
- Aggregate daily call center KPIs such as offered calls, handled calls, and abandoned calls.
- Calculate performance indicators including Average Speed of Answer (ASA) and call handling rate.
- Classify daily performance based on ASA thresholds (Excellent, Good, Poor).
- Compare abandoned calls to the average abandoned calls to identify outliers.
- Build a SQL view to easily monitor total handled and offered calls per agent.

## Purpose  

These queries were designed to support reporting and decision-making by:
- Providing insights into agent productivity.
- Highlighting trends in call center operations.
- Simplifying performance tracking with reusable views.

## How to Use  

1. Ensure your database includes a table named `Salla_Data` with the relevant columns (agents, calls, ASA, forecast, etc.).
2. Run the SQL queries in your preferred SQL environment (such as SQL Server Management Studio).
3. Use the created view to generate reports or integrate with dashboards.

## Notes  

- The dataset structure assumes columns like `Agent_Name`, `Calls_Offered`, `Calls_Handled`, `Calls_Abandon`, `ASA`, and `Month`.
- The provided SQL queries can be customized to match different time periods or conditions.
