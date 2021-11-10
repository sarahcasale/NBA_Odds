# NBA_Odds

To run the scraper you have to do it through jupyter notebook.
The jupyter notebook installation instructions can be found here: https://jupyter.org/install

The only other thing you'll have to change is the path to where the excel file should be saved.
This can be found where the writer variable is initialized near of the bottom of the the nba_odds() function definition.
--> writer = pd.ExcelWriter(r'/Users/sarahcasale/Documents/NBA Odds/Scraped Data/' + dt.strftime('%b-%d-%Y') + '_nba_data' + '.xlsx')
Make sure you keep the r and just replace the '/Users/sarahcasale/Documents/NBA Odds/Scraped Data/' with your own folder path. 
