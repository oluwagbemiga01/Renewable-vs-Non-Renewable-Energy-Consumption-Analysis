![](https://github.com/oluwagbemiga01/Renewable-vs-Non-Renewable-Energy-Consumption-Analysis/blob/main/transition.jfif)

# Energy Consumption and Sustainability Intelligence Dashboard

## Project Overview
This project analyzes renewable and non-renewable energy consumption patterns across multiple locations, with a focus on energy utilization trends, seasonal performance, emission factors, and sustainability metrics.

The dashboard was developed to support energy performance monitoring and sustainability focused decision making through interactive visual analytics.

## Business Problem

Organizations and energy stakeholders require visibility into energy consumption patterns, renewable energy adoption, and associated environmental impacts to support sustainable operational planning and energy optimization initiatives.

This project aims to evaluate renewable energy performance, monitor energy consumption trends, and identify opportunities for improving sustainability outcomes.

## Objectives

- Analyze renewable and non-renewable energy consumption
- Monitor total energy usage trends
- Evaluate seasonal energy distribution patterns
- Compare year-over-year renewable energy performance
- Track emission-related metrics
- Support sustainability and energy optimization analysis

## Key KPIs

| KPI | Value |
|---|---|
| Renewable Energy | 33M kWh |
| Non-Renewable Energy | 24M kWh |
| Total Energy Consumption | 56.87M kWh |
| Renewable Energy Share | 58.06% |
| Emission Factor | 389.82 kg CO2/kWh |

## Dataset Description

| Variable | Description |
|---|---|
| Location | Geographic location of energy usage |
| Renewable_Energy | Renewable energy generated or consumed |
| Non_Renewable_Energy | Non-renewable energy consumption |
| Energy_Consumption | Total energy utilized |
| Emission_Factor | Estimated carbon emission factor |
| Season | Seasonal classification |
| Month | Monthly reporting period |

## Data Cleaning & Transformation

The dataset was cleaned and transformed using Power Query to improve analytical consistency and reporting accuracy.

Key transformation steps included:

- Standardizing location naming conventions
- Correcting data types
- Creating calculated energy share metrics
- Preparing seasonal classifications
- Validating consumption totals

## Data Modelling

A star schema data model was implemented to support efficient analytical reporting and improve dashboard performance.

The model consists of a central fact table containing energy consumption metrics connected to dimension tables describing dates.

### Fact Table

The fact table stores measurable energy metrics, including:

- Renewable Energy Consumption
- Non-Renewable Energy Consumption
- Total Energy Usage
- Emission Metrics

### Dimension Tables

| Dimension Table | Purpose |
|---|---|
| Dim_Date | Supports time-based analysis |


### Relationship Structure

One-to-many relationships were established between dimension tables and the fact table to ensure accurate filtering and aggregation across the dashboard.
