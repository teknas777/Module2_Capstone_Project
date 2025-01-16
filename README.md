# Module2_Capstone_Project

## Project Overview

This project involves conducting an in-depth Exploratory Data Analysis (EDA) of a dataset related to FedEx Logistics operations. The primary objective is to uncover insights into shipment management, identify factors contributing to delays, and assess cost-effectiveness across global supply chains. These findings aim to enable FedEx to enhance delivery timelines, reduce freight costs, and improve customer satisfaction.

## Business Context

FedEx Logistics operates globally, managing shipments across various industries. The project focuses on analyzing shipment methods, delivery performance, vendor agreements (INCO terms), and product attributes to pinpoint inefficiencies and provide data-driven solutions for streamlining operations.

## Objectives

The key objectives of this analysis are:
Analyze Shipment Performance: Evaluate the impact of shipment modes (air, sea, land) on delivery timelines.
Vendor and Country Insights: Identify vendors and countries with high delay rates and assess the influence of vendor agreements on shipment performance.
Cost Analysis: Examine the relationship between shipment weight and associated freight and insurance costs.
Visualize Trends: Create data visualizations to highlight key patterns and bottlenecks in the logistics process.

## Dataset Details

The dataset includes the following attributes:
Shipment Mode: Transportation method (air, sea, land).
INCO Terms: Vendor agreements and associated terms.
Delivery Dates: Scheduled and actual delivery timelines.
Freight and Insurance Costs: Shipment cost details.
Product Details: Item descriptions, dosage, and weight.
Destination Country: Location of shipment delivery.
Vendor Details: Information about shipment vendors.
Dataset File: FedEx_Logistics.csv

## Key Questions

This analysis aims to address the following questions:
Are specific shipment teams more likely to achieve on-time deliveries?
How does the shipment mode (air, sea, etc.) impact delivery performance?
Which countries experience the highest shipment delays?
Do higher-weight shipments incur proportionately higher insurance costs?
What is the relationship between INCO terms and delivery efficiency?

## Tools and Libraries

The project utilizes the following Python libraries:
Pandas: Data manipulation and analysis.
NumPy: Numerical computations and array operations.
Matplotlib: Static visualizations such as line, bar, and pie charts.
Seaborn: Statistical and enhanced visualizations.
 
## Key Findings

Shipment Mode and Delivery Performance: Air shipments consistently outperformed sea shipments in on-time delivery rates.
Vendor Performance: Certain vendors demonstrated frequent delays, often linked to specific INCO terms.
Country Delays: Destinations such as Vietnam and India exhibited higher delay frequencies compared to countries like the US and those in Europe.
Visualizations
Shipment Mode vs. Delivery Performance: Comparative analysis of on-time delivery rates by transportation mode.
Freight Cost Distribution: Cost analysis across shipment modes and weights.

## Conclusion

The EDA highlighted critical insights into FedEx's logistics operations, such as shipment patterns, vendor inefficiencies, and regional delays. These findings offer actionable recommendations for optimizing delivery schedules and reducing operational costs.

## Next Steps

Develop predictive models to forecast shipment delays.
Examine the impact of revised INCO terms on vendor performance.
Analyze the influence of product attributes (weight, dosage, etc.) on freight and insurance costs.
