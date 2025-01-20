**Generated Report **
https://app.powerbi.com/links/Mkzsv0vKML?ctid=131c4223-bcf6-4747-bc82-36fd195e1b49&pbi_source=linkShare



# global_cancer_predictions
**1.Incidence and Mortality Analysis:**

What are the top countries by cancer incidence or mortality rates?
How does mortality vary by age group and cancer type?

**Analysis: Incidence and Mortality Analysis**
This analysis aims to explore and compare cancer incidence and mortality rates across various dimensions such as countries, cancer types, and age groups.

**Key Metrics to Analyze
Incidence Rate:**

Total number of new cancer cases recorded.
Indicator of how widespread the disease is in a specific population.
**Mortality Rate:**

Total number of deaths caused by cancer.
Reflects the severity and potential challenges in treatment.

**Questions to Address**
**Top Countries by Incidence and Mortality:**

Identify countries with the highest and lowest cancer incidence and mortality rates.
Example visualization: A bar chart or map showing top countries by these metrics.
**Cancer Type Distribution:**

Which cancer types have the highest mortality rate relative to their incidence?
Example visualization: A stacked bar chart comparing incidence and mortality rates for each cancer type.
**Age Group Trends:**

How do incidence and mortality rates vary across different age groups?
Example visualization: A line chart or heatmap showing age-specific trends for both metrics.
**Incidence-to-Mortality Ratio:**

Calculate the ratio of incidence to mortality for each country or cancer type.
Example insight: Countries with a low ratio may face challenges like inadequate healthcare or late diagnosis.

**Steps to Implement in Power BI**
**Data Preparation:**

Use the Incidence and Mortality columns as key measures.
**Create calculated fields:**
Incidence-to-Mortality Ratio: Ratio = Incidence / Mortality

**Visualizations:**

Map: Highlight countries based on their incidence and mortality rates using color gradients.
Bar Charts: Compare the top 10 countries by incidence and mortality.
Scatter Plot: Plot incidence against mortality for each country to identify outliers or patterns.
**Filters:**

Add slicers for Country, Cancer_Type, and Age_Group to make the report interactive.



**2.Risk Factor Insights:**

Which risk factors are most associated with high cancer incidence?
What is the correlation between lifestyle factors (e.g., tobacco use, obesity) and cancer rates?

**1. Which risk factors are most associated with high cancer incidence?**
Approach:

Correlation Analysis:
Calculate correlations between risk factor percentages and Incidence. Higher correlations indicate stronger associations.

Example: Use a area chart to  visualize relationships (e.g., Tobacco_Use_% vs. Incidence).
Ranking:
Rank risk factors by their correlation values or incidence contribution.

Example Visualization:

A bar chart or heatmap showing correlations between each risk factor and cancer incidence.

**3.Regional Disparities:** This section focuses on understanding how cancer prevalence varies across regions or countries and the impact of factors like urbanization and population density. 
How does cancer prevalence vary across regions or countries?
What role does urbanization or population density play in cancer rates?

