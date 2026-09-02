# India-Port-Level-Export-Analytics(2018-2024)
Data analysis of India’s port-level exports by principal commodity, covering export trends, commodity-wise performance, and key insights using Python.

## Project Overview

This project analyzes **India’s port-level export data from 2018 to 2024** at the principal commodity level.

The analysis focuses on understanding India's export performance across **years, states, ports, destination countries, and principal commodities**. Python-based data cleaning, statistical analysis, exploratory data analysis, and visualization techniques are used to identify important export trends, major contributors, and business insights.

The project transforms a large-scale export dataset into meaningful analytical findings that help understand **overall export performance, commodity-wise contribution, state-wise performance, yearly trends, and export concentration**.

## Business Problem

India’s export dataset contains a large number of records across **years, states, ports, destination countries, and principal commodities**. Analyzing this large volume of data manually makes it difficult to identify important export patterns and performance differences.

There is a need to systematically analyze the data to understand **overall export performance, major contributing commodities, state-wise export performance, yearly trends, commodity-state relationships, and export concentration**.

This project addresses the problem by applying **data cleaning, statistical analysis, exploratory data analysis, and data visualization using Python** to convert the raw export data into meaningful business insights.

## Project Objectives

1. **Analyze the overall export performance of India** across the available years based on export value and quantity.

2. **Identify the top-performing principal commodities** based on their contribution to total export value.

3. **Analyze state-wise export performance** and identify major exporting states.

4. **Examine yearly export trends** to understand changes in export performance over time.

5. **Analyze the relationship between commodities and states** to identify major commodity-state combinations.

6. **Identify commodity-wise changes across years** and understand how commodity performance varies over time.

7. **Measure the contribution and concentration of commodities and states** in total exports.

## Dataset Description

The dataset used for this project contains **India’s export data at the principal commodity level** for the period **2018–2024**.

| Attribute | Details |
|---|---|
| **Dataset Name** | Exports at Principal Commodity Level |
| **Source** | India Data Portal / Directorate General of Commercial Intelligence and Statistics (DGCI&S) |
| **Location** | India |
| **Domain** | Commerce / International Trade / Exports |
| **Time Period** | 2018–2024 |
| **Granularity** | State / Port / Principal Commodity |
| **Frequency** | Monthly |

### Dataset Features

The dataset contains export information across **states, ports, destination countries, and principal commodities**.

| Column | Description |
|---|---|
| `id` | Unique record identifier |
| `date` | Export date |
| `state_name` | Name of the exporting state |
| `state_code` | State code |
| `country` | Destination country |
| `port` | Export port |
| `pc_code` | Principal commodity code |
| `commodity` | Principal commodity name |
| `units` | Measurement unit |
| `quantity` | Export quantity |
| `dollars_value` | Export value in USD |
| `inr_value` | Export value in INR |

   
