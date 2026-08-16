# KPC-EDA-Operational-Diagnostics
Operational diagnostics project using exploratory data analysis, anomaly detection, drill-down analysis, Pareto analysis, and root-cause investigation to identify drivers of throughput losses in an Oil &amp; Gas production environment.

## Business Problem

Production performance varies across operational sites, but the key drivers behind throughput losses are unclear.

This project investigates:
- Where performance degradation occurs
- Which operational factors contribute most
- What actions can improve production reliability

  ## Analytical Approach

The investigation followed an operational diagnostics workflow:

1. Data profiling and quality validation
2. Exploratory Data Analysis (EDA)
3. Anomaly detection
4. Bivariate analysis
5. Drill-down investigation
6. Pareto analysis

   ## Key Findings

The analysis identified:

- Nairobi depot as the primary source of throughput reduction.
- NBI-P03 as the dominant contributor, accounting for ~93% of low-throughput events.
- Missed maintenance as the main failure pattern, representing ~88% of production-loss cases.
- Maintenance-related degradation reduced NBI-P03 median throughput from ~1,057 to ~626 barrels.

  ## Tools Used

Python:
- Pandas
- NumPy
- Matplotlib
- Seaborn

Analytics:
- Exploratory Data Analysis
- Correlation Analysis
- Drill-down Analysis
- Pareto Analysis
- Root Cause Analysis

Reporting:
- CIA Framework
- Operational Diagnostics Reporting
8. Root cause identification
9. Business recommendations
