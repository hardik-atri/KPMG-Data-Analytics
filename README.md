# KPMG-Data-Analytics
Completed the KPMG Data Analytics Virtual Internship by Forage

Task 1 - Data Quality Assessment
 * There are missing values in the dataset

 * Invalid Data: 
          a. Entry with wrong dob having year = 1843 
          b. Gender Column consist of Femal , M : 1 , F : 1 , Male , Female
          c. There is a transaction with 5034 id which is invalid since there is no customer with 5034 customer_id
          
 * There are duplicate entries in the dataset

 * There are some irrelevant columns in the dataset

 * Inconsistent data: ( eg job_title = health_coach , job_industry = Property )

Task 2 - Data Preprocessing and Modelling
 * Cleaned the data 

 * Performed RFM analysis to segment the customers.
           1. Recency = Recent transaction date in dataset - Transaction Date
           2. Make pivot table
                    * Row = Customer_id
                    * Values = Recency , Count of Product_id ( Frequency ), Sum of Profit ( Monetary)
           3. R_score (1 - 4 ) = if Recency > 75 quartile, 1
                    * Similarly calculate F_score, M_score
           4. RFM score = 100 * R_score + 10 * F_score + M_score
           5. Segment customer into different sections ( Diamond , Gold, Silver, Bronze )
                    * Diamond customers have the maximum RFM value which indicates they have the highest customer value.

 * Data Modelling
           1. Used Customer Profile as target variable calculated using RFM analysis.
           2. Modelled the data using Random Forest and calculated important features.


Task 3 - Creating Dashboard using Power BI
 * Using important features, we build the dashboard using Power BI


