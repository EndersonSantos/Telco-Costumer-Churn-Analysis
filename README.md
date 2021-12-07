# Telco Costumer Churn Analysis

## Ask
Telco Systems is a global leader in telecommunications, with over 40 years of experience in the design and development of high-performance network communications solutions. With its advanced software and hardware solutions, Telco Systems provides a revolutionary approach to the network edge for service providers, allowing them to offer the highest levels of service innovation to customers. Thus has a lot of available data from your customers that can be used to answer interesting questions that can lead to data driving decisions.
Some of the questions that we would like to answer is:

**What attributes are more correlated with the churn rate?** <br/>
**Which kind of retention programs can we develop focused to diminished the churn rate?**

## Prepare 
The problem we want to attach is clear, so now let's move on to see what data we need to solve this problem. We need customer-related data. Fortunately, we can find this in the Kaggle datasets.
The data were collected from [IBM Samples Data Sets] (https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113) and the latest update was made on 02/23/2018. And it's under the community-guaranteed kaggle license. Data files © Original Authors.
We will continue our analysis on this dataset, of course it would be better to have a more recent dataset on hand.
This data contains information about:
- Customers that left within the last month - *churn* <br/>
- Services that each customer has signed up for – *phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies* <br/>
- Customer account information – *how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges* <br/>
- Demographic info about customers – *gender, age range, and if they have partners and dependents.* <br/>
<p>This data will allow us to answer our questions <p/>

## Process
The data is already cleaned so we not going to do anything in this matter although is probably one of the most important steps. So we going to focus on our exploratory data analysis, visualizations to propel data-driven decisions.
The tools that we going to use is Python and its main libraries like:
- **Pandas: For Exploratory Data Analysis.**<br/>
- **Jupyter Note Book: For data Handling.**<br/> 

## Analyse 
+ We saw that there's a high correlation between contract type and the number of churn. Most people we contract type of month to month indeed churn and most of people with contracts with one or more years churn way less.
+ We saw an decrease of a churn rate as long the tenure rate increase

We were able to train models that were able to perform relatively well but not as we liked. However, something interesting was the fact that the model corroborates our analysis using the type of contract as the strongest attribute to predict whether or not a customer will churn.


## Share 
![telco](https://user-images.githubusercontent.com/90560755/142908206-8c57973a-b4a5-47e9-bcbb-7e4d7b6ec093.jpg)
![tenure_rate](https://user-images.githubusercontent.com/90560755/142908558-04015f49-6fd8-4fd9-baa0-4705d33d7e76.png)
![contract](https://user-images.githubusercontent.com/90560755/142908655-2cfb8eee-7e2a-451c-954a-d80a244ce9c5.png)

## Act
+ Reduction bonus after a one year contract or a two year contract where we bring down those charges again to make sure that customer doesn't churn
+ Coupon program after a one year contract or a two year contract
+ Create surveys to understand why the custumer that churn made that decision.

