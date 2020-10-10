readme.md


## Overview
This project aims to use linear regression to predict a movie's lifetime gross earnings.


## Web-scraping movie data
Data for 3363 movies were scraped from BoxOfficeMojo.com using BeautifulSoup. These data include distribution studio, opening weekend earnings, budget, release date, MPAA rating, runtime, genre, and domestic earnings. Python code for webscraping is in: Scrape_Top_Movies.ipynb

## Formatting data and linear modeling
Data were cleaned and formatted to produce linear models with scikit-learn and statsmodels. Different models were created to assess the impact of feature interactions and polynomial features on model performance. Models built on these feature combinations were assessed using consecutive train/test splits to identify changes in R^2, and LassoCV regularization was used to further optimize models via feature exclusion. Python code for formatting and modeling is in: Linear_Regression.ipynb
