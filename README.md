Movies Dataset

This project contains a dataset of movies, including various details like titles, genres, ratings, and more. It can be used for data analysis, visualization, and machine learning practice.

 File Included

- movies 2.csv`: The main dataset file containing information about movies.

Columns Description

Title`: Name of the movie
- Genre`: Genre(s) of the movie
- Year`: Release year
- Rating`: Viewer rating
- Duration`: Duration of the movie in minutes
- Director`: Movie director
- Votes`: Number of IMDb votes

Use Cases
- Analyze movie trends by year or genre
- Visualize data with charts and graphs

- Sample Code for Analysis
 Load the Data
```python
import pandas as pd
import seaborn as sns
import numpy as np


import matplotlib
import matplotlib.pyplot as plt
plt.style.use('ggplot')
from matplotlib.pyplot import figure

%matplotlib inline
matplotlib.rcParams['figure.figsize'] = (12,8) #Adjusts the configuration of the plots we will create


#Read the Data
df = pd.read_csv('movies.csv')

  
