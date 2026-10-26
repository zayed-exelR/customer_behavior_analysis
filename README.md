# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior to understand purchasing patterns, customer segments, product performance, discount usage, and subscription trends. The goal is to turn raw shopping data into meaningful business insights that can support data-driven decision-making.

## Objectives

- Analyze customer purchasing patterns and spending behavior.
- Compare purchasing behavior across customer groups.
- Evaluate product categories, ratings, discounts, and shipping preferences.
- Examine subscription status and customer loyalty.
- Build an interactive Power BI dashboard to communicate key findings.

## Tools & Technologies

- **Python:** Data cleaning, preprocessing, and analysis using Pandas.
- **MySQL:** SQL queries, aggregations, joins, subqueries, and window functions.
- **Power BI:** Dashboard creation and data visualization.
- **Jupyter Notebook:** Python analysis and documentation.

## Project Workflow

1. **Data Cleaning:** Checked for missing values and duplicate records, handled missing review ratings using category-level median values, and prepared additional analysis columns.
2. **Data Preparation:** Created age-group and purchase-frequency analysis fields.
3. **SQL Analysis:** Used MySQL to investigate revenue, customer segments, product ratings, discounts, shipping types, and subscription behavior.
4. **Dashboard Development:** Created a Power BI dashboard with key performance indicators and visualizations for customer and product analysis.
5. **Reporting:** Prepared a project report and presentation summarizing the analysis.

## Key Business Questions

- How does purchase amount vary by gender?
- Which products have the highest average review ratings?
- How do spending patterns compare between Standard and Express shipping?
- How do subscribers and non-subscribers compare?
- Which products have higher discount usage?
- How can customers be segmented by previous purchase history?
- Which are the top three products by review rating within each category?
- How does revenue vary across age groups?

## Key Findings

- The dataset contains **3,900 records**.
- The average purchase amount in the dashboard is approximately **59.76** in the dataset's recorded currency.
- The average review rating is approximately **3.75**.
- Clothing has the highest purchase amount among the categories shown in the dashboard.
- Subscribers represent approximately **27%** of records, while non-subscribers represent approximately **73%**.
- Average purchase amounts are similar for subscribers and non-subscribers in this dataset.

These findings describe the analyzed dataset and should not automatically be interpreted as evidence of broader customer behavior or causation.

## Project Files

This repository includes:

- Python notebook for data cleaning and analysis.
- MySQL SQL script containing analytical queries.
- Power BI dashboard file (`.pbix`).
- PDF project report.
- PowerPoint project presentation.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- SQL querying and business analysis
- Customer segmentation
- Data visualization and dashboard development
- Communicating findings through reports and presentations
  
## Dashboard Preview
dashboard.png

## Conclusion

This project demonstrates an end-to-end data analysis workflow, from preparing shopping data and querying it with MySQL to visualizing results in Power BI and presenting business findings.

**Tools used:** Python | Pandas | MySQL | Power BI | Jupyter Notebook
