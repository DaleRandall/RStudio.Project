Cleaning Data and Removing Duplicates in R Studio and Visualizing it in Power BI

I began by importing the raw data into R Studio. The dataset contained information on hollywood movies, including various columns such as Genre, movies produced, rotton tomatoes rating and customer rating.

To start, I removed duplicates using the duplicated() function in R Studio. This function identified and removed rows that were exact duplicates of one another. Once duplicates were removed,

I then inspected the remaining columns to identify any errors or inconsistencies in the data.

After cleaning the data, I exported the cleaned dataset as a CSV file to be used in Power BI. I used the write.csv() function to export the cleaned dataset as a CSV file named "clean_df.csv" without row numbers.

Next, I imported the CSV file into Power BI. I created a simple bar chart to visualize the avrage total transaction amounts by product. You selected the Product_ID and Transaction_Amount columns from the Fields pane and clicked on the "Bar Chart" visualization type from the Visualizations pane. You then dragged the Product_ID column to the "Axis" field well and the Transaction_Amount column to the "Values" field well. You customized the chart as needed (e.g., changed the colors, added a title) and saved the chart.

This bar chart provided a clear and concise overview of the total transaction amounts by product. It helped business stakeholders identify which products were the most popular and profitable and make informed decisions about marketing and sales strategies.
