# Senator Stock Trading Tester
Program to compare stock performance of Senator's transactions vs when the sale is disclosed. Using to find if tracking Senator stock trades is a worthwhile investment strategy: it is.

# Code Explanantion
Calls SenateStockWatcher.com's API to receive an aggregate list of Senator stock transactions. Then uses a for loop to cycle through the stock purchases and calls senator_performance and disclosure_performance functions to find buy prices and current prices of each to calculate performances.

# Conclusions
Senators have a statistically significant overperformance of the market average (~6% yearly). Specific to this program, although Senators overperform vs their diclosure dates, tracking Senator stock purchases from their disclosure dates is a worthwhile investment strategy.

# Author
Cole Cestaro - University of Virginia, Class of 2025

# License
This project is licensed under the MIT License.
