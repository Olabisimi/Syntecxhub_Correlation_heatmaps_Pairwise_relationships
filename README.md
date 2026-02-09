<img width="800" height="600" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/812a1392-fd47-42da-ac24-72708ebccf45" />
[Correlation.ipynb](https://github.com/user-attachments/files/25190166/Correlation.ipynb)
<img width="1000" height="1000" alt="pairplot" src="https://github.com/user-attachments/assets/45cf12d3-8802-4c1c-8e5a-7ead8198d681" />
# Syntecxhub_Correlation_heatmaps_Pairwise_relationships
Correlation analysis and pairwise relationship exploration using Python.

## Project Overview
This project explores the relationships between key numerical variables in a retail sales dataset using correlation analysis. Pearson correlation coefficients are computed to quantify linear relationships, and visual tools such as heatmaps and pairplots are used to identify patterns, strengths, and trade-offs between variables.

## Dataset
The analysis uses a cleaned and merged sales dataset containing:
- Sales
- Profit
- Quantity
- Discount
- Customer and order-related attributes

The dataset was reused from previous projects after data cleaning and preprocessing.

## Objectives
- Compute Pearson correlation coefficients between numeric features
- Visualize correlations using a heatmap with annotated values
- Explore pairwise relationships using scatter plots (pairplots)
- Identify strongest positive and negative relationships
- Summarize key insights from the correlation results

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Key Insights
- Sales and Profit show a moderate positive correlation, indicating that higher sales generally lead to higher profit.
- Discounts have a negative relationship with profit, highlighting their impact on margins.
- Quantity has weak correlations with both sales and profit, suggesting volume alone does not guarantee profitability.
- No extremely strong correlations were found, indicating that business performance is influenced by multiple interacting factors.

## Visualizations
- Correlation heatmap (Pearson correlation matrix)
- Pairplots for key variable combinations

All visual outputs are saved in the `outputs/` folder.

## Conclusion
This analysis demonstrates how correlation techniques can uncover meaningful relationships in business data and support data-driven decision-making. The findings provide a foundation for deeper modeling and predictive analysis in future projects.
