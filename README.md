Project goal was to build a model to predict LIX-number of the articles.
1. three web-sources were scrapped:
	1.1. TV2 - majority of data.
			Data stored: isds2023_group31/Data/TV2_raw
			Scrapping code: isds2023_group31/codes/data scraping/ Eksamen-Test_New_New.ipynb and TV2-...
	1.2  DR
			Data stored: isds2023_group31/Data/FINAL_dr_articles.csv
			Scrapping code: isds2023_group31/codes/data scraping/ DR_scraping and cleaning.ipynb
	1.3. Extrabladet
			Data stored: 
			a) isds2023_group31/Data/extrabladet_all_urls_18082023_2029.csv
         (list of scrapped urls of single articles to scrap 5 main fields)
			b) isds2023_group31/Data/final_extrabladet_1732articles.csv
         (scrapped data of 5 fields: author, title, body, time, category)
			c) isds2023_group31/Data/ekstrabladet_withgenderlix.csv
         (structured data, new columns calculated based on 5 main fields)
			Scrapping code: isds2023_group31/codes/data scraping/extabladet_scraping_Elena.ipynb
3. data was cleaned, structured and variables calculated. Data distribution plots created.
			Code: isds2023_group31/codes/data_structuring_cleaning/
			Support info to derive model variables: List of names to define gender based on author name:
           isds2023_group31/Data/Name_Boy.xlsx , isds2023_group31/Data/Name_Girl.xlsx 
			Data for modelling: isds2023_group31/Data/TV2_FINAL,
           isds2023_group31/Data/FINAL_dr_articles.csv, isds2023_group31/Data/ekstrabladet_withgenderlix.csv
3.Modelling and Validation
	    isds2023_group31/codes/modeling/Model_Ny_Ny_Ny_Ny.ipynb (final version of code)			
