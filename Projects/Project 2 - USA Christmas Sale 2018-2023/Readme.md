# Project : USA Christmas Sale 2018-2023


## Introduction
The dataset contains a wealth of sales data, which incorporates trends, patterns, and key performance indicators across the holiday season. This project will uncover actionable insights and trends, helping stakeholders to make informed decisions and enhance their marketing and sales strategies.

Key objectives of this analysis include:

* `Trend Analysis` : Examine annual sales trends and identify patterns across different years to understand seasonal fluctuations and growth trajectories.
* `Regional Performance` : Assess sales performance across various regions to pinpoint high-performing areas and identify regions that may require additional focus.
* `Product Insights` : Analyze which products or categories perform best during the holiday season, providing valuable information for inventory and promotional planning.
* `Comparative Analysis` : Compare sales performance year-over-year to evaluate the impact of various factors such as economic conditions, marketing campaigns, and consumer behavior changes.


## Original Datasets (Denormalised Dataset with column description)
* TransactionID (Unique identifier for each transaction)
* Date (Date of the transaction, format: YYYY-MM-DD)
* Time (Time of the transaction, format: HH:MM:SS)
* CustomerID (Unique identifier for each customer)
* Age (Age of the customer)
* Gender (Gender of the customer: Male, Female, Other)
* Location (City or town where the purchase was made)
* StoreID (Unique identifier for the store, if applicable)
* OnlineOrderFlag (Boolean: True if online, False if in-store)
* ProductID (Unique identifier for the product)
* ProductName (Name of the product)
* Category (Category of the product, e.g., Electronics, Clothing, Toys, Food, Decorations)
* Quantity (Number of items purchased in the transaction)
* UnitPrice (Price per unit of the product)
* TotalPrice (Total price for the product, calculated as Quantity * UnitPrice)
* PaymentType (Type of payment, e.g., Credit Card, Debit Card, Cash, Online Payment)
* PromotionApplied (Boolean: True if any promotion was applied, False otherwise)
* DiscountAmount (The amount of discount, if any)
* GiftWrap (Boolean: True if the product was gift-wrapped, False otherwise)
* ShippingMethod (Method of shipping, e.g., Standard, Express, Overnight, if online)
* DeliveryTime (Number of days taken for delivery, if online)
* Weather (General weather condition on the day of purchase, e.g., Snowy, Rainy, Sunny)
* Event (Special events on the purchase day, e.g., Christmas Market, Black Friday)
* CustomerSatisfaction (Customer satisfaction rating, on a scale of 1-5)
* ReturnFlag (Boolean: True if the product was returned, False otherwise)


## Entity- Relationship Diagram (Normalised dataset)
![ER - USA Christmas Sales](https://github.com/user-attachments/assets/28c2ec32-e752-4278-96ed-c7df699ac404)



## Application
Microsoft - Power BI Desktop


## Code
- Dataset >> Dataset/USA Christmas Sales 2018-23.xlsx
- Column Description >> Dataset/Column Description.xlsx
- Questions >> Questions.pdf
- Power BI File >> code/Project - USA Christmas Sales 2018-23.pbix
- Output >> Project - USA Christmas Sales 2018-23 Without Apply Filter.pdf and Project - USA Christmas Sales 2018-23 With Apply Filter.pdf


## Reference
Dataset Reference : https://onyxdata.co.uk/data-dna-dataset-challenge/datadna-dataset-archive/
