# Bank 

https://preppindata.blogspot.com/2023/01/2023-week-1-data-source-bank.html

## Requirements
- Split the Transaction Code to extract the letters at the start of the transaction code. These identify the bank who processes the transaction 
- Rename the new field with the Bank code 'Bank'. 
- Rename the values in the Online or In-person field, Online of the 1 values and In-Person for the 2 values. 
- Change the date to be the day of the week 
- Different levels of detail are required in the outputs. You will need to sum up the values of the transactions in three ways:
    - Total Values of Transactions by each bank
    - Total Values by Bank, Day of the Week and Type of Transaction (Online or In-Person)
    - Total Values by Bank and Customer Code
