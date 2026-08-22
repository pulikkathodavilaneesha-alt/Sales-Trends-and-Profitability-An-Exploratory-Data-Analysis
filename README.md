# Sales-Trends-and-Profitability-An-Exploratory-Data-Analysis

## Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of the Superstore dataset using Python.

The main purpose of the project is to understand sales and profitability patterns and identify how different factors such as **time, product categories, regions, customer segments, quantity, and discounts** contribute to overall business performance.

The analysis uses Python to clean, explore, visualize, and interpret the transactional data and convert it into meaningful business insights.



## Objectives

The key objectives of this project are:

* To understand the structure and characteristics of the Superstore dataset.
* To clean and prepare the data for analysis.
* To analyze the distribution of Sales, Quantity, and Profit.
* To examine the relationship between Sales and Profit.
* To analyze sales trends over time.
* To identify the product category with the highest sales.
* To compare profitability across different regions.
* To analyze sales performance across customer segments.
* To examine the relationship between Discount and Profit.
* To derive meaningful business insights and recommendations.



## Dataset

The project uses the **Superstore dataset** provided in Excel format.

The dataset contains **9,994 observations and 21 variables** covering information related to:

* Customer orders
* Order and shipping dates
* Customers
* Customer segments
* Products
* Product categories and sub-categories
* Geographical regions
* Sales
* Quantity
* Discounts
* Profit

The main variables used in the analysis include **Order Date, Segment, Region, Category, Sales, Quantity, Discount, and Profit**.



## Tools and Technologies

The following tools and Python libraries were used:

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Microsoft Excel**
* **GitHub**


## Analysis Methodology

The project follows an Exploratory Data Analysis approach.

### 1. Data Understanding

The dataset was initially examined to understand its dimensions, variables, data types, and overall structure.

The dataset contains 9,994 rows and 21 columns.

### 2. Data Cleaning

The dataset was checked for missing values and duplicate records.

No missing values were identified in the dataset. Duplicate records were also checked during the data preparation stage.

The Order Date variable was converted into an appropriate date format to enable time-series analysis.

### 3. Univariate Analysis

Univariate analysis was performed to understand the individual characteristics and distributions of:

* Sales
* Quantity
* Profit

Histograms and boxplots were used to identify distributions, variation, and extreme observations.

### 4. Bivariate Analysis

The relationship between Sales and Profit was analyzed using visual analysis and correlation.

The analysis showed a moderate positive relationship between Sales and Profit, with a correlation of approximately **0.479**.

### 5. Time-Series Analysis

Sales trends were analyzed using the Order Date variable.

Monthly and yearly sales were examined to identify changes in sales performance over time.

### 6. Multivariate Analysis

The relationships among Sales, Quantity, Profit, and Discount were examined using correlation analysis and visualizations.

The analysis indicated that Sales and Profit had the strongest relationship among the variables examined.

### 7. Category Analysis

Sales and profit were compared across the major product categories:

* Technology
* Furniture
* Office Supplies

### 8. Regional Analysis

Average profitability was compared across the four regions:

* West
* East
* South
* Central

### 9. Customer Segment Analysis

Sales performance was examined across:

* Consumer
* Corporate
* Home Office



## Key Findings

### Sales and Profit

The average sales value per transaction was approximately **229.86**, while the average profit was approximately **28.66**.

Sales showed a positively skewed distribution, meaning that a relatively small number of high-value transactions contributed significantly to total sales.

Profit included both positive and negative values, indicating that some transactions resulted in losses.

The correlation between Sales and Profit was approximately **0.479**, indicating a moderate positive relationship.



### Sales Trends

Sales performance varied over time.

The yearly analysis showed that **2014 recorded the highest annual sales**, at approximately **733,947.02**.

The highest monthly sales occurred in **November 2014**, with approximately **112,326.47** in sales.

These patterns indicate that sales performance varies across periods and that certain months may represent stronger demand periods.



### Product Category Performance

**Technology generated the highest total sales**, with approximately **836,154.03**.

Technology also generated the highest total profit, at approximately **145,454.95**.

Furniture generated substantial sales but comparatively low profit, with total profit of approximately **18,451.27**.

This indicates that high sales do not necessarily translate into high profitability.



