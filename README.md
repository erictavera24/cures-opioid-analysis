# California Opioid Prescribing Analysis — Kern County Focus

## Overview

This project examines opioid prescribing rates across California counties 
using the CURES Metrics by Month, County, and Age Group dataset published 
by the California Department of Justice. The analysis uses Python and pandas 
to clean and process the raw data, calculate opioid prescribing rates per 
100,000 residents, and apply z-score analysis to compare each county against 
the statewide average within each age group.

This project draws on my professional background in Pharmacy Compliance and 
Controlled Substance Investigations, and was built as part of my data analysis 
portfolio targeting healthcare analytics roles.

## Dataset

**Source:** California DOJ CURES Statistics  
**URL:** https://oag.ca.gov/cures/statistics  
**File:** Metrics by Month, County, and Age Group  
**Coverage:** January – June 2025, all 58 California counties, 5 age groups  

## Key Findings

- Adults aged 25–44 in Kern County were prescribed opioids at a significantly 
  higher rate than the statewide average for the same age group, ranking 4th 
  highest among all 58 California counties
- Adults 65 and older in Kern County were prescribed opioids at a lower rate 
  than the statewide average — a pattern consistent across all 6 months of data
- Yuba County was identified as a statewide outlier with a z-score above 3 for 
  the 25–44 age group, including a notable spike in May 2025
- Kern County's elevated rates in working-age adults may be partially explained 
  by the county's large blue collar workforce, where physical labor injuries and 
  chronic pain are more prevalent

## Recommended Next Steps

- Extend the analysis using the CURES annual dataset, available back to 2019, 
  to identify when Kern County's rate for the 25–44 age group first diverged 
  from the statewide trend
- Cross-reference findings with county-level employment and injury data to test 
  the blue collar labor hypothesis
- Investigate Yuba County's May 2025 spike using prescriber-level data

## Tech Stack

- Python (pandas, numpy, matplotlib)
- Jupyter Notebook

## Project Structure

```
cures-opioid-analysis/
├── data/
│   └── Metrics_Month_County_AgeGrp.csv
├── notebooks/
│   └── cures_analysis.ipynb
└── README.md
```

## About

Built by Eric Tavera as part of a data analysis portfolio focused on 
healthcare analytics. Background includes controlled substance compliance, 
pharmacy loss investigations, and KPI reporting across 61 California pharmacy 
locations.
