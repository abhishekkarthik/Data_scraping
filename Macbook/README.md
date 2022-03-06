Contains details of all the Apple Macbook products available in flipkart.com
Link: https://www.flipkart.com/laptops/pr?sid=6bo%2Cb5g&fm=neo%2Fmerchandising&iid=M_8b3b3f65-7ceb-4375-912c-d2bcdde87c58_1_372UD5BXDFYS_MC.34WHNYFH5V2Y&otracker1=hp_rich_navigation_PINNED_neo%2Fmerchandising_NA_NAV_EXPANDABLE_navigationCard_cc_13_L1_view-all&cid=34WHNYFH5V2Y&p%5B%5D=facets.brand%255B%255D%3DAPPLE&otracker=clp_metro_expandable_6_26.metroExpandable.METRO_EXPANDABLE_Apple_laptops-store_SKIHMOPFPDC3_wp9&fm=neo%2Fmerchandising&iid=M_b4d0e2ef-aaac-4e7e-9272-9b8be53c2dc5_26.SKIHMOPFPDC3&ppt=clp&ppn=laptops-store&ssid=j5fwd6niaz0hnchs1645514684273

Brief procedure on how data was scraped:
-	Importing the required packages, changing directory to webdriver file location.
-	Accessing the html code of the webpage remotely by using selenium webdriver and BeautifulSoup from bs4 package. 
-	Scraping the product names
-	Scraping the product prices and converting them to “int” datatype.
-	Scraping the product ratings and converting them to “float” datatype.
-	Scraping the total number of ratings & total number of reviews converting them to “int” datatype.
-	Scraping the product specifications as a list.
-	Creating a dataframe with the scraped data.
-	Defining a function which returns the dataframe.
-	Create dataframe containing details from all pages (i.e. 2 pages).
-	Creating a csv file with the dataframe.
