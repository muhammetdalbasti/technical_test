# technical_test

This code snippet demonstrates web scraping using Selenium to extract financial data for the company TESLA (TSLA) from Yahoo Finance. It initializes a Chrome driver with specified options, navigates to the TSLA stock page, and handles cookie consent if present. The code then selects the "Profile" and "Financials" tabs to retrieve relevant information.

The code first retrieves the number of Full Time Employees from the "Profile" tab and prints it.

Moving to the "Financials" tab, the code extracts the Total Revenue for the years 2020, 2021, and 2022. The revenue figures are converted to integer values and multiplied by 1000 to represent the actual revenue amounts.

Next, the code retrieves the Operating Income for the same years, following a similar approach as with Total Revenue.

Additionally, the code expands the "Selling General and Administrative Expense (SG&A)" section on the "Financials" tab. It then retrieves the SG&A expenses for the years 2020, 2021, and 2022, using the same conversion and multiplication steps.

Each extracted value is printed, providing insights into the financial performance of TESLA.
