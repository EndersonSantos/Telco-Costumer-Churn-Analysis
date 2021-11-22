# Telco Costumer Churn Predictions

## Ask
Telco Systems is a global leader in telecommunications, with over 40 years of experience in the design and development of high-performance network communications solutions. With its advanced software and hardware solutions, Telco Systems provides a revolutionary approach to the network edge for service providers, allowing them to offer the highest levels of service innovation to customers. Thus has a lot of available data from your costumers that can be used to answer interesting questions that cand lead to data driving decisions.
Some of the question that we would like to answers is:

**Based on historical data can we predict churn?** <br/>
**Which kind of retentions programns can we develop focused on diminished the churn rate?**

## Prepare 
The problem that we want to attach is clear so now lets move on for what data do we need in order to solve this problem. And, it's obvious that we need data related to the customers. Luckly we can find this on Kaggle data sets.
The data was collected from [IBM Samples Data Sets](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113) and the last updated was made on 23-02-2018. And, is under the licence guaranteed by kaggle comunity Data files © Original Authors.
We going to proceed our analysis and training modeling on this data set of course would be better to have on hands a more recent dataset.
This data contains information about:
- Customers that left within the last month - *churn* <br/>
- Services that each customer has signed up for – *phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies* <br/>
- Customer account information – *how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges* <br/>
- Demographic info about customers – *gender, age range, and if they have partners and dependents.* <br/>
<p>This data will allow us to answer our questions <p/>

## Process
The data is already cleaned so we not going to do nothing in this matters although is probaly one of the most important step. So we going to focus on our exploratory data analysis, vizualizations and training modeling to propel data driven decisions.
The tools that we going to use is Python and its main libraries like:
- **Pandas: For Exploratory Data Analysis.**<br/>
- **Dash: For creating a dashboard to show the means findings from the previous step.**<br/>
- **Jupyter Note Book: For data Handling.**<br/> 
- **Skit-Learn - For training different models and avaluate its performances.** 

## Analyse 
+ We saw that there's a high correlation between contract type and the number of churn. Most people we contract type of month to month indeed churn and most of people with contracts with one or more years churn way less.
+ We saw an decrease of a churn rate as long the tenure rate increase

## Share 
![telco](https://user-images.githubusercontent.com/90560755/142908206-8c57973a-b4a5-47e9-bcbb-7e4d7b6ec093.jpg)
![tenure_rate](https://user-images.githubusercontent.com/90560755/142908558-04015f49-6fd8-4fd9-baa0-4705d33d7e76.png)
![contract](https://user-images.githubusercontent.com/90560755/142908655-2cfb8eee-7e2a-451c-954a-d80a244ce9c5.png)

## Act
+ Reduction bonus after a one year contract or a two year contract where we bring down those charges again to make sure that customer doesn't churn
+ Coupon program after a one year contract or a two year contract

