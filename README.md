# Amazon-Scraper
A simple Amazon Scraper to extract product  and prices from Amazon.it using Node.js.

Features
Extract product data from the search result(by category, by country)
Extract lots of signle product data by using ASIN id
Extract product reviews data by using ASIN id
Extract list of categories
Is supporting all available Amazon Marketplaces
Sort result by sponsored products only
Sorts result by discounted products only
Result can be saved to the JSON/CSV files
You can scrape up to 500 produtcs and 1000 reviews





# Usage
From a terminal

Clone this project git clone https://github.com/Chry1911/Amazon-Scraper.git and cd into it cd amazon-scraper
When you are ready, you have to download node from here https://nodejs.org/it/ and install it.
Next you need to install https://www.apachefriends.org/it/index.html to have your server in localhost.

When you have setted node and xampp, you need to clone this project into the directory ---> xampp/htdocs/your project folder
and then open a command prompt with Admin privileges and execute:
- node amazon.js 
this launch a program with node js that extract some datas and create json files into a folder.

To show the result of the web scraping, in the same folder if you launch this website: https://localhost/yourwebsitename/scraped.html
you can see the scraped object from amazon in a web HTML table.



# Donation
if you like the project and you want to personalize it and use it for other things here, a donation to help me in improvements


[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?business=cortesechristian%40hotmail.com&item_name=Donazione+volontaria&currency_code=EUR)
