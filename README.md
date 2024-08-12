# Retail-Sales-Analysis

# INTRODUCTION

Hello and welcome. In today’s presentation, I am excited to take you through this company’s retail sales dataset.
I am really excited to be doing this presentation as it has given me the opportunity to dive into, and gain insightful information about this store’s performance.

# Process

I am excited to state that, I took the necessary process in ensuring that this project has passed through the necessary steps and procedure before finally arriving at the final result.
Two common data cleaning tasks are performed on the dataset. The first involves identifying NULL or missing values, while the second entails checking for any duplicated records. Power BI and Excel, both offers built-in features for both of these tasks. 
Also I did use a little bit of dax formula in this project to group the various ages into “young adults, Early middle-aged, Late middle-aged and Old”. Kindly find the formula below;
Age_Group = IF(retail_sales_dataset[Age]<22,"Young Adults",IF(retail_sales_dataset[Age]>60,"Old",IF(retail_sales_dataset[Age]>21 && retail_sales_dataset[Age]<34,"Early Middle-aged","Late Middle-aged")))


# OBJECTIVES

There are two main tasks identified when carrying out this project
1. Efficiently clean, transform, and analyze the dataset
2. Uncover valuable and unexpected hidden insights from the data, answering business questions and providing strategic recommendations


# BUSINESS QUESTIONS / KPIs

1. How does customer age and gender influence their purchasing behavior?
2. Are there discernible patterns in sales across different time periods?
3. Which product categories hold the highest appeal among customers?
4. What are the relationships between age, spending, and product preferences?
5. Are there distinct purchasing behaviors based on the number of items bought per   transaction?
6. What insights can be gleaned from the distribution of product prices within each category?


# INSIGHTS

1. between the age bracket of 35 and 60 years are the highest contributing customers with the males in this bracket contributing a little more than females in same bracket.
2. People between the ages of above 60 years are our least contributing group with a significance difference between the late middle-aged group and old.
3. There is a fair increase in sales from the month of January to February with sales declining fairly in march.
4. However, there is also a significant increase in sales in May standing at 259 sales and October at 252 sales followed by August at 227 sales with sales being at it’s lowest during the months of September at 170 sales and July at 176.
5. There is also a stable small increase in sales from November to December.
6. This tells management that, demand is at its peak during the months of  May, October and August and management must capitalize on these time periods.
7. Also, the late middle-aged being the highest contributing group tend to split their spending amongst all three product categories almost fairly. There really is no significant difference between their spending habit for all three product categories.
8. Same can perhaps be said for the “old” age group being the least revenue contributing group.
9. However, it’s a different case for the Early middle-aged and Young adults group. In the case of Young Adults, we can see they prefer to spend more on Electronics and beauty than on clothing by a fairly significant amount.
10. In the case of Early middle-aged, we see that they rather prefer to spend a significant amount on Clothing than the remaining two product preferences.
11. the total price within the three product categories from the store with the total price for electronics being $62,210, clothing being $61,175 and Beauty being
$56,505.
12. However, we can also see that even though the price for electronics is the highest, its still the most demanded product on average by customers across all age groups, with a total revenue of $156,905. However beauty being the lowest priced product is also the least demanded item on average across the various age groups with a total revenue of $143,515.
13. I would agree that that pricing for these products are about okay, except a slight increase in electronic products would be great looking at the number of sales its making.
    























