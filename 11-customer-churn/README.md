# Сustomer Сhurn

## Objective

Based on data about visitors of a fitness center network, predict the probability of churn for each client in the next month, and use clustering to describe user portraits

## Data

-gender
-living or working in the area where the fitness center is located
an employee of the club's partner company (cooperation with companies whose employees can receive discounts on a subscription - in this case, the fitness center stores information about the client's employer)
-the fact of the initial registration as part of the "bring a friend" promotion (used a promo code from a friend when paying for the first subscription)
-a contact phone number
-age
-time since the first visit to the fitness center (in months)

Information based on the log of visits, purchases and information about the current status of the client's subscription:
-duration of the current active contract (month, 6 months, year)
-term until the end of the current active contract(in months)
-the fact of attending group classes;
-the average frequency of visits per week for the entire time since the start of the contract;
-average frequency of visits per week for the previous month
-total revenue from other services of the fitness center: cafe, sporting goods, beauty and massage salon
-fact of churn in the current month.

## Used libraries

*pandas*, *matplotlib*, *seaborn*, *scikit-learn* 
