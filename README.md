# Analyzing Shopping Trends: Insights from Istanbul Malls 2021- March 2023

## Business Understanding
Shopping is the activity of buying goods or services for personal consumption or specific needs. This data is from 10 different shopping malls between 2021, 2022, and up to the third month of 2023 in Istanbul. This case has some business questions using the data:

1. How many products are sold each year?
2. What products are most purchased by customers?
3. How much money do customers spend each month per year?
4. What payment methods do customers use most often?
5. Is there a difference between the amount spent based on gender?

## Data Understanding
 Source : https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset

 This data consists of 99,457 rows and 10 columns with the following attribute information: 
 
 **Invoice_no** : Invoice number, with a combination of the letter 'I' and a 6-digit integer uniquely assigned for each transaction.
 
 **Customer_id** : Customer number, with a combination of the letter 'C' and a 6-digit integer uniquely assigned for each transaction.
 
 **Gender** : Customer's gender.
 
 **Age** : Customer's age in integer.
 
 **Category** : Category of the product purchased.
 
 **Quantity** : Quantity of each product (item) per transaction. Numeric.
 
 **Price** : Unit price. Price of the product per unit in Turkish Lira.
 
 **Payment_method** : Payment method (cash, credit card, or debit card) used for the transaction.
 
 **Invoice_date** : Invoice date. Day when the transaction was made.
 
 **Shopping_mall** : Name of the shopping mall where the transaction took place.
 

## Data Cleansing 

Data that has been processed is clean data; there are no duplicates or empty values, so no additional cleanup process is required. However, there is a change in the invoice_date data type from object to datetime64.

## Exploratory Data Analysis

**1. What are the most purchased products by customers?**

![image](https://github.com/fatimahzza/Mini-Project-Data-Analytics/assets/165742717/c0e790ce-2c1f-455d-9708-8ad9d149b1df)


Based on the data above, we can observe that **the number of products sold annually has shown an increasing** trend from 2021 to 2022. **Data for 2023 is not yet available for analysis as it only covers the first three months**. In 2021, there was a lower sales figure of **136.096** compared to the following year. However, there was a significant increase in 2022 to **137.147** This indicates that the business is experiencing positive growth year over year.

**2. What are the most purchased products by customers?**

![image](https://github.com/fatimahzza/Mini-Project-Data-Analytics/assets/165742717/ea5f2733-425f-41c1-b226-1e3f31cc7af8)


Based on the chart, it is evident that certain product categories have significantly higher sales volumes compared to others. In this case, products from the **clothing category** are the mainstays that are **most in demand by customers**. Therefore, the business team can **increase sales in the following month by promoting new products in other categories to customers this month.**

**3.How much money do customers spend each month per year?**

![image](https://github.com/fatimahzza/Mini-Project-Data-Analytics/assets/165742717/a0dfbb89-b242-4660-9951-e02d07b4b0ab)

From the analysis results, we observe that **the total amount of money spent by customers each month per year fluctuates significantly**, but there is always an increase in October. Therefore, business teams can **develop more effective marketing strategies and optimize monthly promotions to increase customer satisfaction and overall business growth.**


**4. What payment methods do customers use most often?**

![image](https://github.com/fatimahzza/Mini-Project-Data-Analytics/assets/165742717/c5b48cc6-2969-4c60-a993-8b405236773a)


Based on the data above, it is evident that the **cash payment method is more popular** than other payment methods. Therefore, the business team can **consider various payment options such as adding electronic money payment methods.**

**5. Is there a difference between the amount spent based on gender?**

![image](https://github.com/fatimahzza/Mini-Project-Data-Analytics/assets/165742717/fcac8fec-7cd4-4567-8db0-d08f84156645)


Based on the data above, it can be observed that the **highest sales for the female gender occurred in 2022**, while the **highest sales for the male gender occurred in 2023**. Therefore, the business team can **consider increasing promotions and products for each gender to maintain and stabilize sales growth.**

## Summary
Data analysis shows that some products have higher sales compared to others, highlighting the importance of prioritizing stock of the most in-demand products. Marketing strategies can be improved by targeting promotions on the most in-demand products, while providing diversified payment options can increase customer satisfaction in transactions. Personalizing the shopping experience can also increase customer loyalty. By implementing these recommendations, it is expected that the business team can achieve higher business targets and improve customer satisfaction.
