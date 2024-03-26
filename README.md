# Mars Exploration Web Scraping and Data Analysis Project
Repository for Module 11 Challenge

## Overview

This project is an exploration into the realm of web scraping and data analysis, focusing on gathering and analyzing data about Mars. Utilizing Python, alongside libraries such as Splinter, Beautiful Soup, Pandas, and Matplotlib, this project is split into two distinct parts:

- **Part 1: Mars News Scraping**: Extracts titles and preview text from Mars news articles.
- **Part 2: Mars Weather Data Analysis**: Scrapes and analyzes Mars weather data, focusing on temperature and atmospheric pressure.

## Repository Structure

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

## Tools and Libraries Used

- **Python**: The core programming language used for this project.
- **Splinter**: Automated web browser interaction for scraping.
- **Beautiful Soup**: HTML parsing and scraping.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.

## Getting Started

### Dependencies

Ensure you have Python 3.x installed along with Jupyter Notebooks. The project's dependencies can be installed using:

pip install pandas matplotlib beautifulsoup4 splinter

## Conclusion
This project showcases the power of web scraping for data collection and the effectiveness of Python libraries for data analysis and visualization. Through careful examination of Mars news and weather data, we gain fascinating insights into the red planet's climate and how it compares to Earth's.

## Notes
- Special thanks to Lucas Ludwig for collaboration on examining Martian year prediction.
- Information is used with permission by and is property of edX and is intended for educational purposes only.

## References
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
