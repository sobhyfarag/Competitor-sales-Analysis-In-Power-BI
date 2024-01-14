# Competitor-sales-Analysis-In-Power-BI

## Overview: 
The core goal of this project is to build a report using a fictional Sales and Market share dataset for a manufacturing company called ***Sintec***. **Sintec is** looking for a solution to focus not only on the company's performance internally on how well their products sell but also analyze other top competitors' sales and how well they are performing against the other competitors' products.

## Preparing the data: 
- Converting the Data type of ZIP column in `sales.csv` dataset from `numeric` to `tex`
- loading International sales folder to power query using "Combine & transform" and clean it by removing unnecessary columns 
- filling-down the category column in ptoducts table to eliminate the null values 
- extract the currency from the price column.
- geography table: remove unnecessary 2 first rows and then clean use the first row as a header
- for the manufaturer table: transpose it and the use the first row as a header 
## Modeling the data 
- Append the international sales table to sales table 
- create a new calculated column inthe `Geography` table that combines the `Zip` and `country` columns with a comma delimiter and name it as ZipCountry, and create the same column in the `sales` table also
- 
## Qustions to Answer:
- Who are the top competitors generating the most revenue
- Best performing segments abd products
- growth over time
- sakes compared to previous year
  
