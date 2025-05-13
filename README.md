# hw-updates
תרגיל ב groupby JOIN- מצגת 22 שקף 25-26  תרגיל ב PIVOT- מצגת 23 שקף 9 הקובץ CSV SALES FUNNEL CRM -- נמצא ב- GITHUB של השיעור  תרגיל ב MATPLOTLIB (לאחרי פסח) מצגת 23 שקף 23


**
**תרגיל ב groupby JOIN-
**מצגת 22 שקף 25-26
Class Exercise - Dataframe Join & Group by**
 Instructions:
 Use the attached Dataframes and implement the following:
 products_df = pd.DataFrame({
 'Product_ID': [1, 2, 3],
 'Product_Name': ['iPhone 12', 'Samsung S21', 'Pixel 5'],
 'Product_Price': [999, 899, 699],
 })
 sales_df = pd.DataFrame({
 'Sale_ID': [1, 2, 3, 4, 5, 6, 7],
 'Sale_Date': pd.to_datetime(['2021-01-01', '2021-02-01', '2021-02-15', '2020-03-01', '2020-04-01',
 '2020-02-15', '2020-01-01']),
 'Customer_ID': [1, 2, 3, 2, 3, 4, 4],
 'Product_ID': [1, 1, 2, 2, 3, 3, 1],
 })
 25
Class Exercise - Dataframe Join & Group by
 Instructions:
 Use the attached Dataframes and implement the following:
 customers_df = pd.DataFrame({
 'Customer_ID': [1, 2, 3, 4],
 'Customer_Name': ['John Doe', 'Jane Doe', 'Jim Brown', 'Jake Smith'],
 'Customer_Age': [25, 30, 35, 20],
 'Customer_Email': ['john@doe.com', 'jane@doe.com', 'jim@brown.com', 'jake@smith.com'],
 })
 ● For each product calculate the number of customers that bought it and their average age
 For example → For product ‘iPhone’ customer count was: 2 and average customer age was: 25
 ● For each year calculate the total sales for each product for that year 
For example → For year ‘2020’, for product ‘iPhone’ the number of sales was 1








**תרגיל ב PIVOT-
**מצגת 23 שקף 9

 Instructions:
 For this exercise use the course ‘Sales_Funnel_CRM.csv’ file
 Load the requested file into a valid Pandas Dataframe and implement the following:
 ● Show in a new Dataframe how many licenses sold for each company from each product
 ● Show in a new Dataframe for each company what is the total amount of sale price and licences sold
 Hint: you don’t need to use the original Dataframe as your pivot table source, you can reduce the 
amount
 9
 of unused columns by creating a Dataframe from just the columns you need and then apply the pivot







**
**תרגיל ב MATPLOTLIB (לאחרי פסח)
**מצגת 23 שקף 23**
Instructions:
 The Numpy library provide np.sin() and np.cos() functions that get the sin / cos value for each element in the
 specified array.
 ● create your x-values from 0 to 5 at intervals of 0.1.
 ● Generate your first set of y-values by using the sin() trigonometric function on your x-values.
 ● Draw these x and y values on a chart. Be sure to give your chart a fitting title and remember to label 
your x and y axes appropriately.
 ● In the same figure, generate another set of y-values using the cos() trigonometric operation.
 ● Draw these new y-values against the same x-values but on a new separate chart in the same figure. 
Give your chart a suitable title and don't forget to label your x and y axes. To adjust for visual comfort, 
allow for some space between the two charts.
 ● Finally, display the figure which should consist of the two separate plots.
