# Retail-Store-Data-Modeling-and-Analysis-using-DataStage

## Project Overview
The project focuses on utilizing IBM InfoSphere DataStage to develop efficient ETL (Extract, Transform, Load) pipelines. These pipelines are designed to create data marts and facilitate analysis of data from a fictional retail store. The objective is to ensure all changes in the dimensions are preserved during the ETL process.

## Project Steps
1. **Extraction**: Extracting retail, customer, and product data from the data warehouse.
2. **Transformation**: Transforming the extracted data to make customer names uppercase.
3. **Loading**: Load the transformed data to a Retail Data Mart.
4. **Analysis**: Answering some business needs by using the Retail Data Mart:
   - Display count of all transactions for each employee for each store.
   - Display max profit made by which customer type. Illustrate: customer type “foreign” makes 5 transactions, customer type “citizen” makes 3 transactions. So, max profit made by
     foreign customers. Named DataMart “ACTIVATIONSALES_DATA_MART”.
   - Based on which customer makes profit, give them Bonus Equation = Annual_Income * SpendingScore * 100.

## Project Files
- **DataStage Jobs**: Contains the dsx jobs used.
- **Dataset**: The data used to make the star schema model.
- **Output Files**: The output for each job.
- **Screenshots**: Screenshots for each job.

## DataStage Jobs

### Count of Transactions
![Count of Transactions](https://github.com/ahmeedaliii/Retail-Store-Data-Analysis-And-ETL-using-DataStage/blob/main/screens/Count_of_Transactions.PNG)

### DataMart
![DataMart](https://github.com/ahmeedaliii/Retail-Store-Data-Analysis-And-ETL-using-DataStage/blob/main/screens/DataMart.PNG)

### Max profit
![max_profit](https://github.com/ahmeedaliii/Retail-Store-Data-Analysis-And-ETL-using-DataStage/blob/main/screens/max_profit.PNG)

### Bonus_equation
![bonus_equation](https://github.com/ahmeedaliii/Retail-Store-Data-Analysis-And-ETL-using-DataStage/blob/main/screens/bonus_equation.PNG)

