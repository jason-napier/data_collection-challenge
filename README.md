# data_collection-challenge
Repository for Module 11 Challenge
For this project, information was scraped from websites about Mars, collected into a data structure and analyzed. 

In this repositor are the following files:

*part_1_mars_news.ipynb*
	-The url 'https://static.bc-edx.com/data/web/mars_news/index.html' was scraped. The titles and preview text were extracted. This information was saved to a dictionary in .json format.

*part_2_mars_weather.ipynb*
	-The url https://static.bc-edx.com/data/web/mars_facts/temperature.html was scraped. 
	-The information from the table was stored in a pandas dataframe.
	-The following information was found:
		-Number of months on Mars
		-How many Martian days of data was collected
		-Average low temperature by month was calculated and graphed.
		-Average atmospheric pressure by month was calculated and graphed.
		-Number of Earth days equal to a Martian year were approximation was predicted.

*Mars_Temperature_Data.csv*
	-A .csv file of the dataframe created by scraping data from the table from url https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Other Notes:
-Special thanks to Lucas Ludwig for collaboration on examining Martian year prediction.
-Information is used with permission by and is property of edX and is intended for educational purposes only.
