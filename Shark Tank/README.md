Contains details of the offers for all the enterpreneurs who participated in the show "Shark Tank India".
Link: https://www.serialupdates.me/shark-tank-india-investors-names-sony-tv-new-show-entrepreneurs-list/

Brief procedure on how data was scraped - 
-	Importing the required packages, changing directory to webdriver file location.
-	Accessing the html code of the webpage remotely by using selenium webdriver and BeautifulSoup from bs4 package. 
-	Scraping the table headers and table body from the html code.
-	Creating a dataframe using the scraped table headers and table body.
-	Defining a function which returns the dataframe.
-	Creating a csv file with the dataframe.
