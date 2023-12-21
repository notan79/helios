Project: Helios
Author: Nathan Crutchfield
Purpose: Collect data of colleges to create a database of the important information that is a 
factor in college decisions. Ultimately going to be turned into website. 
Folders: 'og_data': Holds csv files that were relevant at some point, whether it was from web
            scraping or just transitioning between days of data collecting. 
         'main_data': Holds the csv files that will be used for the final website
Files: 'formatting_gov_data.ipynb': Used to format the data of the csv file from 'gov_data.ipynb'
       'gov_data.ipynb': Uses the College scorecard API to write a csv file with the data
       'web_scrape.ipynb': Uses website data to collect info about colleges. Not used in the 
          main csv files. May come into use later. This data is written to og_data files 'info'
          and combined into COPY_OF_DATA.csv
