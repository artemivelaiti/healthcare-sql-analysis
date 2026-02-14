# Healthcare SQL Analysis

## Project Overview
This project analyzes hospital bed availability and utilization across counties using SQL.  
The objective is to extract meaningful insights about healthcare capacity, regional resource distribution, and operational pressure across different areas.

## Dataset
The dataset contains hospital-level information including:

- Facility name
- County
- Available beds (BED_AVL)
- Licensed beds (BED_LIC)
- Operational days (DAY_PER)
- Audit indicators and reporting details

These fields enable analysis of **capacity, utilization rates, and regional healthcare demand**.

## SQL Analysis Performed
Key analytical queries include:

1. **Top hospitals by reporting frequency**  
   Identifies facilities with the highest number of records.

2. **Average operational days by county**  
   Measures hospital activity stability across regions.

3. **Total available beds by county**  
   Highlights areas with the greatest healthcare capacity.

4. **Bed utilization rate by county**  
   Calculates utilization using:
   to detect overloaded or underutilized regions.

## Key Insights
- Some counties show **utilization above 100%**, suggesting reporting inconsistencies or extreme demand.
- Large metropolitan counties dominate **total bed availability**, revealing unequal resource distribution.
- Smaller counties often operate at **near-full utilization**, indicating vulnerability during demand spikes.

## Business Value
This analysis demonstrates how SQL supports:

- Healthcare capacity planning  
- Regional resource allocation  
- Early detection of system stress  
- Data-driven operational decision-making  

## Tools Used
- SQL (SQLite)
- DB Browser for SQLite
- GitHub for version control and portfolio presentation

## Author
**Artemi Velaiti**  
Aspiring Data Analyst focused on healthcare and business analytics.
