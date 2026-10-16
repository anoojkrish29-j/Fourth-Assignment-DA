# Fourth-Assignment-DA
## Assignment 4- Dax and Data visualization

### Calculated Columns:

1 Create a Calculated Column for 'Category Type': created a coloumn and combined category coloumn and sub category column.

2 Calculate Revenue per Order in Order Details Table: created a new table and calculated Amount * Quantity.

3 Create a Calculated Column to Categorize Sales: Found Above and Below average with Amount coloumns Average.


### Calculated Measures:

1 Calculate Order Count: with New measures option created order count, display using card.

2 Calculate Average Profit in Delhi:CALCULATE(AVERAGE('Order Details'[Profit]), 'List of Orders'[City] = "Delhi")

3 Calculate Year-to-Date (YTD) Sales:YTD sales = CALCULATE(SUM('Order Details'[Amount]),DATESYTD('List of Orders'[Order Date]))


### Data visualization:

Compared different sections in the datasets to get the outcome with the help of chart and visualization in Power Bi.

Used clustered column chart, Donut chart,Line chart, Scatter chart, Matrix,Map, Tree map, and Funnel.
