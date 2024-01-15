## How to Setup Great Expectation Tool for Data Quality Check on Postgres Data

1. Install the Python library in your system.
>pip install great_expectations   
2. Creating Data Context
>great_expectations init
3. Connect to Datasource
>great_expectations data source new   
4. Create Expectation Suite of your Data
>great_expectations suite new  
5. If you want to edit or add new expectations run the below command  
>great_expectations suite edit suite_name   
6. Creating Checkpoint
>great_expectations checkpoint new cartcheckpoint  
7. Run the Checkpoint
>great_expectations checkpoint run cartcheckpoint  

## **Great Expectations Dashboard**

If you want to view the **Great Expectations Dashboard** then Navigate to this path **/uncommitted/data_docs/local_site/index.html**