# AWG Business Analyst Project — New Item Sales Performance Analysis

## Overview
This project was a client-facing business analytics project completed for AWG. The goal was to evaluate which store support approaches were associated with stronger early sales performance for newly launched items.

I led the analytical work by structuring the dataset, defining the comparison approach, building KPI reporting, and interpreting the results for a client-facing presentation.

## Business Problem
When new items are introduced, stores may receive different levels of launch support. The core business question for this project was:

**Which store support approach is associated with better early sales performance in the first few months after a product launch?**

The analysis focused on understanding whether stores receiving stronger combined support outperformed stores with less or no support.

## Project Scope
- **Granularity:** Store × Item × Month
- **Time Window:** First 6 months after launch
- **Analytical Focus:** Early sales lift and new item performance
- **Approach:** KPI reporting + controlled regression analysis

## My Role
I led the analytical portion of the project and contributed to turning the results into a business-facing recommendation. My responsibilities included:
- Building the analytical dataset structure
- Comparing early sales performance across store groups
- Creating KPI reporting views for business interpretation
- Using regression analysis to separate support impact from product-level differences
- Summarizing findings in a client-facing format

## Methodology
I approached the project using two complementary analytical lenses:

### 1. Descriptive KPI Reporting
I built reporting views to compare **average sales** across store groups, brands, and months.

Averages were used instead of totals because some store groups were much larger than others, which could make raw totals misleading.

### 2. Controlled Regression Analysis
I used regression to compare store groups while holding the product constant. This helped isolate the likely effect of support approach from differences caused by the item itself.

This combination of descriptive and controlled analysis helped produce findings that were more meaningful for business decision-making.

## Key Findings
- Stores receiving the **strongest combined support** showed the clearest positive lift in early sales performance
- The strongest impact appeared around **Month 3**
- Simple descriptive totals alone could be misleading because the largest group contained many more stores
- A more balanced interpretation required focusing on averages and controlled analysis rather than raw totals

## Business Value
This project reflects the kind of work involved in business analytics and business analyst roles:
- turning a real business question into a measurable analysis
- structuring messy data into a usable format
- selecting methods that support fair comparison
- translating findings into recommendations stakeholders can use

The results can help support decisions around rollout strategy, launch support, and how to measure early performance for newly introduced products.

## Tools Used
- SQL / Azure SQL
- Excel
- Python
- Regression analysis
- KPI reporting
- Client-facing presentation development

## Repository Contents
This repository includes selected project materials, such as:
- final presentation deck
- selected visuals
- sanitized project summary

## Note on Confidentiality
This repository is a **sanitized public version** of the project.

To respect confidentiality:
- raw client data is not included
- internal working files are not included
- only selected materials relevant for project showcase purposes are shared

## Author
**Avish Shakwala**
MS in Business Analytics, University of Illinois Urbana-Champaign
