# From Fear to Flight
### A Data-Informed Guide to Your First Solo Trip

Data analysis of safety, cost of living, and tourism patterns across 87 countries to identify the most accessible destinations for first-time solo travelers.

## Overview
The biggest barrier to solo travel isn't lack of information — it's uncertainty. This project uses data to make that uncertainty more structured and decisions more actionable.

## Data Sources
- **Numbeo Quality of Life Index** — Safety Index, Cost of Living Index
- **World Tourism Economy Data** — Tourism arrivals by country

## Methods
- Data cleaning & standardization (Pandas)
- Country-level merge across two datasets
- Correlation analysis (safety, cost, tourism)
- Visualization (Seaborn, Matplotlib)

## Key Findings
- Safety and cost have only a weak positive correlation (r = 0.357) — cheaper ≠ less safe
- Tourism arrivals are nearly uncorrelated with safety (r = 0.042) — popularity is driven by familiarity, not objective safety
- Southeast Asia (Thailand, Malaysia, Indonesia) balances all three criteria best for beginner travelers

## Limitations
- Cost of Living Index is relative, not an absolute USD measure
- Vietnam & Laos dropped from final dataset due to missing tourism data
- Country-level analysis masks regional differences

## Tools
`Python` `Pandas` `Seaborn` `Matplotlib`
