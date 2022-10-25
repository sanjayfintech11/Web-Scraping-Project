# Web-Scraping-Project
- Scraping of Crypto Coins on Cryptocompare using Python &amp; Selenium
- Scraping of Crypto Coins on Cryptocompare using Python & Selenium
- Using Python, Requests and Selenium- Extracting the details of top 100 crypto assets from each category based on their Market Capitalization from the website Cryptocompare

# Objectives of the project:
- We are going to scrape https://www.cryptocompare.com/coins/list/all/USD/1
- We will get a list of Coins from each tab of Crypto assets.
- For each coin, We will get Ranking, Coin name, Coin URL, Price, Direct Volume, Total Volume, Top-Tier Volume, Market Cap, Rating and % Chg.
- We will return all the extracted values into a dictionary and then to create a data frame.
- From Data Frame, we will create a CSV file format
![image](https://user-images.githubusercontent.com/85775960/197727907-7e18bb76-9542-4897-9c87-0b0f6a4c1c51.png)

# Overview Description of the Project
- Scraped Cryptocompare Website. We used Python, libraries such as Requests, Selenium, and Pandas to extract the details for this project.
- The project scrapes the list of 100 cryptocurrencies from each tab of the page and provides details like Rank, Name, URL and Price in USD, Market cap, Volume, and Rating.
- Parsed all the scraped data into a data frame and hence stored it in a CSV file containing 277 rows and 11 columns.

# Summary
- We used Python, libraries such as Requests and Selenium to extract the details for this project.
- The project scrapes the list of 100 cryptocurrencies from each tab of the page from Cryptocompare and provides details like Rank, Name, URL and Price in USD, Market cap, Volume, and Rating.
- Parsed all the scraped data into a data frame and hence stored into a csv file containing 277 rows and 11 columns.

# Future work
- Code optimization
- Improving the documentation part of the project
- Adding a time and date stamp at the point when website's page is requested and adding it to the output, as the web page is dynamic and frequently changes values.
- Web Scraping the website Cryptocompare using REST API as the website provides free API. https://min-api.cryptocompare.com/
- We can also extract more details out of a coin by accessing the coin_url from each tab, going forward
