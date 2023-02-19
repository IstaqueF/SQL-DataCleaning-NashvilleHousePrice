# SQL - Nashville house price - Data cleaning Project

In this project I have cleaned the data and prepared it for the analysis. 
The initial spreadsheet contained multiple inconsistencies in format and in value which needed to be fixed before we could proceed for the main analysis. 

The below operations were carried out

#1 changed data type of the column to make it consistent 

#2 Updated database with new data type 

#3 Found the NULL values in specific columns and populated them using SELF JOIN 

#4 broke out the long string (Address) and assigned the separate values in new columns 

#5 Updated the database with these newly created columns

#6 Changed datatype of specific column from bit to nvarchar and assigned values of "Yes" and "No" in place of 0 and 1. 

#7 Created a temporary table and removed duplicate rows. (I created a temporary table as didn't want to remove values from the origical database) 

#8 Deleted unused columns 
