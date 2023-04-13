Cleaning Data and Removing Duplicates in R Studio and Visualizing it in Power BI

You began by importing the raw data into R Studio. The dataset contained information on customer transactions, including various columns such as transaction ID, customer ID, product ID, and transaction amount.

To start, you removed duplicates using the duplicated() function in R Studio. This function identified and removed rows that were exact duplicates of one another. Once duplicates were removed, you examined the dataset to identify any columns that were not relevant to your analysis. You identified a column containing transaction ID that was not needed for your analysis and used the select() function from the dplyr package to remove this column.

You then inspected the remaining columns to identify any errors or inconsistencies in the data. You found that some transaction amounts were negative, which didn't make sense for your analysis. You used the filter() function to remove these rows.

After cleaning the data, you exported the cleaned dataset as a CSV file to be used in Power BI. You used the write.csv() function to export the cleaned dataset as a CSV file named "clean_customer_transactions.csv" without row numbers.

Next, you imported the CSV file into Power BI. You created a simple bar chart to visualize the total transaction amounts by product. You selected the Product_ID and Transaction_Amount columns from the Fields pane and clicked on the "Bar Chart" visualization type from the Visualizations pane. You then dragged the Product_ID column to the "Axis" field well and the Transaction_Amount column to the "Values" field well. You customized the chart as needed (e.g., changed the colors, added a title) and saved the chart.

This bar chart provided a clear and concise overview of the total transaction amounts by product. It helped business stakeholders identify which products were the most popular and profitable and make informed decisions about marketing and sales strategies.
