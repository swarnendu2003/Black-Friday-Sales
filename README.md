# Black Friday Sales
Black Friday is a shopping holiday  that takes place on the day after Thanksgiving. It is known for its deep discounts and special deals on a wide range of products, including electronics, home goods, clothing, and more. Many retailers offer special doorbuster deals and extended hours on Black Friday, and it is traditionally one of the busiest shopping days of the year. 

The dataset that we are having contains 537578 rows and 12 columns.

Our main goal will be to do various kind of analysis and get inferences which will be able to help to provide valuable insights on the market and hence will be beneficial for the company.


Here we are basically trying to check out the basic things regarding our dataset such as the column names, the data type of the columns, if there are any null values present in our data, etc. After some analysis we were able to detect a lot of null values in the column Product_Category_2 and Product_Category_3. So now if we try to use the function df.dopna() it would remove all the rows and might create a data loss problem later. Therefore we decide to delete the whole column instead and we get rid of all the null values present in our dataset.

 
