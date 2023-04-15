#KPM TELECOM Q3 CHURN ANALYSIS
## CHURN ANALYSIS REPORT 
![image](https://user-images.githubusercontent.com/92734328/232178924-33c621db-b20b-4314-9c93-96fb23be4d3e.png)

The KPM Telcom dataset is a fictional dataset provided by IBM as a practice dataset among other dataset. I took up the challenge to discover what mystery about churning this dataset contains. 

The link to the raw dataset is available on [Kaggle](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset).
The Excel workbook with report is available on [Google sheet](https://docs.google.com/spreadsheets/d/1ow0Ij6fxo2fdlFvpOqWH9WfTMndRiuEy/edit?usp=share_link&ouid=113315458040633601808&rtpof=true&sd=true).

 The business objectives are :
1. Analyze the rate at which customer leave the company.
2. Investigate the impact of customer churn in the industry as a whole.
3. Identify which customers are leaving.
4. Identify root cause of customer churning.
5. Which group of customers have the highest churn rate?.

 As required of every data analytic process, I dived into the topic as I was relatively new to it. Customer churn aka customer attrition is the number of paying customer who fail to become repeat customers. Customer churn is also the measurement of the number of subscription customers who have cancelled their subscription over a set period of time.
 
After I had studied about the topic, I studied the data set that was provided. This usually provide insights to observing patterns, trends, errors, outliers, data structure, data formats et cetera in preparation for the cleaning process. However the data provided is completely clean.

The churn dataset initially has 7043 rows containing values and 33 columns. The dataset is the churn material available for the third quarter of a year in California.

Below are steps i took in analyzing my data for insights.
1. Duplicates were removed but none were found.
2. I calculated number of customers retained and churn which turned out to be 5168 and 1869 respectively.
3. I calculated churn rate and made a donut chart to visualize churn rate to retention in the given quarter.
4. Since 27% of the customers churned, it is worth investigating the source.
5. I categorized customers churning into categories for churning. I sorted the categories based on
 the number of customers(complaint)
6. Since the top 9 reasons account for exactly 69.9% for churning. I visualized the discovery using a horizontal column chart
 along with figures
7. I investigated the relationship between customer churning and their subscription type. From the 1869 customers churning,
 1655 had a Month-to-Month contract, 48 two year contract and 166 had one year subscription
 5168 customers were retained, 2219 customers have a month-to-month subscription, 1645 have two years subscription and 1304 have
 a year subscription.
8. I made a visualization to support my claim - Customers with monthly subscription tend to churn.
9. To understand how the churn affected the business, it is important to find out how much was lost in revenue.
10. I calculated the total revenue generated that quarter, revenue from churned subscribers and Revenue from retained subscribers.
11. I created a new spreadsheet, named it Report and put together all my visualizations.

If you enjoyed my analysis, follow me on [Twitter](https://twitter.com/Michael61712605) and [Linkedin](https://www.linkedin.com/in/michael-olagoke/)
