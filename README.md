Cleaning Data and Removing Duplicates in R Studio and Visualizing it in Power BI

I began by importing the raw data into R Studio. The dataset contained information on hollywood movies, including various columns such as Genre, movies produced, rotton tomatoes rating and customer rating.

To start, I removed duplicates using the duplicated() function in R Studio. This function identified and removed rows that were exact duplicates of one another. Once duplicates were removed,

I then inspected the remaining columns to identify any errors or inconsistencies in the data.

After cleaning the data, I exported the cleaned dataset as a CSV file to be used in Power BI. I used the write.csv() function to export the cleaned dataset as a CSV file named "clean_df.csv" without row numbers.

Next, I imported the CSV file into Power BI and created a visual dashboard.

My Power BI presentation https://app.powerbi.com/links/SgHrazxoDb?ctid=6efd0f20-57c8-4447-b53f-00d4992ca50b&pbi_source=linkShare
![2023-04-06 (1)](https://user-images.githubusercontent.com/126267763/231778557-bb8e0bd2-2491-46ff-8754-b0cfee2b5fee.png)
