# Home Sales Analysis
Determine key metrics about home sales data using SparkSQL.

The Home_Sales_colab Jupyter notebook uses SparkSQL and reads home sales csv data from a AWS S3 bucket to determine the following key metrics about home sales from 2010 to 2017 -
1. The average price for a four-bedroom house sold for each year
2. Average price of a home for each year it was built that has three bedrooms and three bathrooms
3. Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet
4. The "view" rating for homes costing more than or equal to $350,000. The run time for the query

Next, the script uses Spark to create temporary views, partitions the data, caches and uncaches a temporary table, and verifies that the table has been uncached.
