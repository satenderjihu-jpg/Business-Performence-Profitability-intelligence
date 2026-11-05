# Business-Performence-Profitability-intelligence

**📌Project Overview**
An E-commerce company is experiencing declining profit margin despite consistent revenue growth
The management wants to identify the key factors affecting profitability including excessive discounts, rising operational costs, product returns, customer segment and sales performance

**👉 Data Size **
The total overview of the data is almost 50,000 rows and columns almost 30...

| Tool                       | Purpose                                                                |
| -------------------------- | ---------------------------------------------------------------------- |
| Python                     | Initial data cleaning and exploratory data analysis                    |
| Pandas                     | Data cleaning, data manipulation, joining, and analysis                |
| NumPy                      | Numerical operations and data analysis                                 |
| Matplotlib                 | Data visualization                                                     |
| Seaborn                    | Exploratory data visualizations                                        |
| Jupyter Notebook           | Executing and documenting Python analysis                              |
| Power BI                   | Interactive dashboard development                                      |
| DAX                        | KPIs calculations and measures                                         |

## 🔄 Project Workflow

### Phase 1: Data Cleaning Using Python

The project started with a raw customer churn dataset.

Python was used to inspect the dataset, identify data quality issues, and prepare the data for analysis.

Key activities included:

* Inspecting the dataset structure and column types.
* Checking for missing values.
* Checking for duplicate customer records.
* Identifying data quality issues.
* Cleaning and preparing the dataset for subsequent analysis.

### Phase 2: EDA Using Python

Exploratory data analysis started after clean the data 

Key activities included:

* Identified the year wise total profit margin
* checked the year-wise revenue
* After that found the year-wise discount pct, shipping rate, COGS
* Found year-wise total Quantity of orders
* Got the root cause behind the profit margin declining

### Phase 3: Power BI Dashboard

Created an interactive dashboard using cleaned data 

Key activities included:

* Created total 6 KPIs related to data
* identified year-wise declining profit margin and Revenue(2023-2025)
* created a chart to identify category-wise profit margin year by year
* Created 4 Slicers (city , region, payment_method, sales channel)

### Phase 4: Business Recommendations: 

Suggested 4 Business recommendation after findings from EDA and power BI KPIs , charts

Power BI dashboard overview

<img width="796" height="451" alt="image" src="https://github.com/user-attachments/assets/69cc26e0-1d66-4359-bfbe-e02e97d7722d" />

**Insights**

**1. Year to year revenue & Profit margin declining   **  
 Net revenue 2023 to 2025 only 4.4% decresed (39.04M->37.31M) that means sales almost stable but profit   Margin ~73% decresed (3.65M->0.98M) 9.4% to 2.6% that means revenue decreased 3% but profit 61%  

**2. Year to year cogs, discount_amount, shipping_cost,marketing_cost, return_cost,refund_amount**
  Discount spend 2023 to 2025 ~49% increased(4.97M->7.40M)while revenue decreased ~4.4% that is the       biggest reason of decreasing profit margin.

**3. Category-wise profit margin**
  Electronic has the highest discount amount as compare to other category (+1.17M) +58% and also electronic have genarated top revenue

**4.order values year by year**
  After increasing discount volume did not affected  

**Business Recommendations**

# Recommendation:-
 1. **Apply a company-wide discount cap of 10-12%** The discount rate rose from 10.3% to 15.1% between 2023 and 2025, while order quantity stayed flat at about 28.3k units the extra discount did not generate extra sales.
 2. **Track the volume impact of over every promotion.** Measure order volume before and after each campaign, and stop discounts that do not lift orders.
 3. **Shift from blanket discounts to targeted ones** Offer discounts only on show-moving products or clearance items, where they can actually increase volume
 4. **Review shipping and marketing costs** Shipping(+14%) and marketing (+11%) grew faster then revenue (-4%), contributing to the decline in profit
