# athletic_sales_analysis

## Data Import and Preparation:

- Imported and combined sales data from 2020 and 2021 into a single DataFrame (combined_df) using concat funtion.

- Checked and confirmed data types, and converted the invoice_date column to a datetime format.

## Analysis Using Grouping and Pivot Tables:

###           Region Products Sold Analysis:
- Determined the top regions with the highest number of products sold using the group_by and pivot_table functions on the units_sold column, showing results by retailer, region, state, and city.
- Sorted and displayed the top 5 regions with the most sales.


###           Region Sales Analysis:
- Determined the top regions with the highest total sales using pivot_table function on the total_sales column, showing results by retailer, region, state, and city.
- Sorted and displayed the top 5 regions with the most sales.


###           Retailer Sales Analysis:
- Determined the top retailers with the highest total sales using pivot_table function using the total_sales column, showing results by retailer, region, state, and city.
- Sorted and displayed the top 5 retailers with the most sales.


###           Women's Athletic Footwear Sales:
- Filtered the data for women's athletic footwear and identified the top 5 retailers by units sold.
- Determined the day and week with the most sales of women's athletic footwear using resampling into daily and weekly bins respectively.
- Sorted the resampled df's to display the top 10 days and weeks with most sales.


