#Orders Dataset - Information
This is the dataset consist of 1200 Rows x 14 Columns.

Type of Columns
    • Numerical  -  Quantity, UnitPrice , ItemsInCart, TotalPrice, Date
    • Categorical – Product, Order Status, RefferalCode , CustomerID, ShippingAddress, PaymentMethod, CouponCode
    • Mixed – OrderId, TrackingNumber

#Task 1 - Data Cleaning

Data Cleaning Process

    • Handling Missing Value – Column “CouponCode” has 309 missing values, so it was filled with “NO COUPON”
    • Removing Duplicates – Drop Duplicate Rows based on key columns
    • Correcting Data Type – Convert Data to appropriate types( Date is changed into “mm/dd/yy format’’, UnitPrice and TotalPrice are changed into currency)
    • Standardizing Text Data – Change Text to Proper Case, remove extra spaces and fix typos.

#Task 2 - Exploratory Data Analysis 

In this task, we will do descriptive statistics on dataset and find some key observation summary after analyzing columns by doing aggregation.
We have done some insights on Marketing Source Effectiveness, Product Sales, Payment Method Distribution and Order Status.
KEY OBSERVATIONS SUMMARY
1. Chair and Laptop have the highest revenue at  approximately $195,000 and $192,000 respectively while the total revenue is $126.741.96.
2. The average order (mean) per value is $1,053.97 and median is $823.62
3. Total number of order and customer is 1200.
4. Outliers of Total Price in first quarter is 410.52 and in third quarter, it is 1578.475



