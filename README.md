 # FUTURE_DS_03: Bank Marketing Campaign Funnel Analysis

## Project Objective
Analyze the marketing funnel for a Portuguese bank's term deposit campaign to identify conversion rates, major drop-off points, and optimize channel performance using Python.

## Dataset
Bank Marketing Dataset from UCI ML Repository - 41,188 customer records with 20 features including age, job, contact method, campaign details, and subscription outcome.

## Key Results
- **Total Customers Contacted:** 41,188
- **Customers Converted:** 4,640 
- **Overall Conversion Rate:** 11.27%
- **Drop-off Rate:** 88.73%

## Key Insights
1. **Major Drop-off Point:** 88.73% of contacted customers did not subscribe, indicating issues with targeting or offer relevance.
2. **Channel Performance:** Cellular contact significantly outperforms telephone and unknown channels in conversion rate.
3. **Campaign Efficiency:** Most conversions happen within the first 2-3 contacts. Conversion drops sharply after 5+ contacts, suggesting diminishing returns.

## Visualizations Generated
1. `overall_funnel.png` - Shows customer journey from contact to conversion
2. `channel_conversion.png` - Conversion rates by contact communication type
3. `dropoff_rates.png` - Percentage of customers lost at each campaign stage

## Tools & Libraries
Python, Pandas, Matplotlib, Seaborn

## How to Run
```bash
pip install pandas matplotlib seaborn
py funnel_analysis.py