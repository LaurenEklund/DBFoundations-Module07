**Name:** Lauren Eklund **Date:** 11/30/2021
**Course:** Foundation of Databases & SQL Programming
**GitHub Link:** https://github.com/LaurenEklund/DBFoundations-Module07.git

# Assignment 7 – SQL Functions #

### Introduction ###
Functions in SQL are a feature that allow advanced manipulation of queried data in SQL statements and performs a variety of tasks with inputs. They are a named series of SQL statements that perform a specific action. There are different types of functions including UDFs, Scalar, Inline, and Multi-Statement functions. This paper will discuss the different functions in addition to when they might be useful. 

### Different Types of Functions ###
 
There are a variety of functions used in SQL that return meaningful data in queries. Scalar functions return a singular value with a given input, such as modifying the format of an existing string or date, converting data types, performing a calculation, etc. In-line functions are a type of table valued function that returns a result set rather than a single value and can also filter returned values on a given parameter. Examples of this might be returning data about a list of sales prior to a specified date in the function, or above a dollar amount threshold etc. Lastly, multi-statement functions are an additional type of table valued function that returns rows of data sets, however it involves the use of table variables that stores result sets returned from within the functions. 

SSMS has several pre-made functions that can be used on demand without any setup. However, it also allows users to create their own functions for more custom queries through User Defined Functions (UDFs). All of the aforementioned function types can be created as a User Defined Function, which is beneficial to use when the pre-made functions don’t accommodate a task that a user needs accomplished. For example, a user might need dates returned in a different format that pre-made functions don’t allow for, so a user could create a custom scalar UDF that accommodates the specific date formatting requirements etc. Or a user might also create a table value function that returns an entire data set with the customized dates according to a specific parameter, such as rows with dates within a specified date range, etc. 

### Conclusion ###
 
In this writing we learned about some of the basics of functions and their uses. There are a variety of different types of functions, including SSMS pre-made functions to custom functions created by users as UDFs.
 
