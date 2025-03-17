# Optimization-Project-Realignment-of-Regional-Office-for-RAM-Wireless

This project addresses an optimization challenge involving the allocation of stores to regional offices while considering factors such as travel costs, geographic proximity, and operational capacity. The goal was to minimize overall operational expenses while maintaining a balanced and manageable workload for each office.

# Problem Statement
The existing store-to-office assignment follows a nearest-office approach, prioritizing travel distance but overlooking office capacity, leading to inefficiencies such as:

High travel costs

Uneven workload distribution

Underutilization of certain offices

The goal of this project was to develop an optimized allocation model for 50 stores, ensuring cost-effective assignments while maintaining office workload feasibility.

# Methodology
Optimization Model: Developed using AMPL, incorporating constraints related to travel costs, service capacity, and geographic feasibility.

Cost Considerations: Factored in mileage costs ($0.585 per mile) and employee salary expenses ($26 per hour of travel time).

Decision Variables: Ensured each store was assigned to exactly one office while balancing workload distribution.

Refinement Process: Introduced manual adjustments to enhance geographic feasibility and further reduce operational costs.


# Results & Insights

The initial optimization model lowered total operational costs to $195,479.31 but resulted in some geographically inefficient assignments.

Manual refinements improved cost efficiency and alignment, reducing costs further to $194,130.69.

A hybrid approach, integrating geographic constraints with manual adjustments, was recommended for optimal store allocation.


# Key Takeaways

Mathematical optimization is a valuable tool for improving logistics and operational efficiency.

Manual refinements can complement algorithmic solutions by addressing real-world constraints.

Future improvements could include dynamic penalties for distant assignments or capacity expansion in high-demand regions to enhance overall efficiency.

