# Online-Retail-Store-Data Mining
A. Introduction/Problem Statement

The senior management wants to understand how their business is performing and what areas are the key strengths of the company. They are also focused on identifying opportunities that would lead to growth and generate more revenue in the future.

B. Data Source: Available from: Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17).
https://archive.ics.uci.edu/ml/citation_policy.html

C. Software used:
a.	Excel 
b.	PowerBI

D. Data Analysis Process

1. Problem statement and understanding of need- 
Gathered requirements, and understood metrics/measures required.

2. Data Inspection & Cleaning
i.	Checked for validity (I.e price should not be less than or equal to zero and quantity less than zero)
Removed data that fell into this set

ii.	Checked for completeness (missing data)- removed null rows
-Customer ID and Description had empty rolls
-In the country column, some revenue where unspecified (not allocated to a country), there is not enough information to delete or say it is irrelevant. Would need to elicit more information in this regard.
iii.	Data type conversation for validity- 
Quantity (should be whole numbers not text), country (categorized as country- Geo), customer ID (from number to text)
iv.	Checked for uniformity in format and measurements- Good
v.	Enriching, create new column- Revenue

4.	Data Integration – using Power BI- Power query

5.	Extraction – ETL

6.	Descriptive Statistics

7.	Data Analysis and Visualisation 

8.	Dashboard reporting to generate insights


E.	Insights the CEO would be interested in:
i.	Which region is generating the highest revenue, and which region is generating the lowest?
ii.	What is the monthly trend of revenue, which months have faced the biggest increase/decrease?
iii.	Which months generated the most revenue? Is there a seasonality in sales?
iv.	Who are the top customers and how much do they contribute to the total revenue? Is the business dependent on these customers or is the customer base diversified?


F.	Insights the CMO would be interested in:
i.	What is the percentage of customers who are repeating their orders? Are they ordering the same products or different?
ii.	For the repeat customers, how long does it take for them to place the next order after being delivered the previous one?
iii.	What revenue is being generated from the customers who have ordered more than once?
iv.	Who are the customers that have repeated the most? How much are they contributing to revenue?

G. Power Point slides prepared

H. Presentation made to CEO
