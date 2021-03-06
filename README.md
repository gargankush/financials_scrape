# financials_scrape

This code will allow you to pull the last 5 years of financials from any stock on Reuters and perform fundamental analysis based on the data.

First, enter the stock ticker of the company you would like to analyze. This is not case-sensitive. It is highly recommended that you find the stock on Reuters first. Usually in the URL the stocks will have the ticker, a period, then another abbreviation based on the stock exchange. As an example, if you find Microsoft on Reuters, you will see that in the URL it is displayed as MSFT.OQ. This means the first parameter for the program would be 'MSFT', and the second parameter would be 'OQ'.

Analysis is performed on a 1-10 basis. A rating above 7.5 is considered a Buy, a rating below 5 is considered a sell, and anything in between is a hold. It is based on a portfolio of 15 different ratios used to guage the fundamental financial well being of a company. The final rating is a mean of the grades of each of these 15 ratios.
