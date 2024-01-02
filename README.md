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

