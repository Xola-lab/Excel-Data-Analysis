# Project - Analysing Online Store Data using Excel

# Executive Summary
### Objective:
To analyse sales data from an online store (Kaggle dataset) to uncover key insights about customer behaviour, revenue trends, and product performance, using Excel’s advanced data analysis tools.

### Skills Highlight:
- Data Cleaning and Preparation.
- Pivot Tables and Charts.
- Time Series Analysis.
- Descriptive Statistics.
- Dashboard Creation.

### Key Insights:
Identified key revenue trends through time series analysis, revealing seasonal spikes.
Discovered a significant female customer base, allowing for targeted marketing.
Highlighted dominant payment methods (Card Payments, Digital Wallets), suggesting optimization opportunities.

### Impact:
This analysis provides actionable insights that can help inform marketing strategies, optimise payment infrastructures, and enhance product offerings, leading to improved business decisions.

# 1 - Introduction
Welcome to this exploration of Data Analysis, where analytical reasoning intersects with numerical insights and spreadsheet tools. In this Excel project, much like a data analyst systematically investigating key patterns, I embarked on an in-depth examination to uncover hidden insights within the dataset. Join me as we navigate through data-driven methodologies, where each cell and formula contributes to a comprehensive understanding of the underlying trends and opportunities. Let's begin the analysis.

# 2 - Cleaning and Transformation
### Data Cleaning and Transformation:
<p align="center">
<img src="RAW DATA.png">
</p>

The raw dataset was meticulously cleaned and transformed to ensure accuracy:

<p align="center">
<img src="CLEAN DATA.png">
</p>

I utilised Excel functions to remove unnecessary spaces for consistent formatting. Conditional Formatting highlighted key anomalies. For example, the categorisation of payment methods was standardised using:
```excel
=IF(L2=0, "Digital Wallets", IF(L2=1, "Card", IF(L2=2, "PayPal", "Other")))
```

# 3 - Utilising Pivot Tables
### Utilising Pivot Tables:
Leveraging Pivot Tables and dynamic charts, I conducted a comprehensive analysis to extract meaningful insights. This functionality enabled the discovery of patterns, such as sales volume by product category and customer demographics. Below is an example of a Pivot Table summarising Payment Methods, highlighting trends for strategic decision-making.

<p align="center">
<img src="PAYMENT METHOD.png">
</p>

# 4 - Dashboard Creation
### Dashboard Creation:
The culmination of my analysis is a comprehensive Dashboard that provides an intuitive overview of key metrics and trends. It includes visualisations like revenue trends, customer demographics, and payment method distribution. Each element is designed to facilitate quick insights for stakeholders, ensuring data-driven decisions are informed and timely.

<p align="center">
<img src="DASHBOARD - FINAL.png">
</p>

# 5 - Recommendations
The analysis of the Online Store dataset has provided actionable insights to drive informed decision-making. After thoroughly examining the data and presenting key findings through a dynamic Dashboard, the following strategic recommendations are proposed:

### Revenue Trends (Time Series Analysis):
The Time Series Line Chart reveals revenue fluctuations over several months. A close examination of these trends is essential for identifying periods of growth and potential areas of concern. If we observe consistent upward movement, this suggests that current strategies are effective and should be replicated. However, any sudden declines or unusual spikes warrant further investigation, as they may be indicative of external market pressures or internal operational inefficiencies.

### Customer Demographics (Gender Distribution):
Analysing the gender distribution of the customer base reveals that a significant proportion of the store’s clientele is female. This insight can inform targeted marketing strategies and product offerings, optimising engagement with this key demographic. Understanding customer preferences at this level provides an opportunity to tailor campaigns that resonate with the most responsive audience.

### Payment Methods (Customer Preferences):
The analysis of payment methods highlights the dominance of Card Payments and Digital Wallets among customers. To enhance the user experience and streamline transactions, it may be beneficial to further optimise these payment methods, ensuring they are prominently accessible and user-friendly. Improving the payment infrastructure based on these preferences could lead to increased customer satisfaction and retention.

# Conclusion
In conclusion, the insights gathered from this analysis provide a strong foundation for refining the store's approach to revenue growth, customer engagement, and payment optimisation. By continuously leveraging data-driven insights, the store can position itself for ongoing success in a competitive e-Commerce landscape.
