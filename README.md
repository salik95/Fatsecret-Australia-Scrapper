# Fatsecret-Australia-Scrapper
The scraper is written using Python Selenium Chromedriver.

The you need to have python 3 installed and all the other dependencies like chrome webdriver and bs4.

First part of the script collects data of all the brand name URLs alphabetically and prints the URL recorded alphabetically on console. That data can be copy pasted anywhere for extended usage. It is already copy pasted in the script to be used in later part of the script.

Then the second part of the script collects data of every individual product in the brand and dumps in a json file named "brand_products_data.json".

Then in the third part of the script, the data is read from "brand_products_data.json" and organised in a list with brand name, product name, and the URL and store it in json file with name "brand_data_list.json".

In the last part of the script, the data is read from "brand_data_list.json" and is scraped via the URL, structured and stored in a final CSV file with name "data.csv".
