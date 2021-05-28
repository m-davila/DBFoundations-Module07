Maribel Davila
May 27, 2021
FDN of Databases & SQL Programming
Assignment 07
GitHub Repository Link
GitHub Webpage


                                                                                SQL Functions
Introduction  
In this assignment document I will reflect on the material covered in the functions module seven. I will highlight some of the key concepts in when a SQL UDF is used, and comparer the differences and similarities between scalar, inline, and multi-statement functions. 

SQL UDF
An SQL UDF is an abbreviation for a user defined function. An SQL UDF allows parameters to perform an action like a calculation and returns the result as a value which can be a single value or even a set of values. User defined functions are useful to store complex codes in one structure, allows an easier option to test input parameters, and allows users to make any needed changes to the code in one place and reflect the changes at every place that the function is used. There are two types of SQL user defined functions that we used in assignment seven. Scalar functions allow a return of a single value such as an integer. Table value functions allow a return of a table. When understanding when to use an SQL UDF, it can be extremely beneficial.

Comparing Scalar, Inline, and Multi-Statement Functions
A scalar function returns a single value by allowing more than one parameter. Scalar functions are good to use when looking to simplify code. For instance, a scalar function can be used rather than using a formula in each query. In contrast, an inline function returns a value functions and does not have return variables associated. An inline function can be used to result in the functionalities of parameterized views and the table returned can be used to join additional tables. A multi-statement function returns multiple statements. This type of function executes at least one query. Inline and multi-statement functions are different in that inline functions do not require there to be a specification of the return table while multi-statement functions declare a table variable that will be used and accumulates the rows that would be returned as a value from the function. In general, inline functions are faster than multi-statement functions. These three types of SQL functions have benefits and different circumstances where they are ideal to use. As such, it is important to understand how these types of functions compare and when to use each. 

Summary
Assignment seven focused on learning when to use a SQL UDF, and the variety of functions such as scalar, inline, and multi-statement functions. This assignment prompted the opportunity to apply the material covered in the functions module to run the code provided and work on implementing the different functions. Overall, this assignment was good practice to check that the code provided the desired results in the assignment requirements. 
