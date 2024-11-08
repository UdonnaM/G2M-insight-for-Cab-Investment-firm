# G2M-insight-for-Cab-Investment-firm

This repository contains a detailed analysis of two cab companies aimed at supporting XYZ's investment decision in the rapidly growing cab industry. The project involves analyzing multiple datasets covering transaction details, customer demographics, and city statistics from 2016 to 2018. Through exploratory data analysis (EDA), hypothesis testing, and visualizations, the goal is to identify key trends and provide actionable insights to determine which company represents a better investment opportunity. The findings are intended to inform XYZ's strategic decisions and will be presented to their Executive team.

**Project Overview**

Objective: Provide actionable insights into the cab market by analyzing ride volumes, profitability, customer demographics, and market trends over a three-year period (2016-2018).

**Scope:**

    i.    Data Integration: Merging multiple datasets to create a unified data view.

    ii.   Exploratory Data Analysis (EDA): Visual and statistical analysis to identify key trends.

    iii.  Hypothesis Testing: Investigating targeted hypotheses for specific business questions.

    iv.   Recommendations: Insights and guidance on the optimal investment opportunity based on the data.

**Key Deliverables**

- EDA Notebook: Contains comprehensive data exploration, hypothesis testing, and key visualizations.

- Data Intake Report: Outlines data preparation steps, integrity checks, and key dataset properties.

- Presentation Slides: Summarizes findings, insights, and final recommendations for XYZ’s executive team.

**Datasets Used**

    i.    Cab_Data.csv: Transaction data of two cab companies.
   
    ii.   Customer_ID.csv: A mapping table of customer IDs and demographic details.
    
    iii.  Transaction_ID.csv: Transaction-to-customer mapping including payment mode.
    
    iv.   City.csv: U.S. city demographics, including population and cab user count.

**Methodology**

**Step 1: Data Pre-processing and Integration**

- Data Cleaning: Removal of missing values, duplicates, and irrelevant data.

- Data Integration: Merging all datasets using Excel’s VLOOKUP to create a comprehensive dataset with 14 features and 359,394 records.

- Profit Calculation: Added a calculated profit column to facilitate financial analysis.

**Step 2: Exploratory Data Analysis (EDA)**

- Customer Insights: Analysis of demographics by company to understand customer segments.

- City-Level Demand: Examined ride volume and revenue across metropolitan and smaller cities.

- Seasonal Trends: Identified usage patterns across years to spot peak periods.

**Step 3: Hypothesis Testing**

To further validate insights, we tested several hypotheses:

- Gender Usage Patterns: Do usage rates differ significantly between males and females?

- Profitability Comparison: Does Yellow Cab have a significantly higher profit margin than Pink Cab?

- Income-Based Revenue: Are high-income customers driving more revenue for Yellow Cab?

- Trip Cost: Is there a difference in the average trip cost between the companies?

- Payment Preferences: Does payment mode impact cab usage frequency?

**Step 4: Insights and Recommendations**

From the analysis, we derived the following insights:

- Market Share: Yellow Cab consistently holds a larger market share, with high annual usage.
  
![Annual Cab Usage](G2M-images/Annual%20cab%20usage.png)

- Profitability: Yellow Cab exhibits a higher average profit margin (30.1%) compared to Pink Cab (17.4%).
  
![Avearge Profit Margin](G2M-images/Average%20profit%20margin%20by%20company.png)

- Customer Retention: A significant percentage of Yellow Cab’s users are repeat customers (83.1%), suggesting loyalty.
  
![cleaned data](G2M-images/Revenue%20contribution%20from%20repeat%20customers.png)

- Target Customer Segments: High-income earners and younger age groups predominantly prefer Yellow Cab.
  
![cleaned data](G2M-images/Revenue%20contribution%20by%20income%20category%20and%20company.png)

- Operational Efficiency: Yellow Cab demonstrates greater cost efficiency across cities.
  
![cleaned data](G2M-images/Cost%20efficiency%20by%20company%20across%20different%20cities.png)


**Recommendations**

Based on the findings, Yellow Cab is the recommended investment for XYZ due to its strong market presence, higher profitability, and consistent performance across key metrics. Additionally, Yellow Cab’s premium positioning and cost efficiency suggest a sustainable competitive advantage.

**Tools Used**

- Python: Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization.

- Excel: VLOOKUP for initial data integration.

- Jupyter Notebook: EDA and hypothesis testing
