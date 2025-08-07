# Cancelled-Orders-Analysis
## Overview 
This project statistically analyses and visualises patterns in Amazon product order cancellations. The goal was to identify any corealation/association with predictors and order cancellation. Predictors analysed in the project are: category of the product, mode of payment and price. 
## Dataset 
Kaggle- Amazon Sales 2025 
https://www.kaggle.com/datasets/zahidmughal2343/amazon-sales-2025
Key data- 250 records of Amazon sales transactions, date, product type, price, total sales, customer address, mode of payment and orde status.  
## Tools and Libraries 
Python (Jupyter Notebooks)
Pandas
NumPy 
Matplotlib 
Seaborn 
SciPy

## Findings and visuals
Firstly, a overall trend in the order status was analysed and visualised. About **35% of the orders were completed, 34% were pending and 30.8% were cancelled**. Then the loss of sales from these cancelled orders was calculated using Python code, which reuslted in loss of $6503. 
<img width="561" height="502" alt="download" src="https://github.com/user-attachments/assets/f112a77e-ba60-418c-ba17-bee956aa1d99" />
Then, each predictor- Product Category, Payment Method and  Price were analysed indivisually. For categorical variables such as- product category and payemnt method, a chi-square test was conducted to check for association and for price which is numerical variable the corelation coefficient and coeficient of determination was caluclated to see if there was in corelation. 
For the chi-sqaure test a **significance level: α = 0.05** was used. 
There was **no statistically significant association between product category and status of the order**. But, it is clearly visible that **Electronic items were almost half (47.4%) of cancelled orders, followed by home appliances (20.6%), clothing (16.5%), footwear (9.3%) and books (6.2%)**. This data is clearly represented in the following visuals.  <img width="1225" height="525" alt="download" src="https://github.com/user-attachments/assets/aacf44f1-fb45-4fc4-9d1c-9dca57017f66" />
Again, for payment method, there was **no statistically significant association between mode of payment and order cancellation**. In addition to that, it was seen that **using Amazon Pay had the least order cancellation and the other modes didn't have a substantially different proportion of cancelaation**. This can be seen in the visual below. <img width="1227" height="601" alt="download" src="https://github.com/user-attachments/assets/e1b3e128-d02e-4955-bd17-eee8ee3f40da" />
While analysiing price, there was **no corelation seen between price and cancellation of order**, this can be seen from the graph below- <img width="687" height="563" alt="download" src="https://github.com/user-attachments/assets/0e5051bd-2585-4664-8415-93e28169c393" />.
