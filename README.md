# bigquery-test-data
Projects to load data to BigQuery for descriptive and predictive analytics.  

The purpose of this project was to create and load test data of 50K sales transactions to BigQuery.  
To learn more about BigQuery check out the documentation: https://cloud.google.com/bigquery/docs/introduction 

This is a 2 part process:  Generate the test data in Python using Faker module.  Part 2 is to load the data into BigQuery for analysis.    

Step 1 is to create a new project in the Google Console.  

The code generates randomized transactions that simulate several months of grocery store purchases.

## Steps followed in this project

- Create a new project in the Google Console.    
- Create the Dataset and Table where you want to load the test data.
- - For this project, I created Dataset named Test_Data_Faker and a Table named Grocery1.
- Use Python code to generate the test transactions.  Element names and transaction count is configurable.
- - For more information on Faker check out: https://pypi.org/project/Faker/
- After the Python code completes the test data is uploaded to BigQuery and can be accessed via the Google Cloud Console.
