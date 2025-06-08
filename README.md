# ☕ Coffee Sales Analysis

##  Project Overview
This project analyzes a fictional coffee order dataset using Microsoft Excel to understand customer behavior, product sales, and geographic performance. The end result is an interactive sales dashboard highlighting key business insights.

## Data Sources
The project utilizes three main datasets:
- orders: Contains order-level information such as customer ID, product ID, quantity, and sales.
- customers: Includes customer names, countries, and loyalty status.
- products: Contains product ID, product category, and coffee bean types.

## Techniques Used
1. XLOOKUP

   Formula: `=XLOOKUP(C2;customers!$A$1:$A$1001;customers!$B$1:$B$1001;;0)`

3. INDEX MATCH

   Formula: `=INDEX(products!$A$1:$G$49;MATCH(orders!$D2;products!$A$1:$A$49;0);MATCH(orders!I$1;products!$A$1:$G$1;0))`

5. Multiplication formula for Sales
6. Multiple IF functions

   Formula: `=IF(I2="Rob";"Robusta";IF(I2="Exc";"Excelsa";IF(I2="Ara";"Arabica";"Librica")))`
   
8. Date Formatting
9. Number Formatting
10. Check For Duplicates
11. Convert Range to Table
12. Pivot Tables and Pivot Charts + Formatting
13. Insert Timeline + Formatting
14. Insert Slicers + Formatting
15. Updating the Pivot Table Data Source
16. Building the Dashboard

## Findings
- Arabica and Robusta show consistent sales across all years, with peaks in mid and late months (especially September).
- Librica had a massive spike in January 2022, possibly due to promotions or unusual demand.
- Excelsa experienced high sales in April 2019 and October 2020, but dropped significantly in 2022.
- Overall sales peaked in 2021, while 2022 saw a notable decline across all coffee types.
- High sales typically occur in Q3 (July–September), suggesting potential seasonal patterns.
- The United States contributes over 75% of total sales, making it the largest market.
  

#  Recommendations
- Focus marketing and inventory efforts during Q3 (July–September) to leverage seasonal demand and maximize sales.
- Focus marketing efforts on top-performing countries, especially the U.S.
- Implement a loyalty program for high-value customers to encourage repeat purchases.
