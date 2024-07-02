# Gala-Groceries-Analysis
Task Info by [Congnizant](https://www.theforage.com/virtual-experience/5N2ygyhzMWjKQmgCK/cognizant/artificial-intelligence-rtbq/exploratory-data-analysis) virtual experience on Data Science. 

## About Gala Groceries
Gala Groceries is a technology-led grocery store chain based in the USA. They rely heavily on new technologies, such as IoT to give them a competitive edge over other grocery stores.  

They pride themselves on providing the best quality, fresh produce from locally sourced suppliers. However, this comes with many challenges to consistently deliver on this objective year-round.  

Gala Groceries approached Cognizant to help them with a supply chain issue. Groceries are highly perishable items. If you overstock, you are wasting money on excessive storage and waste, but if you understock, then you risk losing customers. They want to know how to better stock the items that they sell.  

This is a high-level business problem and will require you to dive into the data in order to formulate some questions and recommendations to the client about what else we need in order to answer that question.  

## Step 1: Ask 

Business Goal: They want to know how to stock better the items that they sell.  

### Guiding Question: 
1. What is the problem you are trying to solve?  
The main objective is to determine how to stock the items better that they want to sell. 

## Step 1: Prepare

This is public data, anyone can download it through the below link. 

### Guiding Questions 
1. Where is your data located?
The data is located [here](https://cdn.theforage.com/vinternships/companyassets/e6nrxEAa6MHFh3Jmw/DCGoJxzfdJHirTYGe/1652216241761/sample_sales_data.csv) under TheForage Licensed.

2. How is the data organized?
The columns are organized in following format: transaction_id, timestamp, product_id, category, customer_type, unit_price,	quantity,	total,	payment_type.

3. Are there issues with bias or credibility in this data? Does your data ROCCC.
here were no potential bias or credibility as data was reputed by the organization itself, which skewed towards positive results. The reputed data is well organized and cleaned before further processing and no sampling is considered while processing.  
This Reputed data is ROCCC which stands for data is

Reliable,
Original,
Comprehensive,
Current, and
Cited.

## Step 2: Exploration & Visualization
Performing Descriptive statistics to determine how data is distributed across the dataset. such as mean, median, std dvn, variance, Quantile, min, and max.  

For visualisation, I encounter with seaborn library in DataScience. 

## Summary


We have completed an initial exploratory data analysis on the sample of data provided. We should now have a solid understanding of the data. 

The client wants to know

```
"How to better stock the items that they sell"
```

From this dataset, it is impossible to answer that question. In order to make the next step on this project with the client, it is clear that:

- We need more rows of data. The current sample is only from 1 store and 1 week worth of data
- We need to frame the specific problem statement that we want to solve. The current business problem is too broad, we should narrow down the focus in order to deliver a valuable end product
- We need more features. Based on the problem statement that we move forward with, we need more columns (features) that may help us to understand the outcome that we're solving for
