# Optimization-Project-Realignment-of-Regional-Office-for-RAM-Wireless
This project focuses on solving an optimization problem related to assigning stores to regional offices while balancing multiple factors such as travel costs, geographic proximity, and operational capacity.The objective was to minimize operational costs while ensuring that each office's workload remained feasible. 

## Project Overview
This project focuses on optimizing the assignment of stores to regional offices for RAM Wireless, a company operating multiple stores across Virginia. The goal is to minimize operational costs while ensuring workload feasibility across four regional offices: Staunton, Richmond, Warrenton, and Tappahannock. These offices provide essential business services such as inventory management, payroll, hiring, marketing, and merchandising.

## Problem Statement
The current store-to-office allocation follows a nearest-office approach, which minimizes travel distance but fails to consider office capacity, leading to inefficiencies such as:

* Excessive travel costs
* Workload imbalances
* Underutilization of certain offices
* Our objective was to develop an optimization model that assigns 50 stores to regional offices cost-effectively while ensuring that service demands do not exceed office capacity.

## Methodology
*Optimization Model: Developed using AMPL, incorporating constraints for travel costs, service capacity, and geographic feasibility.
*Cost Considerations: Included mileage costs ($0.585 per mile) and employee salary costs ($26 per hour of travel time).
*Decision Variables: Ensured each store is assigned to exactly one office while balancing workload.
*Refinement: Applied manual adjustments to enhance geographic feasibility and reduce operational costs.
*Results & Insights
*The initial model reduced total operational costs to $195,479.31 but resulted in geographically inefficient assignments.
*Manual adjustments improved cost efficiency and geographic alignment, further lowering costs to $194,130.69.
*A hybrid approach combining geographic constraints and manual adjustments was recommended for optimal realignment.

## Key Takeaways
*Mathematical optimization is a powerful tool for logistics and operational efficiency.
*Manual adjustments can enhance algorithmic solutions by addressing real-world constraints.
*Future improvements could explore dynamic penalties for distant assignments or capacity expansion in high-demand regions.

