# Project 1 Impact Of Car Features Analysis

This project analyzes a dataset containing 11,159 car models with 16 attributes, including make, engine, fuel type, MSRP, market category, and fuel efficiency. The goal is to provide insights into consumer demand and profitability, helping car manufacturers optimize pricing strategies and product development.

## Dataset
The dataset includes information on car models, such as:
- Make
- Engine type
- Fuel type
- MSRP (Manufacturer's Suggested Retail Price)
- Market category
- Fuel efficiency (MPG)
- And more...


## Project Description
This project analyzes the relationship between car features, fuel efficiency, pricing, and popularity in the automotive industry...

## Approach
The project involves the following key steps:

1. **Data Cleaning**: 
   - Remove any missing values.
   - Check for outliers in the data.
   - Standardize the format of data for consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Use pivot tables, charts, and descriptive statistics to explore the relationships between the various variables.

3. **Regression Analysis**:
   - Build a regression model to understand the impact of features such as engine type, fuel type, and other factors on the price.

4. **Dashboard Creation**:
   - Develop an interactive dashboard in **Excel** to allow the client to explore pricing, car features, and popularity based on different filters.

5. **Visualization**:
   - Use scatter plots, combo charts, and pivot charts for insights.
   - Apply trendlines in the regression model for better interpretation.
   - Utilize summary statistics to understand the correlation between different variables.

## Technology Used

- **Excel**: Used for data cleaning, pivot tables, and dashboard creation.
- **Advanced Excel Techniques**: Regression analysis, trendlines, pivot charts, and data visualizations.
- **Visualization Tools**: Scatter plots, line charts, bar charts, combo charts, and slicers will be used to make the dashboard interactive and insightful.
- **Functions**: SUMIF, AVERAGEIF, AVERAGEIFS, and correlation functions will be used to calculate averages, sums, and relationships across different variables.

- ## Key Insights:
1. **Market Popularity**: Analyzing how car model popularity varies across market categories.
2. **Price vs. Engine Power**: Understanding how engine horsepower influences pricing.
3. **Price Determinants**: Identifying key features like fuel type and transmission that affect pricing.
4. **Price Across Manufacturers**: Comparing average prices across different car manufacturers.
5. **Fuel Efficiency vs. Engine Cylinders**: Evaluating the relationship between fuel efficiency (MPG) and engine cylinders.


[**View Full Project Report**](https://1drv.ms/b/c/5c04ca5b7bc77dac/EWT7RfsCaatFs_QDdlJjzCYB9icTkdquwclET_Cl3grhhQ?e=AnOtt6)

[**View Excel File with Project Analysis**](https://1drv.ms/x/c/5c04ca5b7bc77dac/Eff3x9ZeBn5OmnmJSvZiJu8B9r2GAyAQVOt2hn19KYg6Eg?e=ss13oP)

# Project 2 Bank Loan Case Study

### Summary
This project involves analyzing a loan dataset for a financial institution to mitigate risks associated with loan approvals. The primary goal is to use Exploratory Data Analysis (EDA) to identify patterns and attributes affecting customer default likelihood.

### Key Objectives
- Identify missing data and handle it appropriately.
- Detect and address outliers.
- Analyze data imbalance and calculate ratios.
- Perform univariate, segmented univariate, and bivariate analysis.
- Segment customers based on risk and provide actionable insights.

### Methodology
1. **Data Understanding:** Understanding attributes like income, credit score, loan amount, etc.
2. **Data Cleaning:** Handled missing data and normalized datasets.
3. **EDA:** Explored individual and interactive variable distributions.
4. **Risk Factor Identification:** Identified attributes associated with loan defaults.
5. **Segmentation:** Grouped customers for targeted strategies.
6. **Recommendations:** Proposed policy changes to mitigate risks.

### Tools Used
- **Microsoft Excel:** Data cleaning, statistical analysis, visualizations.
- **Python (optional):** For deeper insights (if applicable).

### Insights
- Missing data was identified and addressed using median/mode imputation.
- Outliers in variables like income, number of children, and employment years were detected and handled.
- Data imbalance was analyzed (92% of customers had no payment difficulties).
- Variables like credit amount and income were weakly correlated with default likelihood.

### Visualizations
Key trends were visualized, including:
- Income vs. default rates.
- Credit bins vs. applicant distribution.
- Correlation heatmaps for risk factors.

[**View Full Project Report**](https://1drv.ms/b/c/5c04ca5b7bc77dac/EVvufTqxdTBGuMrmiN4sQW0BVDruAiOytO_EM0PJwU0OGQ?e=5u2hCy)

[**View Excel File with Project Analysis**](https://1drv.ms/x/c/5c04ca5b7bc77dac/Ed9FG9BY4lZBvNJiSWI1FtcBF8jM2cgVH_CGTks9NRBT4w?e=0uES1r)


# Project 3 Customer Churn Analysis

### Project Overview
The objective of this project is to analyze customer churn patterns for a telecom company, identify key factors leading to churn, and provide actionable insights to reduce customer attrition.

### Key Insights
- **Churn Rate**: Approximately 26.54% of customers have churned.
- **Tenure**: Customers with longer tenure are less likely to churn.
- **Contracts**: Customers on month-to-month contracts have a higher churn rate compared to one-year or two-year contracts.
- **Payment Method**: Customers using electronic checks are more likely to churn compared to other payment methods.
- **Service Usage**: Lack of services like PhoneService, InternetService (DSL), and OnlineSecurity correlates with higher churn rates.

### Approach
1. **Data Cleaning**:
   - Replaced blank `TotalCharges` values with 0 and converted the column to numeric.
   - Converted binary columns (e.g., `SeniorCitizen`) to more understandable labels (`Yes`/`No`).
2. **Exploratory Data Analysis**:
   - Used univariate, bivariate, and multivariate analysis to uncover churn patterns.
3. **Visualization Tools**:
   - **Seaborn** and **Matplotlib** for creating insightful graphs.

### Tools and Libraries
- **Pandas** for data manipulation.
- **NumPy** for numerical computations.
- **Seaborn** and **Matplotlib** for visualizations.

### Future Scope
- Develop predictive models using machine learning to predict churn based on key features.
- Implement customer segmentation strategies to provide personalized offers for high-risk customers.
  
[**View CSV File**](https://1drv.ms/x/c/5c04ca5b7bc77dac/ESqdAM92sNhEmXB9_uM-NJ8BDWAMub45k_wM3-YfXArrEA?e=Qn5aNj)

[**View Python Code (pdf)**](https://1drv.ms/u/c/5c04ca5b7bc77dac/Ec9twD78nQtGkNhhUhdW5oQBmhF4PKfl-4oygBe7g8Pu4Q?e=xnTS4Q)

[**View Project Report**](https://1drv.ms/b/c/5c04ca5b7bc77dac/EfKKu4QUtxxFp0aIC-eQczsBzYMpN-g6ilI2VSvA1IlpQw?e=dki0mk)

# Project 4 ABC Call Volume Trend Analysis

## Description
This project analyzed **Customer Experience (CX)** data for a company's inbound call operations over 23 days. The goal was to optimize manpower allocation, reduce call abandonment rates, and enhance service efficiency by analyzing call duration, volume trends, and customer interaction data.

## Key Features
- **Call Volume Analysis**: Visualized call volumes by time buckets to identify peak hours, ensuring effective staffing and reduced wait times.
- **Manpower Planning**: Proposed workforce adjustments to lower call abandonment rates from 30% to 10% during peak and night shifts.
- **Call Duration Trends**: Analyzed average call durations to identify patterns and improve customer handling efficiency.
- **Night Shift Optimization**: Designed a night shift staffing plan to address 30% of daily calls occurring during off-hours.

## Tools & Skills
- **Excel**: Data cleaning, pivot tables, and time-based analysis.
- **Statistical Analysis**: Trend identification for improving operational efficiency.

## Outcomes
- Reduced call abandonment during peak hours by optimizing manpower allocation.
- Improved customer experience by ensuring adequate staffing during critical periods.
- Provided actionable insights for effective resource planning and enhanced service levels.

- [**View Full Project Report**](https://1drv.ms/b/c/5c04ca5b7bc77dac/EYBpr4OyCCZJo6ADgoNm7owB5895hlj9V9DylSwJMbP40g?e=G43LO5)

[**View Excel File with Project Analysis**](https://1drv.ms/x/c/5c04ca5b7bc77dac/Eepqx8eoc4ZChJF5Hy6aTSgBuBJsS91tmT_dy5eK6Rsg4A?e=7cmKup)

# Project 5 Sales Performance Project

## Description
This project involved analyzing sales performance data of a superstore using **Power BI** and **Python** to derive insights on sales trends, profitability, and customer behavior. The objective was to support data-driven decision-making and improve business operations.

## Key Features
- **Category Performance**: Identified **Office Supplies** and **Technology** as top-performing categories, with $0.64M and $0.47M sales, respectively.
- **Regional Insights**: Highlighted the **West** as the highest-performing region and the **South** as a growth opportunity.
- **Customer Segmentation**: Consumers accounted for 48% of total sales, offering key insights into customer preferences.
- **Seasonal Trends**: Detected sales peaks in November and December, aligned with holiday promotions.

## Tools & Skills
- **Power BI**: Visualized sales data using bar and line charts to highlight trends across categories, regions, and time.
- **Python**: Used for data preprocessing and detailed analysis.

## Outcomes
- Recommended promotional strategies for high-demand subcategories like Phones and Chairs.
- Proposed improvements in shipping methods, emphasizing potential for First Class and Same Day shipping.
- Leveraged seasonal insights to enhance inventory planning and maximize holiday sales.

- [**View Full Project Report**](https://1drv.ms/b/c/5c04ca5b7bc77dac/EaiiYPhuz7lNtBdKginZsQsBvBOnkwQFHFA98ZCqc2kblg?e=nhdO1K)

[**View Power BI File with Project Analysis**](https://1drv.ms/u/c/5c04ca5b7bc77dac/ETJ0ZrhmdKpNgKGs6oqHtyYBhujFfHlaFp6E4WTGLdXxFg?e=p6NZfw)
