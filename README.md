# Power-BI-Assignment-1-Data-Transformation-Data-Modeling
Import Data,Data Transformation,Merging Data,Handling Missing Data &amp; Duplicate Data,Sorting and Filtering Data,Grouping and Aggregating Data,Data Modeling
Imported the required dataset into Power BI using the Get Data option.
Restrict the "List of Orders" table to only the first 500 rows by using keep rows function
Ensure the “Order Date” column in the “List of Orders” table is set to data type 'Date'by clicking the left corner of the heading 
Change the data type of “Amount” and “Target” columns to ‘Fixed Decimal Number by clicking the left corner of the heading
Format the "CustomerName" column into proper case, ensuring consistent capitalization for each word. by using the Transform-Format-capitalized each word
Merge the "State" and "City" columns to create a new column named "Location" in the format ‘City, State’ by adding new column and = select the bothe value and in between given &
Create a new custom column named "Profit Margin" as the percentage of "Profit" divided by "Amount" created by adding custom column
Add a new conditional column named "Profit Status" based on the values in the by using if and else if
Merge the "List of Orders" and "Order Details" tables into a new single table named "Orders Data" based on the "Order ID" relationship done by group in
Sort the orders by Order Date in descending order to analyze recent trends by selecting descending order 
Filter the orders to focus only on a specific state (e.g., Tamil Nadu) for regional analysis. by using filering 
Duplicate the “Order Details” table and calculate the count of each Order ID, average profit by Category or total amount by Sub-Category. by using by duplicate the order details by right clickk and by using grouping
Duplicate the “Sales Target” table and aggregate the total target amount by Month of Order Date. by using group in 
Establish a relationship between the “List of Orders” and “Order Details” tables using the ‘Order ID’ column. by using manage relationship
Build a relationship between the “Order Details” and “Sales Target” tables based on the ‘Category’ column. Click "Manage relationships" and ensure this relationship is active.by using the same manage relationship
