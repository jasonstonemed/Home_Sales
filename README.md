# Module 22: Home Sales Big Data Project

# Introduction – 
The goal of this project is to demonstrate the usage of Spark SQL in analyzing home sales data contained in a csv file. It involves running queries from the temporary view of the data, cached data, and partitioned data. Runtimes were performed under each condition for comparison.

# Setup – 
1.	Apache Spark
2.	A data set of home sales in a comparable format (CSV)
   
# Usage - 
1.	Clone the repository to the local machine
2.	Ensure Spark is installed
3.	Load data into directory accessible by Spark
4.	Update data path
   
# Queries 
Queries run from uncached data:
1.	Average price for a four-bedroom house sold for each year
2.	Average price of a home for each year it was built that has three bedrooms and three bathrooms
3.	Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet
4.	 "view" rating for homes costing more than or equal to $350,000. This query was run to include runtime.
   
Queries run from cached data and partitioned data, with runtimes:
1.	View ratings with an average price of greater than or equal to $350,000

Credits – 

Cached vs Uncached Runtime solution in #9 was provided by ChatGPT 3.5

I would also like to extend great appreciation to everyone who made my BootCamp learning experience possible: my Support Manager, instructors, teaching assistants, my tutor, support assistants, the graders, and all of my fellow students. You all contributed to, and supported, this learning experience and personal journey. Thank you all.
