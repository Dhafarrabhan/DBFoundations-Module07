# Functions in SQL

### Introduction
SQL language offer its users the opportunity to improve the efficiency of their codes using either bulit-in or uder-defined functions.  
### UDFs in SQL
UDF is short for User Defined Functions which is a capability in SQL that allows users to code and customize their functions to be called in as needed to perform a specific function. Using UDF minimizes the amount of time and effort required to re-write the code each time requieed to perform the same set of activities. 
### The differences between Scalar, Inline, and Multi-Statement Functions  
Scalar Function: It accepts more than a single parameter and returns one value.
Inline Table-Valued Function: This type of functions accepts multiple parameters and returns the results in rows and colomns similar to a view. The results can be called in a another query.
Multi-Statement Table-Valued Functions: This type of function returns the results in a table. “The function body might consists of multiple statements and one of which will populate this TABLE VARIABLE. And the scope/life of this TABLE VARIABLE is limited to only this function - outside of this function it is not available” 1. 
### Summary
Functions are important and necessary to ensure the script is optimized and ensure the data can be pulled as fast as possible expecailly when the data set is large and complex. 
