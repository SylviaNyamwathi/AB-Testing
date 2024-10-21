# A/B Test Analysis of Marketing Campaigns

## Overview
This analysis focuses on evaluating the performance of three marketing campaigns using A/B testing techniques. The dataset is aggregated by LocationID, PromotionID, and week. The analysis involves pairwise comparisons of the campaigns to determine the best-performing one.

## Methodology
1. **Data Aggregation**: The dataset was aggregated by LocationID and PromotionID before performing statistical tests.
2. **Statistical Analysis**: Pairwise comparisons were conducted using t-tests to compare each campaign against one another. Given the potential for multiple testing problems (increased risk of false positives), a confidence level of 99% was used to ensure the reliability of results.

## Findings
- **Campaign 1** significantly outperformed Campaign 2, with a p-value indicating a statistically significant difference.
- There was no significant difference found between Campaigns 2 and 3, as well as between Campaigns 1 and 3.
- Based on these results, Campaign 1 is recommended as the best-performing campaign.

## Recommendations
- Focus on optimizing Campaign 1 for improved results.
- Consider further testing to differentiate between Campaigns 1 and 3 if more data becomes available.

## Files
- **Excel file**: Contains the data analysis and code used for aggregation and statistical calculations. You can find the file [here](https://1drv.ms/x/c/8a2481f5177c1dbe/EUhT2DsIkslAlWKbmmNqwe4B4ZdYK6PqyiJnbLxVfX-I2Q?e=gLdhnh)
- **Jupyter Notebook (IPYNB)**: Includes the A/B testing analysis.

Please find both the Excel file and the IPYNB file in this repository for detailed insights into the analysis.
