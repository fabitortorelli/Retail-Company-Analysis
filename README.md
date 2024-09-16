# Retail Company Analysis

## Overview
This project provides an Exploratory Data Analysis (EDA) on a retail dataset, followed by answers to key business questions and the development of an interactive dashboard. The goal is to uncover meaningful insights from sales data, assist in business decision-making, and visualize the findings through a dynamic dashboard.

The dataset used in this project is provided by the course **"Fundamentos de Linguagem Python Para Análise de Dados e Data Science"** from [Data Science Academy](https://www.datascienceacademy.com.br/path-player?courseid=fundamentos-de-linguagem-python-para-analise-de-dados-e-data-science&unit=642bac12d1798ca10e00c703Unit)

## Project Structure
**notebooks/:** Jupyter notebooks used for the exploratory analysis and responding to business questions
**dashboard/:** The code and configuration for the dashboard created in Power BI
**report/:** The presentation slides that outline findings from the data analysis, business questions, and dashboard overview
**README.md:** Project overview and instructions (this file)

## Key Objectives

**Exploratory Data Analysis (EDA):**

- Perform a thorough EDA to understand the structure of the dataset
- Identify trends, patterns, and outliers in the data
- Analyze sales, customer behavior, and product performance across different segments, regions, and time periods

**Business Questions Answered:**

- Which City has the Highest Sales Value for Products in the 'Office Supplies' Category?
- What is the Total Sales by Order Date?
- What is the Total Sales by State?
- What are the Top 10 Cities with the Highest Total Sales?
- Which Segment Had the Highest Total Sales?
- What is the Total Sales by Segment and by Year?
- What is the Average Sales by Segment, by Year, and by Month?
- How many Sales would receive a 15% discount based on the following rule?
  - If the Sales Value is greater than 1000, it receives a 15% discount
  - If the Sales Value is less than 1000, it receives a 10% discount
- Assume the company decides to grant a 15% discount from the previous item. What would be the average Sales Value before and after the discount?
- What is the Total Sales by Category and SubCategory, considering Only the Top 12 SubCategories?

**Dashboard:**

- Create an interactive dashboard to visualize key metrics, including total sales, customer distribution, and product performance
- Allow filtering by year, segment, and state to enable dynamic data exploration
- Present insights in an easily digestible format for stakeholders

### Data
The dataset used in this project includes the following features:

- **Order Date:** The date of each sale
- **Sales Value:** The total amount of sales per order
- **Customer ID:** Unique identifier for each customer
- **Segment:** The customer segment (e.g., Consumer, Corporate, Home Office)
- **Category:** Product categories such as Technology, Office Supplies, and Furniture
- **Sub category:** Product subcategories like Binders, Phones, Tables, etc
- **City:** The city where the sale occurred
- **State:** The state where the sale occurred
- **Country:** The country where the sale occurred (here we have only EUA)
- **Order ID:** Unique identifier for each order
- **Product ID:** Unique identifier for each product

## Tools and Technologies

- Python: Used for data cleaning, analysis, and visualization
- Pandas: For data manipulation
- Matplotlib & Seaborn: For creating graphs and charts during EDA
- Power BI: For building the interactive dashboard
- Jupyter Notebook: To document and run the analysis


## Insights

Some key insights uncovered during the analysis:

- Sales have increased steadily over the years, with the highest sales recorded in 2018
- The Technology category contributes nearly 37% of total sales
- New York City and California lead in total sales by city and state, respectively
- The Consumer segment consistently records the highest sales
- The third quarter shows the highest sales, likely driven by events like Black Friday and Christmas

## Future Work
To further improve the analysis, future steps may include:

- Profit margin analysis by product and region
- Customer retention and lifetime value analysis
- Seasonal trends and purchase frequency analysis

## Contributing
Contributions are welcome! If you have additional data, corrections, or suggestions, free to contact me. Please ensure that your contributions align with the goals of this project and maintain a respectful tone.

