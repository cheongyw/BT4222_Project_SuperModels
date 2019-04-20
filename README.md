# BT4222_Project_SuperModels
Github Repo for BT4222 Group Project - Cheong Yi Wei, Chua Wei Han, Ng Gin Wen, Yang Xiya

# Pre-Requisites
Python 3 is used for this project. Most of the libraries used are installed in colab. Please refer to requirements.txt for details. Furthermore, the default pandas library on colab is outdated. Please upgrade it before using pickle to load the data files found in the link below.

# Description
### Data Sources
- The news data and market data came from the [Two Sigma Kaggle Competition](https://www.kaggle.com/c/two-sigma-financial-news).
- Webscraping is done across multiple website which includes [Thomson Reuters](https://www.reuters.com/), [Yahoo Finance](https://sg.finance.yahoo.com/), [U.S. Securities and Exchange Commission (SEC)](https://www.sec.gov/edgar/searchedgar/companysearch.html) and [FINVIZ](https://finviz.com/) as in ```Web-Scraping.ipynb```.
- The industry data that were obtained from web scraping and cleaning can be found [here](https://drive.google.com/open?id=1IxKUUlggh1aX-maK3kyqYL3_9kxTrGif).
### Data Preprocessing
- Clusters and standardised features were produced as in ```Generate-Standardised-Features.ipynb```.
- Word vectors were produced as in ```DNN_(2_April_Running_Version).ipynb```.
### Model
- For ensemble model predictions, run ```Ensemble_Model.ipynb```.
### Google Drive Link
- Please go to [this link](https://drive.google.com/open?id=1LojN4W8IFENp87j3Csb0DbF30hUF8Z9G) to access the data and raw notebooks
