The project is a banking project where we have used a banking dataset. Here in this dashboard we are going to show features like Loan analysis and Deposit Analysis and summary of the overall dataset. 
This dataset basically contains information about bank details ,various client details which consists of multiple tables which are interlinked with each other through keys like primary key and foreign key.
The various tables are Banking Relationship, Client-Banking, Gender, Investment Advisor and Period.
Data Cleaning –
Creating bins for the Estimated Income > 300000 as High and > 100000 as Mid and < 100000 as Low with the column named as Income Band in Clients-Banking table.
Calculated Functions – 
Sum : 
The power bi sum function will add all the numbers in a column and the column contains numbers to sum. It returns a decimal number.
Syntax :
Sum= SUM(<column>)
Example:  Bank Deposit = SUM(Banking_Clients [Bank Deposits] )


DistinctCount :

Counts the number of distinct values in a column

Syntax:

DISTINCTCOUNT(<column>)

Example :

Total Clients = DISTINCTCOUNT((Banking_Clients [Client ID] )

Finding: 
Bank loan is highest for Mid Income band and lowest for High Income band. 
Highest Deposit features are in the European countries followed by Asian Countries.
Lowest Deposit features are in Australian countries followed by African countries.
Bank loan is highest for European countries and lowest for African countries. 






