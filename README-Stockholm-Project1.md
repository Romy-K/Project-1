# Netflix Local Strategy - Project 1

## Description

We saw a lot of Netflix datasets and figured that would be an interesting topic. We decided on the question: what country should Netflix invest in and what should they focus on to gain subscribers? 

First, we used 2 datasets to figure out which country to focus on. One dataset shows the number of Netflix subscribers per country where Netflix is currently available. The other dataset is world population per country. We merged these datasets to get to a subscriber rate; the percentage of people in a country that is subscribed to Netflix. 

There is a clear winner here: India has a huge amount of people and only a small percentage of them is subscribed to Netflix. So we decided to focus on India. 

So, after we decided to focus on the India, we wanted to find information about the revenue from Netflix streaming there(and all over the world). It’s important to show the potential, so the stakeholders could make the right decision about investing in content creation.
We found the dataset, that represents the revenue in each region:
UACN : United States and Canada
EMEA : Europe, Middle East and Africa
APAC : Asia-Pacific (Our focus)
LATM : Latin America

Then we wanted to display the revenue growth in our focus area (APAC).
Also, we wanted to highlight the forecast of possible revenue for Netflix, if they will decide to expand their content creation for India, based on the revenue growth from 2019-2024. Forecast shows us revenue growth for 2025-2027.

We then wanted to figure out: what do the people in India like to watch? So we used a dataset that shows the weekly top 10 of most viewed movies and TV shows per country from 2021 to 2023. 
We dropped all of the other countries and looked at India. Then we used value counts to see which movies and TV shows were in the top 10 most frequently, and created an overarching top 10 for movies and TV shows. 

## Getting Started

### Dependencies

Iryna: MacOS, VSCode, Google Collab, Gihub.
Romy: MacOS, Jupyter Notebook, Google Collab, Github. 
Libraries: panda as pd, seaborn as sns, statsmodels.tsa.statespace., sarimax  SARIMAX, matplotlib.pyplot as plt, numpy as np, from collections import Counter, import tmdbsimple as tmdb.
For Google Drive files:
from google.colab import drive
drive.mount(‘/content/drive’)


### Executing program

You can run all the cells in Google Collab, or just download .ipynb file, open it in your Jupiter Notebook or VS Code, and run all the cells there.
But if you want to run the code from Google Collabs, you should apply the code to get the access to the files on Google Drive.

## Presentation
https://docs.google.com/presentation/d/14Pv-pNndVos2e0LziXR-CsuJZFx4g_oTxARTdlTn67I/edit#slide=id.g33aa774f291_0_503

## Trello
https://trello.com/b/ZKvzTP8J/stockholm-board-project-1

## Authors

Iryna Oleinikova
oleyinikovairyna@gmal.com

Romy Koreman 
mmmpaper1@gmail.com


## Acknowledgments

Inspiration, code snippets, etc.
https://www.kaggle.com/datasets/octopusteam/full-netflix-dataset ;
https://www.kaggle.com/datasets/prasertk/netflix-subscription-price-in-different-countries ;
https://www.kaggle.com/datasets/henryshan/netflix-stock-price ;
https://www.kaggle.com/datasets/jatinthakur706/most-watched-netflix-original-shows-tv-time ;
https://www.kaggle.com/code/eward96/netflix-recommendation-engine ;
https://www.kaggle.com/datasets/sujaykapadnis/official-netflix-streaming-data ;
https://www.kaggle.com/datasets/davidpbriggs/most-popular-netflix-shows ;
https://paperswithcode.com/dataset/imdb-movie-reviews ;
https://surfshark.com/best-rated-netflix-shows-and-movies ;
https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data/data ;
https://www.kaggle.com/datasets/evanschreiner/genres ;
https://www.census.gov/ ;
https://www.ons.gov.uk/ ;
https://www.statcan.gc.ca/ ;
https://www.abs.gov.au/ ;
https://ec.europa.eu/eurostat ;
https://www.ine.es/en/index.htm ;
https://www.cbs.nl/en-gb ;
https://www.data.gov.in/ - Open Goverment Data Platform India;