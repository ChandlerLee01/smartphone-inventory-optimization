# Reducing Excess Inventory in Smartphone Production
A Data-Driven Process Optimization Case Study

This project analyzes overproduction in a simulated smartphone manufacturing system and identifies data-driven strategies to reduce excess inventory while maintaining service levels.


## Problem

Overproduction in smartphone manufacturing leads to excess inventory, increasing storage costs, tying up capital, and creating risk of product obsolescence.

In this project, a production system is simulated to analyze how forecasting errors, safety stock policies, and communication gaps contribute to inventory buildup.


## Data and Simulation

A 30-day production system was simulated to reflect real-world manufacturing conditions:

- Daily demand was generated with variability
- Forecasted demand included random error
- Production was based on forecast plus safety stock
- Inventory accumulated as production minus demand

Key metrics tracked:
- Inventory level
- Forecast error
- Inventory turnover
- Stockout occurrences


## Key Findings

The analysis identified three primary drivers of excess inventory:

- Overproduction driven by high safety stock policies
- Forecast inaccuracies leading to mismatch between supply and demand
- Communication gaps, including unshared forecasts and outdated data

Pareto analysis showed that overproduction, forecast not shared, and old data usage accounted for the majority of observed issues.

Overall, inventory buildup was not caused by random variation, but by systematic process inefficiencies.


## Improvements

Based on the identified root causes, the following improvements were tested:

- Reducing safety stock multiplier from 1.15 to 1.05
- Improving forecast accuracy
- Prioritizing recent data over outdated inputs
- Standardizing planning and decision processes


## Impact

Simulation results show significant improvements after implementing changes:

- Average inventory reduced by over 700 units
- Inventory turnover increased from approximately 14 to over 40
- Forecast improvements eliminated stockouts
- Safety stock reduction improved efficiency with minimal stockout risk

These results demonstrate that small adjustments in production policy can lead to substantial operational gains.


## Key Takeaways

- Overproduction is primarily driven by system-level decisions, not random variation
- Safety stock policies have a large impact on inventory levels
- Data-driven adjustments can significantly improve efficiency without sacrificing service levels
- Combining simulation with process analysis enables effective decision-making


