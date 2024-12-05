This repository consists of:
- House price data extraction and cleaning - 'housing-data-EDA' folder.
- Green space data analysis - 'green-spaces' folder.
- Transit station data analysis -'TTC_Files' folder.
- Safe injection sites and needle dropbox location data analysis - 'Injection-Site-EDA' folder.

The house price data is the base of all the analyses as all factors are being assessed against house prices. Outputs and codes from these notebooks were used in the notebooks for each factor analysis.

This house price data is located in the main repository and the relevant files have been copied to each sub folder for the different factors affecting house prices.

Each notebook in this repository conducts exploratory data analysis on the various factors affecting house prices and generates relevant output. 

The notebook(s) for each folder are:
- housing-data-EDA: Four notebooks independent of each other - Housing_Combined.ipynb; Municipal_Json_Mapping.ipynb; Selenium_Zillow.ipynb; Ward_Map.ipynb

- green-spaces: green-space-analysis.ipynb

- TTC_Files: TTC_Lines.ipynb

- Injection-sites: Two notebooks which need to be run in order -1) City of Toronto SIS and NDB Locations Web Scraping.ipynb and 2) Injection Site EDA.ipynb
                 
The notebooks would be able to run without issue as all required files being called are located within the same sub folder. 

This exploratory data analysis is discussed in the following medium article:
'Analyzing Possible Factors Affecting Housing Prices in Toronto Using Exploratory Data Analysis' - https://medium.com/@antonio.tripodi/a6273111b1a6 
