# Overview

This project develops a Power BI dashboard to enable monitoring the performance of a hypothetical E-commerce business. The dashboard delivers insights on the overall business performance, regional performance, or performance of a specific product relative to KPIs while enabling to analyze individual customers for marketing purposes. It is worth mentioning that, in addition to the visualizations, all the data preparation and modeling in this case is also done in Power BI.


# Data Preparation
The data is imported in the CSV format. Data preprocessing, such as proper text formatting, date and time formatting, validating variable types, etc. are done in Power BI. Since the tables are normalized, the relationships between different entities are defined considering cardinality and filter flow to avoid confusion. The entity-relationship diagram is as follows:

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/0.DataModel_ERD.jpg)

Having the data model created, calculated fields required are defined using DAX. 


# Executive View

This page of the dashboard is targeted towards executives who want to have a quick overview of business performance. Therefore, it provides information about the total revenue, profit, number of orders and return rate as the main KPIs. In addition, a trend line lets the top managers know if the monthly revenue is within the acceptable threshold along with monthly revenue, profit, and returns compared to the previous month that are included in the report to enable them to quickly detect any performance decrease. The following is a snapshot of this view:

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/1.ExecutiveViewSnapshot.jpg)

This view also provides information about top products and product categories. The information can also be filtered based on products.

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/1.Filters_Products.jpg)

A filter pane is also designed to enable managers to filter the results based on region or year.

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/1.Filters_ExecutiveView.jpg)


# Regional View

Since the business operates in different locations, this view provides the end users with high-level information about the countries and the total number of orders in each market. The information can also be filtered based on the region.

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/2.RegionalViewSnapshot.jpg)


# Product Detail

This view provides more detailed information about the performance of a specific product by allowing the user to compare the monthly number of orders, revenue, and profit for a specific product with the pre-defined KPIs. It also delivers information about the trend for product metrics including the number of orders, revenue, profit, returns, and return rate, along with the expected impact of a price adjustment. 

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/3.ProductViewSnapshot.jpg)


# Customer Detail

This view communicates overall customer KPIs including the total number of customers and revenue per customer along with the related trend line to enable analyzing the performance over a desired period of time. Also, this report provides information about customer segments defined by occupation and income level. Last but not least, information about the top customers is also included in this view, which enables identifying the most loyal customers or those who generate higher revenues for the company for marketing purposes. 

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/4.CustomersViewSnapshot.jpg)

This view can also be filtered to show information for specific customers. 

![alt text](https://github.com/Ramanvkl/BusinessIntelligence/blob/main/4.Filters_CustomersView.jpg)
