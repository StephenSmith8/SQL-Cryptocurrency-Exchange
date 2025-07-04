# SQL-Cryptocurrency-Exchange

Project Overview

This project is centered on helping a cryptocurrency exchnage analyze their ledger data using SQL aggregate functions. The name of the table in this project is called 'transactions' and it comsists of the columns below:

- id
- user_id
- date
- currency
- money_in
- money_out

Listed below are the query prompts I was required to complete for this project:

1. Let’s start by checking out the whole transactions table. What is the total money_in in the table?
2. The money_out column records the amount (in USD) the user sold. What is the total money_out in the table?
3. The money_out column records the amount (in USD) the user sold. What is the total money_out in the table?
4. It was reported that Bitcoin dominates Fiddy Cent’s exchange. Let’s see if it is true within these dates by answering two questions:
  - How many money_in transactions are in this table?
  - How many money_in transactions are in this table where ‘BIT’ is the currency?
5. What was the largest transaction in this whole table? Was it money_in or money_out?
6. What is the average money_in in the table for the currency Ethereum (‘ETH’)?
7. Let’s build a ledger for the different dates. Select date, average money_in, and average money_out from the table. And group everything by date.
8. To make the previous query easier to read, round the averages to 2 decimal places. Give the column aliases using AS for readability.
