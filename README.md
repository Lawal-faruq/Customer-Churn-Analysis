# Customer Churn Analysis

**Introduction**

In the ever-evolving realm of business, understanding and mitigating customer churn is not just a strategy; it's an art. This project unveils a powerful symphony of insights, meticulously crafted to guide you through the nuances of customer behavior. Dive into the rich tapestry of data, where tenures, activity levels, card types, credit scores, age demographics, and geographical nuances come together to compose a narrative of customer loyalty. As you embark on this journey, let the dashboard be your compass, unraveling the intricacies and revealing opportunities to fine-tune your retention strategies. Join us in orchestrating a melody of customer loyalty that resonates long after the last chord.

**Data Preparation**

The dataset was downloaded from Kaggle. I took a glance at the dataset using excel to do a quick review of the data I would be working with. This is just to know how many rows and columns this dataset has, what kind of data are in each column, and whether there are any null values that would help with my analysis. The snapshot of the dataset in excel is shown below:

![Image1](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/4c8bde22-af67-42ec-84c7-7c6825ce7d94)

The data consist of 18 columns and 10000 rows, the columns are: RowNumber, CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure,Balance,NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary, Exited, Complain, Satisfaction_Score, Card_Type and Point_Earned.

**Data Processing**

After taking a glance at the data, it is now time to import the dataset into the tool that I will be using for this analysis, which is Power Bi, so that I can do some transformation in power query editor. When the data was load into power query the following was carried out:

1.)	The column names were on the first row, so I need to make the first row as headers.

![Image2](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/08b603e1-0eba-4244-8ffe-882611600a64)

![image3](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/8cebbde9-0cbf-4984-9b40-23056070ce5b)

So, after making the first row as header it is discovered that the datatypes or not correct, so I need to change each columns to the appropriate datatypes. 

2.)	I changed the columns to their correct datatype.

![image4](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/6ea491bd-6d7b-4712-ae56-e4c170d9cc84)

3.)	So, for the analysis, I will be needing to create additional columns to aid my analysis, the columns are shown below:

![image5](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/70816dff-ea09-4a07-b726-c970f5702cb9)

**Data Analysis**

After doing all the necessary processing, the next thing is to close and apply my steps, then move into the analysis process proper. The next thing is to write DAX formula for my analysis.

![image6](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/2166c3c8-c17a-4beb-bc17-1c12ea265733)

So, after everything is set and ready to go, I can now proceed to gain the following insight from the data and provide recommendations for the stakeholders. The insights are as follows:

For Customer Demographics 

•	What is the customer churned rate?
•	What is the churn rate for male customers?
•	What is the churn rate for female customers?
•	What is the number of the total churned customer?
•	What is the churned rate by country?
•	What is the churned rate by age groups?

For Customer Churned Analysis

•	What is the churned rate by credit score?
•	What is the churned rate by card type?
•	What is the churned rate by tenure?
•	What is the churned rate by active/inactive customers?

So the insights and recommendation are shown in the dashboard below:

![image7](https://github.com/Lawal-faruq/Customer-Churn-Analysis/assets/107109677/3fc95b96-e5ad-4e7a-8446-8ed65c0c174a)

