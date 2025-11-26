# Exploratory-Data-Analysis-EDA-on-Sales-Data
Finding Sales Insights Using Python 

Scenario:
  -  GlobalMart is a large retail chain that wants to understand its sales performance across various areas of the business
  -  You've just joined the data analysis team at GlobalMart, a large international retail chain. The company wants to understand its sales performance across different regions, product categories, and time periods. Your task is to perform an exploratory data analysis on the company's sales data to uncover insights that can drive business decisions.

Mission/Objective:
  - Conduct an exploratory data analysis on GlobalMart's sales data using Python. You'll need to import the data, clean it, perform basic analyses, and create visualizations to communicate your findings.

The Data Set:
  - I'll be working with the "Global Superstore Dataset". This dataset contains information about sales, profits, product categories, customer segments, and geographical data.

Tools
  -  Python 3.x
  - Jupyter Notebook
  - Libraries: pandas, numpy, matplotlib, seaborn

### Q1 Which product categories are the most profitable ?
- The comapny sells products in three categories: Technology, Furniture and Office Supplies.
- Technology shows the biggest variability in sales, indicated by the longest vertical line, whereas Furniture has the second highest
  and office supplies shows smallest variability in sales.
- In terms of performance Technlogy, Furniture and Office supplies sales approx 400 units, around 375 units and about 225 units     respectively.
-  Martket Focus:-
    - According to analysis the Global Mart's Strongest market is in Technology products.
- Potential Strategies:-
    - The company might want to investigate why Technology sales are more variable and if there are seasonal or oher factors affecting this.
    - Also, might be an opportunity to boost office Supplies sales.

### Q2 Are there any noticeable trends in sales over time ?
- The GlobalMart's overall upward trend in sales from 2012 to 2016, with sales peak becoming higher over time. The most noticeable feature is drametic spike in sales around early 2015, reaching about 12,000 units.
- There appear to be some recurring peaks, possibly indicating seasonal trends, through they're not consistent across all years.
- From 2012 to mid 2014, sales were relatively stable, mostly below 2,000 units per month, with only minor fluctuations.
- After the major spike in 2015, sales have remained higher and more volatile than in eralier yeras frequently exceeding 4,000 units.
- Potential Outlier:
    - The extreme peak in eraly 2015 could be due to a special event, promotion or data anomaly, given how dramatically it differs from other        periods.
### Q3 How do sales and profit vary by region ?
- Sales vary significantly by region, with each area showing distinct product category strengths.
- Office Supplies dominate in the Eastern and Central US, indicating strong demand for workplace essentials in these regions.
- Western US excels in Furniture and Technology sales, reaching 6,000 units each suggesting a robust market for both home and office equipment.
- Central US leads overall with the highest sales of 11,231 units in the office supplies category.
- Furniture sales are weakest in the Central and Southern US, presenting potential growth opportunities in these markets.

### Q4 Is there a correlation between discount and profit ?
- The weak negative correlation between discount and prfits implies that offering discounts might be slightly reducing the company profitability. However, the relationship is not strong enough to conclude that discount are significantly harming profits.
- Possible Implications:
    - The discounting stratgy may need review, but it is not causing major harm to profits.
    - There might be other factors influencing the relationship between discounts and profits.
    - The comapny might want to investigate if there are specific products or customer segments where discount are more or less effective.
    - Total Discount: $ 29.95
    - Total Profit: $ 12,063.97
    - Discount profit correlation: -0.16 (A value indiacates a waek correlation between discount and profits)
### Key Points for seasonality trend:-
- Overall upward sales trend from 2012-2013
- Major sales spike in early 2015
- Increased sales volatility after mid-2014
- Consistent seasonal patterns thorughout the years.
- Residuals show some outliers, Particularly a large positive deviation in early 2015.

For More coding and graph details in EDA of Global SuperStore Project-checkpoint.ipynb 
