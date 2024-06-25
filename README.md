# Sales-Analysis
Next Supermarket Sales Analysis

## Project Overview

This is a python and SQL project on an imaginary supermarket called NASA SUPERMARKET .. The analysis project objective is to analyze and glean insight into the sales performance of Na sa Supermarket for the year 2023. By analyzing various aspect of the sales data, we want to identify trends, make-data driven recommendation, and gain a deeper understanding of the supermarket’s (company) performance to answer critical questions and help the supermarket make data-driven decisions.

### Data Source 

Sales data: the primary data set used for this analysis is the “Sales_data.csv” file, containing  detail Information about each sale made by the supermarket for the period under review.

### Tools

  - Excel
  - Python
  - SQL server data analysis
  - power BI creating report

 ### Data cleaning and preparation 

 In the data preparation phase, I performed the following tasks :

   1. Data loading and inspecting
   2. Handling missing values-i replac## Data Analysis ed the missing values with zeros
   3. Data cleaning and formatting

 ###   Exploratory Data Analysis

 EDA provides the means to exploring the sales data to answer critical questions such as:
    -what is the overall sales trend?
    -which products are top sellers?
    -what are the peak sales period?
    
### Data Analysis

Some interesting codes/features worked with (use back tick)

***python

Sales_df = pd. read_csv(“c:/Users/Nasa/Data bank analysis/Dataframes/sales.csv

***

***python

Sales . columns = [i. lower () for I in sales .columns

***

```python

Sql = pd.read_sql(select * from sales)

Sql

```

```sql

Select * from sales;

```


###Result / findings

The following are the summaery of the analysis


1. The supermarket sales has been steadily increasing over the past year with a noticeable peak during the holiday seasons
	
3. Products category clothes, sockets, and phones are the best performing category in terms of sales and revenue generation

5.   customer segment with high life time value(LTV) should be targeted for marketing efforts

### Recommendations

Based on the just concluded analysis, we here by recommend the following actions:

   -	Invest in marketing  and promotions during peak sales seasons to maximize revenue
   -	Focus on expanding and promoting products categories cloths, sockets and phones
   -	Implement a customer segmentations  strategy to target high LTV customs effectively

### Limitations 


I have to remove all missing values and zeros from Tuesday to Friday columns because they would have impacted the accuracy of my result or conclusions from the analysis. There are still a few outliers even after the verifications but even then, we can still see that there is a positive correlation between daily sales and products.

### References









    

    

    
  
    

    
