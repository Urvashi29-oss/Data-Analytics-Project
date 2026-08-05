#Orders Dataset - Information
This is the dataset consist of 1200 Rows x 14 Columns.

Type of Columns
    • Numerical  -  Quantity, UnitPrice , ItemsInCart, TotalPrice, Date
    • Categorical – Product, Order Status, RefferalCode , CustomerID, ShippingAddress, PaymentMethod, CouponCode
    • Mixed – OrderId, TrackingNumber

#Data Cleaning Project 1

Data Cleaning Process

    • Handling Missing Value – Column “CouponCode” has 309 missing values, so it was filled with “NO COUPON”
    • Removing Duplicates – Drop Duplicate Rows based on key columns
    • Correcting Data Type – Convert Data to appropriate types( Date is changed into “mm/dd/yy format’’, UnitPrice and TotalPrice are changed into currency)
    • Standardizing Text Data – Change Text to Proper Case, remove extra spaces and fix typos.



