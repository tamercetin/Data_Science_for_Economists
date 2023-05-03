****************************************************************
Prepared for Gabor's Data Analysis

Data Analysis for Business, Economics, and Policy
 by Gabor Bekes and  Gabor Kezdi
 Cambridge University Press 2021
 gabors-data-analysis.com 

Description of the 
case-shiller-la dataset

used in case study 18B Forecasting a home price index

****************************************************************
Data source

All data is downloaded from the FRED
(Feredeal Reserve Economic Data) website maintained by the Federal Reserve Bank of St Louis (USA)
Easiest is to use their API (need to get a key and copy it into your code)
Or you can search for variables and download them as xls or csv


****************************************************************
Data access and copyright

You can use this dataset for educational purposes


****************************************************************
Raw data tables

ts_houseprices_2019
 monthly time series of the Case-Shiller home price index 
	in Los Angeles, CA and New York, NY, and a few other variables
 starting with Jan 1987
 end depends on when you download the data
 ID variables 	datestr	string date (1st day of month in "year-month-day" format)
 important vars	LXXRSA 	S&P/Case-Shiller CA-Los Angeles Home Price Index, seasonally adjusted
		LXXENSA S&P/Case-Shiller CA-Los Angeles Home Price Index, not seasonally adjusted
		CANA 	All Employees: Total Nonfarm in California, thousand, seasonally adjusted
		CANAN 	All Employees: Total Nonfarm in California, thousand, not seasonally adjusted
		CAUR 	Unemployment Rate in California, percent, seasonally adjusted
		CAURN 	Unemployment Rate in California, percent, not seasonally adjusted

****************************************************************
Tidy data table

homeprices-data-2000-2018.csv
 monthly time series of the Case-Shiller home price index 
	in Los Angeles, CA and New York, NY, and a few other variables
 2000-2018
 ID variables 	date
		year
		month
 important vars	ps 	S&P/Case-Shiller CA-Los Angeles Home Price Index, seasonally adjusted
		pn	 S&P/Case-Shiller CA-Los Angeles Home Price Index, not seasonally adjusted
		us 	All Employees: Total Nonfarm in California, thousand, seasonally adjusted
		un 	All Employees: Total Nonfarm in California, thousand, not seasonally adjusted
		emps 	Unemployment Rate in California, percent, seasonally adjusted
		empn 	Unemployment Rate in California, percent, not seasonally adjusted