### Regional Profitability

The **West region recorded the highest average profit**, at approximately **33.85** per transaction.

The Central region recorded the lowest average profit, at approximately **17.09**.

The difference in regional profitability indicates that business performance varies across geographical areas.

---

### Customer Segments

The **Consumer segment generated the highest sales**, contributing approximately **1.16 million** in sales.

The Corporate and Home Office segments contributed comparatively lower sales.

This indicates that Consumer customers are an important contributor to overall revenue.



### Discount and Profit

The analysis showed a negative relationship between Discount and Profit, with a correlation of approximately **-0.219**.

This suggests that higher discounts are generally associated with lower profitability.

However, correlation does not establish causation, so the result should be interpreted as an observed relationship rather than proof that discounts directly cause lower profit.


## Business Insights

The analysis provides several important business insights:

* Technology is the strongest product category in terms of both sales and profit.
* Furniture requires further investigation because it generates significant sales but relatively low profit.
* The West region demonstrates the strongest average profitability.
* The Central region has comparatively lower average profitability.
* Consumer customers are the largest contributors to sales.
* Higher sales are generally associated with higher profit.
* Excessive discounting may negatively affect profitability.
* Sales vary over time, creating opportunities for seasonal planning.
* Profitability should be considered alongside sales when evaluating business performance.



## Recommendations

Based on the findings, the following recommendations are proposed:

1. **Focus on the Technology category** because it performs strongly in both sales and profitability.

2. **Investigate Furniture profitability** by examining product-level pricing, discounts, costs, and sub-category performance.

3. **Review discount strategies** to ensure that discounts increase sales without significantly reducing profitability.

4. **Investigate the Central region** to identify the factors contributing to its relatively low average profit.

5. **Strengthen Consumer customer retention** because the Consumer segment generates the highest sales.

6. **Use historical sales trends** to support inventory planning, promotional campaigns, and resource allocation.

7. **Conduct product-level analysis** to identify products that generate high sales but low profit.

8. **Consider predictive analytics** in future projects to forecast sales and profitability.



## Visualizations

The project includes visualizations for:

* Sales distribution
* Profit distribution
* Quantity distribution
* Sales and Profit boxplots
* Sales versus Profit
* Monthly sales trends
* Yearly sales trends
* Correlation analysis
* Relationships among Sales, Quantity, and Profit
* Sales by product category
* Regional profitability
* Customer segment sales



## Project Structure

The repository is organized as follows:

**Superstore-Sales-EDA**

* `data/` — Contains the Superstore Excel dataset.
* `notebook/` — Contains the Jupyter Notebook with the complete Python analysis.
* `report/` — Contains the detailed project report.
* `README.md` — Provides an overview of the project, methodology, findings, and recommendations.



## How to Use This Project

To reproduce the analysis:

1. Download or clone this repository.
2. Install Python and the required libraries.
3. Open the Jupyter Notebook.
4. Ensure that the Superstore Excel dataset is available in the appropriate project folder.
5. Run the notebook cells sequentially.
6. Review the generated analysis and visualizations.


## Future Scope

This project can be extended beyond Exploratory Data Analysis.

Future work could include:

* Sales forecasting
* Profit prediction
* Regression analysis
* Customer segmentation
* RFM analysis
* Product-level profitability analysis
* Time-series forecasting
* Interactive dashboards using Power BI or Tableau
* Machine learning-based sales prediction
* Identification of high-risk loss-making transactions

## Conclusion

This project demonstrates how Python-based Exploratory Data Analysis can be used to transform retail transaction data into meaningful business insights.

The analysis highlights important patterns in sales, profitability, product categories, regions, customer segments, and discounts.

The findings indicate that **Technology is the strongest category, Consumer customers generate the highest sales, and the West region has the highest average profitability**. The analysis also highlights the importance of managing discounts and investigating areas where strong sales do not translate into strong profits.

Overall, the project provides a foundation for making data-driven decisions related to sales strategy, product management, pricing, customer management, and profitability improvement.

## Author

**Aneesha PulikkaThodavil**

**Project:** Superstore Sales and Profitability Analysis

**Focus Areas:** Python, Data Analysis, Exploratory Data Analysis, Data Visualization, Business Analytics
