### CCPG Project Scraper

This code is used to scrape China’s CCGP website to get data on private sector participation contracts in the water industry.

**Task**: Initially, a list of potential contracts was presented in a csv file with the task of searching for these on the CCGP website to confirm existence. A follow up task was then set to use a web scraper to get information about the contracts including its length, cost, type, and a summary of activities.

**Functionality**: Inadequate and unpredictable navigation of the site meant it was much easier to use Bing to indirectly search the site. This is the purpose of bing_scrape.ipynb. For this I combined Bing’s site search function with the Python Beautiful Soup library, storing it in a Pandas dataframe and then outputting as a csv. 

When the second task was set I used created a second code, second_china_scrape.ipynb. This imports the Bing data from the csv and uses Beautiful Soup to visit each page on the CCGP site to scrape data. Given the data is in a standard table format for each contract, it was easy to grab more than enough information. Again, storing this in a dataframe and exporting to csv format. The task was a success, with the data cleaned and manipulated in Excel by analysts and used for updating various company databases.

