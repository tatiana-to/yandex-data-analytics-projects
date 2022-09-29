# Telecom

## Objective

Based on the data of the mobile operator's customers, analyze the behavior of customers and search for the optimal tariff.

## Data

Table users:   

user_ID  
first_name  
last_name  
age  
reg_date - start using the tariff (day, month, year)  
churn_date  - termination of using the tariff (if the value is absent, then the tariff was still valid at the time of uploading the data)
city    
tariff   

Table calls:

id - unique call number  
call_date  
duration  
user_id    

Table messages:

id — unique message number  
message_date  
user_id  

Table internet:

id — unique session number  
mb_used   
session_date   
user_id   

Table tariffs:

tariff_name   
rub_monthly_fee   
minutes_included   
messages_included  
mb_per_month_included   
rub_per_minute - the cost of a minute of conversation in excess of the tariff package  
rub_per_message — the cost of a message  in excess of the tariff package  

## Used libraries

*pandas*, *matplotlib*, *NumPy*, *SciPy*  
