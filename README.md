# Churn-Rate-Analysis-Power-BI                             
### Bank Churn Rate Analysis-Power BI                                  
This dataset is for ABC Multistate bank with following columns:                
                                
customer_id, unused variable.                              
credit_score, used as input.                          
country, used as input.                            
gender, used as input.                            
age, used as input.                                   
tenure, used as input.                           
balance, used as input.                               
products_number, used as input.                               
credit_card, used as input.                                  
active_member, used as input.                                    
estimated_salary, used as input.                                          
churn, used as the target. 1 if the client has left the bank during some period or 0 if he/she has not.   
#### (Data Source- Kaggle)   

### Aim is to predict the Customer Churn Rate 

Created a Measure in Power Query Editor to find the Churn Rate by using a DAX formula -       
#### Churn Rate = SUM('Bank Customer Churn Prediction'[churn])/COUNT('Bank Customer Churn Prediction'[customer_id])                                       
Changed Formamt to Percentage                                   
Created Crad Visual to show the Churn Rate, Total Customers, Active Customers & Churn Customers                              
Crated a Pie Chart to show the Gender Distribution                               
Created Line Chart showing Churn Rate for different tenures                                   
Created a Bar chart to analyse the churn Rate based on Products Numbers                              
Inserted a slicer for different countries     

## Insights                 
Churn Rate for ABC Multistate bank is 20.4 % which is very high.                    
Churn Rate for Germany is Highest at 32.4 %                              
Female(25.1 %) have a higher churn rate compared to Male customers (16.5%)                           
Churn Rate is highest when tenure is very less takes a dip when the tenure is between 2 to 7 and rises again.                                 
Produt number 4 has 100% churn rate followed by Product number 3 (82.7%)                              
Product 2 has lowest churn rate (7.66%) followed by Product 1 (27.7%)                                
