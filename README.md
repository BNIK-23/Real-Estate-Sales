![Screenshot 2025-03-25 144320](https://github.com/user-attachments/assets/61b1fb4c-bc7a-4458-87e9-19ba8357d3df)

OBJECTIVE
To analyze property sales and make a breakdown of the total sales, average and number of sales by the different property types and residential types.
KPIs
Total Sales 
Sales trend
Average Sales
Sales breakdown by property type and residential type 
Valuation to sale conversion rate.

Tools used:
Power BI

Data Source:
Data.gov

Data Cleaning
- Removed duplicates
- Removed columns like Address, Assessor remarks
- With the aid of a custom column, removed rows where both Sale Amount and Assessed Value were 0.
- Replaced blanks with unspecified in the Property Type column.
- Split the Date column by delimiter, reordered the columns as per UK date type, merged the columns and set date data type.
- In the Property Type column, replaced entries that specified the residential type with “Residential Type” to standardize data.
- Standardized columns.

Insights
- Total sales; $43Billion
- Average Sales: $443K
- Total number of sales: 96K
- Residential Property Type accounted for the most sales at $28 Billion. It must be noted that $10 Billion worth of total sales is not specified as to which Property Type it belongs.
- On average, apartments sold at a higher value per unit relative to other property types.
- Total number of sales shows a gradual increase from 2012 with a peak in 2021 followed by a gradual decrease in sales thereafter.
- The valuation to Sale Conversion rate steeply increased from 2001 to a peak in 2003 but then decreased thereafter with slight but significant increases in 2006, 2015 and 2022.
- Between 2009 and 2014, sale ratio (Valuation to Sales ratio) was less than 1. This means properties were sold below the valuation or assessed value, as such sellers made a loss.




Created a Date table for DAX Time Intelligence Calculations.
DAX functions and formulas were used to create measures to aid in the analysis.
