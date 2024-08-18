### Home Sales Analysis Project
## Overview
This README outlines the steps that were completed in the Home Sales Analysis project using PySpark. The tasks involved renaming files, importing necessary functions, working with data in Spark DataFrames, and performing various analyses.

## Completed Tasks
1. Renamed the File
The Home_Sales_starter_code.ipynb file was renamed to Home_Sales.ipynb.

2. Imported Necessary PySpark SQL Functions
The required PySpark SQL functions were imported for the assignment.

3. Read Data into Spark DataFrame
The home_sales_revised.csv data was read into a Spark DataFrame.

4. Created Temporary Table
A temporary table named home_sales was created.

5. Performed SparkSQL Queries

* Calculated the average price for a four-bedroom house sold each year, rounded to two decimal places.
* Determined the average price of a home for each year the home was built, with three bedrooms and three bathrooms, rounded to two decimal places.
* Found the average price of a home for each year the home was built, with three bedrooms, three bathrooms, two floors, and at least 2,000 square feet, rounded to two decimal places.
* Calculated the average price of a home per "view" rating for homes with an average price greater than or equal to $350,000, and determined the runtime for this query, rounded to two decimal places.

6. Cached the Temporary Table
The home_sales temporary table was cached.

7. Verified Caching
Confirmed that the temporary table was indeed cached.

8. Compared Cached and Uncached Query Runtime
Using the cached data, the query calculating the average price of a home per "view" rating for homes with an average price greater than or equal to $350,000 was run. The runtime was compared to the uncached runtime.

9. Partitioned Data and Created Temporary Table
The parquet data was partitioned by the "date_built" field. A temporary table was created for the parquet data.

10. Compared Runtime for Partitioned Data
The query calculating the average price of a home per "view" rating for homes with an average price greater than or equal to $350,000 was run using the partitioned data. The runtime was compared to the uncached runtime.

11. Uncached Temporary Table
The home_sales temporary table was uncached.

12. Verified Uncaching
Verified that the home_sales temporary table was uncached using PySpark.

13. Uploaded to GitHub
The Home_Sales.ipynb file was downloaded and uploaded to the "Home_Sales" GitHub repository.

## Conclusion
The tasks outlined above were successfully completed, involving data manipulation, query execution, performance evaluation, and documentation.
