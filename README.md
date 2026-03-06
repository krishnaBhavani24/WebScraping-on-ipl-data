# IPL Auction Data Web Scraping

## Project Overview

This project demonstrates how to collect and analyze data from the IPL auction website using web scraping techniques in Python. The script extracts team information from the IPL 2022 auction page and converts it into a structured dataset for further analysis.

## Objective

* Scrape IPL auction data from the official IPL website.
* Extract important details such as teams, funds remaining, overseas players, and total players.
* Convert the scraped data into a structured format using Pandas.
* Save the dataset as a CSV file for further analysis.

## Data Source

Data is scraped from the official IPL auction webpage of the Indian Premier League.

Website used: https://www.iplt20.com/auction/2022

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook / Google Colab

## Project Workflow

1. Send a request to the IPL auction webpage using the Requests library.
2. Parse the HTML content using BeautifulSoup.
3. Locate the auction table containing team details.
4. Extract column headers and table data.
5. Store the extracted data into a Pandas DataFrame.
6. Export the final dataset to a CSV file.

## Dataset Fields

The dataset generated from scraping contains the following columns:

* SR.NO – Serial number of the team
* TEAM – Name of the IPL team
* FUNDS REMAINING – Remaining auction budget
* OVERSEAS PLAYERS – Number of overseas players in the team
* TOTAL PLAYERS – Total players in the squad

## Output

The scraped data is saved as:

IPL_Auction_2022.csv

This dataset can be used for further analysis and visualization of team budgets and squad composition in the IPL auction.

## Conclusion

This project shows how web scraping can be used to collect sports data automatically from websites. The extracted data can help analyze team spending patterns and player distribution in the IPL auction.
