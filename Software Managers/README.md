Contains details of Interviews with Software Managers who transitioned from development to management from devtomanager.com
Link: https://devtomanager.com/interviews/

Brief procedure on how data was scraped-
-	Importing the required packages, changing directory to webdriver file location.
-	Accessing the html code of the webpage remotely by using selenium webdriver and BeautifulSoup from bs4 package. 
-	Scraping the employee names, job position, company and interview quotes.
-	Scraping the dates and converting them to datetime format.
-	Scraping the tags as a list.
-	Creating a dataframe with the scraped data.
-	Defining a function which returns the dataframe.
-	Creating a  dataframe containing details from first 5 pages.
-	Creating a csv file with the dataframe.
