# Sales Analysis

Analyze sales data to gain insights into which cities in the U.S. have sold the most athletic wear over two years. Determine which retailers had the greatest total sales for athletic wear, and which retailers sold the most women's athletic footwear. Finally, determine which day and week had the highest sales for women's athletic footwear.
The areas of focus on this assignment are .GROUPBY, .PIVOT, .PIVOT_TABLE, sorting and binning.

## Details

*Combine and Clean the Data 
*The two DataFrames have been combined on the rows using an inner join and the index has been reset.
*The "invoice_date" column has been converted to a datetime data type. 
*Determine which Region Sold the Most Products  
*A groupby or pivot_table function has been used to create a multi-index DataFrame with the "region", "state", and "city" columns. 
*The aggregated column has been renamed to reflect the aggregation of the data in the column. 
*The results are sorted in ascending order to show the top five regions, including the state and city that sold the most products. 
*Determine which Region had the Most Sales 
*A groupby or pivot_table function has been used to create a multi-index DataFrame with the "region", "state", and "city" columns. 
*The aggregated column has been renamed to reflect the aggregation of the data in the column.
*The results are sorted in ascending order to show the top five regions, including the state and city that generated the most sales.
*Determine which Retailer had the Most Sales  
*A groupby or pivot_table function has been used to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns. 
*The aggregated column has been renamed to reflect the aggregation of the data in the column. 
*The results are sorted in ascending order to show the top five retailers along with their region, state, and city that generated the most sales.
*Determine which Retailer Sold the Most Women's Athletic Footwear  
*A filtered DataFrame is created that shows only women's athletic footwear sales data. 
*A groupby or pivot_table function has been used to create a multi-index DataFrame with the "retailer", "region", "state", and "city" columns. 
*The aggregated column has been renamed to reflect the aggregation of the data in the column.
*The results are sorted in ascending order to show the top five retailers along with their region, state, and city that had the most women's athletic footwear sales.
*Determine the Day with the Most Women's Athletic Footwear Sales  
*A pivot table is created that has the "invoice_date" column as the index and the "total_sales" column assigned to the values parameter. 
*The aggregated column has been renamed to reflect the aggregation of the data in the column.
*The resample function is used on the pivot table, the data is placed into daily bins, and the total sales for each day is calculated. 
*The results are sorted in ascending order to show the days that generated the most women's athletic footwear sales. 
*Determine the Week with the Most Women's Athletic Footwear Sales  
*The resample function is used on the pivot table, the data is placed into weekly bins, and the total sales for each week is calculated.
*The results are sorted in ascending order to show the weeks that generated the most women's athletic footwear sales.


# Reference
Chatgpt 
