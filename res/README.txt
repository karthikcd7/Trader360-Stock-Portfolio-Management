FEATURES OF THE PROGRAM

* IN THIS ITERATION, WE HAVE IMPLEMENTED
** DOLLAR COST AVERAGING,
** GRAPHICAL USER INTERFACE(GUI) FOR THE APPLICATION.
* THE GUI ENABLES THE USER TO WORK ON FLEXIBLE PORTFOLIO. THE GUI PROVIDES ALL THE FUNCTIONALITY
FOR UPLOADING A FILE, ADDING A PORTFOLIO, EXAMINING A PORTFOLIO, GET THE TOTAL VALUE OF A PORTFOLIO,
BUY STOCK, SELL STOCK, GET THE COST BASIS OF A PORTFOLIO, GET THE PERFORMANCE CHART OF A
PORTFOLIO, CREATE A STRATEGY (DOLLAR COST AVERAGING).
* WE HAVE ALSO ADDED THE BAR CHART IN THE GUI WHERE THE APPLICATION SHOWS A BAR GRAPH TO
SUMMARIZE THE PERFORMANCE OF A PORTFOLIO OVER A SPECIFIC TIME FRAME.

OUR APPLICATION PROVIDES USERS THE OPTION TO CREATE BOTH A FLEXIBLE AND INFLEXIBLE PORTFOLIO.

INFLEXIBLE PORTFOLIO

* Allow a user to create one or more portfolios with shares of one or more stock.
Once created, shares cannot be added or removed from the portfolio.
The above feature has been successfully implemented with keeping in mind of a single user.
In our program, the user can create one or more portfolios by choosing
(option 1 - Enter data as a file: Yes/No : No enter data manually) OR (option 2 - Add a portfolio).
Once a portfolio has been created, user cannot add/remove a stock from it.

* Examine the composition of a portfolio.
The above feature has been successfully implemented. User can examine the composition of
a portfolio by choosing option 3 - Examine a portfolio - which will give a list of user’s
portfolios. From this list, the user can choose a portfolio to examine.  The option will
display the portfolio name (unique), stock details of each stock (stock symbol, stock name,
quantity, purchase date, purchase price).

* Determine the total value of a portfolio on a certain date.
The above feature has been successfully implemented. User can determine the total value of a
portfolio at a desired date by choosing option 4 - Get the total value of a portfolio -
which will give a list of user’s portfolios. From this list, the user can choose a portfolio.
User will be required to enter a date as well. If this date is before 1995/1/1, or in the future,
then user have to re-enter a date since the date is either invalid or not supported.

* Determine the value of a portfolio on a specific date (to be exact, the end of that day).
The value for a portfolio before the date of its first purchase would be 0, since each stock in the
portfolio now was purchased at a specific point in time.

* Save the data which the user has worked on so far.

ADDING TO ALL THE ABOVE FEATURES, THE FLEXIBLE PORTFOLIO HAS THE ADDITIONAL FEATURES
FLEXIBLE PORTFOLIO


In this assignment we have enhanced the features of the stock implementation, added support for
the user to create a strategy.

* Buy Stock
Allow a user to create one or more portfolios with shares of one or more stock. Once created,
shares the user can now add(buy) shares to the portfolio. The user can purchase a
specific number of shares of a specific stock on a specified date, and add them to the portfolio of
their choice. For every transaction the user has to enter a commission fee between 2 and 30 dollars.

* Sell Stock
Allow a user to sell a specific number of shares of a specific stock on a specified date from a
portfolio of the user's choice. For every transaction the user has to enter a commission fee between
2 and 30 dollars.

* Get the cost basis
Determine the cost basis (the total amount of money invested in a portfolio) until a specific date.
This includes all the purchases made in that portfolio till that date and the commission fee paid
for each transaction (buy or sell).

* Get the performance of a portfolio
Show the performance of a portfolio over time. The user can enter the period during which they
wish to see the portfolio's performance. The chart can show the analysis in months, days and years
based on the user choice. The scale used to represent the  asterisks is absolute.
A measure of the portfolio's value at that timestamp is shown by the number of asterisks on each line.
The value is computed at the end of that day if the timestamps are dates. The value is computed on
the final working day of the month if the timestamps are in the form of months. The value is computed
on the final business day of the year, if the timestamp is in years.

* The user can create a strategy inorder to invest money regularly. Details such as the start date,
end date, frequency with which the money should be invested, the total amount for investment,
weight for each stock symbol and so on. The strategy helps the user invest periodically and
keep track of investments.

* Quit



FEATURES YET TO BE IMPROVISED/NOT WORKING FEATURES

1. The application does not support multiple users.
