# Customer-Retention-Analysis
Customer Retention &amp; Demographic Insight Dashboard (Excel Data Analysis Project)

# Executive Summary

## Business Problem:
The company needed to understand customer retention patterns and demographic behavior to improve loyalty and target marketing efforts more effectively. The dataset contained customer details, demographics, and income data but lacked clear segmentation and insight into which groups were most valuable or at risk of churn.

## Solution:
Cleaned, transformed, and analyzed the customer dataset in Excel, creating a comprehensive view of customer demographics, income distribution, and home ownership patterns.
A dynamic PivotTable dashboard was developed to visualize key patterns such as gender distribution, income by occupation, age group by gender, and wealth category by marital status.

## Impact:

- Enabled data-driven understanding of customer wealth and demographics.

- Identified key income-driving occupations and dominant wealth groups.

- Created a scalable dashboard that updates automatically with new data.

## Next Steps:

- Apply AB testing for customer retention campaigns.

- Train teams to use the dashboard for client targeting.

- Track and measure campaign email/text open and click rates.

# Business Problem

The organization lacked insight into the demographic and financial characteristics of its customer base, making it difficult to design effective retention or upsell strategies.
Key questions included:

- Which gender and marital groups own homes more often?

- Which occupations generate the highest total income?

- What are the wealth distribution patterns across marital statuses?

- How do age and gender relate to customer categories?

By answering these, management could better target communications and improve retention programs.

# Methodology

## Data Cleaning & Transformation

- Removed duplicates and missing records.

- Combined First Name and Last Name into a single Full Name field.

- Extracted Year of Birth from the date of birth column.

- Standardized Gender and Marital Status (e.g., “M” → “Male”, “S” → “Single”).

- Extracted Username from Email using text formulas.

- Created Wealth Category from Annual Income using nested IF statements:
-     =IF(N2>=150000,"Wealthy",
       IF(N2>=100000,"Rich",
       IF(N2>=50000,"Average","Poor")))

## Pivot Table Analysis

Built multiple PivotTables to answer key business questions:

- How many male vs. female customers own a home versus those who don’t?

- Which occupations contribute the highest total annual income?

- What is the average number of children per customer by wealth category?

- How does Age Group distribution differ by Gender?

- How many customers fall into each wealth category (Rich, Average, Poor), grouped by Marital Status (Single, Married)?

## Visualization & Dashboard

Designed a PivotTable-based dashboard with dynamic charts and slicers:

- Pie Chart → Gender vs. Home Ownership

- Column Chart → Occupation vs. Total Income

- Bar Chart → Average Children per Wealth Category

- Clustered Chart → Wealth Category by Marital Status

- Age-Gender Breakdown Visual

Applied consistent Blue–Green palette for readability and professionalism.

# Skills & Tools Used
## Data Analysis & Excel Skills
- Data Cleaning & Standardization

- Text Manipulation (LEFT, RIGHT, MID, FIND, LEN, CONCAT, TEXTJOIN)

- Date Extraction (YEAR, MONTH, DAY)

- Conditional Logic (IF, IFS, IFERROR)

- Aggregations (SUMIFS, COUNTIFS, AVERAGEIFS)

- PivotTables & Charts

- Dynamic Dashboards

## Tools & Technologies

- Microsoft Excel (Primary Tool)

- Formulas: Data manipulation, income categorization, and KPIs

- PivotTables: Data summarization and filtering

- Visualization Tools: Charts, Slicers, KPI Cards

# Results & Insights

## Key Findings:

- Male vs Female Ownership: Males had a higher rate of home ownership, while females had slightly higher proportions in rental categories.

- Top Occupations: Certain professional roles (e.g., Management, Skilled Labor, and Clerical) contributed the highest total annual income.

- Children vs Wealth: Wealthier customers tended to have fewer children, while average-income groups showed larger household sizes.

- Age Group by Gender
  !Img alt[

- Wealth vs Marital Status

# Business Recommendations

- Target married professionals with high income for premium product promotions.

- Design family-oriented offers for middle-income groups with more children.

- Develop retention programs focusing on age groups with declining engagement.

- Personalize outreach based on income category and marital status.

- Use customer profiles (username, demographics, wealth) for segmentation in email and loyalty campaigns.

