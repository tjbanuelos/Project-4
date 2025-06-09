# MLB_2023-2025
Project 4 Group 6

# Analyzing Baseball Metrics

# The Story

In 2023 Major League Baseball (MLB) installed a new camera system in all 30 of its ballparks to better track the biomechanical markers of its batters.  The point was for clubs and fans to better understand what made a particular hitter “good”. In May 2025 they released further internal data metrics aimed at breaking down the physical characteristics of each batters swing. These include attack angle, attack direction, and swing path (tilt). 
Our goal is to see if we build a model that can correctly predict a hitters offensive production just by using physical characteristic data.

# The Path
We used MatPlotlib to confirm our intitial assmptions about offensive production, then we investigated if we could train a model to cluster hitters using unsupervised machine learning methods and finally we used supervised machine learning techniuqes to build a model to predict OPS based off of a hitters process stats.

# The Data

![image](https://github.com/user-attachments/assets/e69afa03-5c40-44c7-aa84-0c6152e369ca)

the data is from  https://baseballsavant.mlb.com/ where we took individual MLB baseball players and their metrics from 2023 to 2025. 

## Cleaning data
![image](https://github.com/user-attachments/assets/9cd432a2-bef5-4b03-a382-5e5f4473ffb2)

![image](https://github.com/user-attachments/assets/d1835373-d801-4b35-a401-39762cdf05fc)

![image](https://github.com/user-attachments/assets/f79197cd-3151-4a58-bf19-846153b27865)

![image](https://github.com/user-attachments/assets/e6ce791e-413b-4715-b747-e58c20098030)

Cleaning the data by changing column names and droping unneeded colums. Also droping null values.

![image](https://github.com/user-attachments/assets/d2d72d4f-f128-4e1a-adaa-3a641aea1c65)

Clean dataframe above!

# Vizualization 

Of course we made plenty of graphs and chart for you to look at. below is a quick preview.

## Pandas/Matplotlib
![image](https://github.com/user-attachments/assets/6ebfe4a0-e73c-4223-81ae-c98131d6df70)

![image](https://github.com/user-attachments/assets/4be6f60d-e47e-4b20-b48f-c72f2b0f6656)

## Unsupervised learning model
![image](https://github.com/user-attachments/assets/b26f2ef7-0788-490e-9bbf-fdaeb223a68f)

![image](https://github.com/user-attachments/assets/9fac3739-ea1f-44c6-9d6d-60303116e538)

## Supervised learning model
![image](https://github.com/user-attachments/assets/434ff360-b442-4f62-ae03-56171fcb98d0)

![image](https://github.com/user-attachments/assets/96387862-bd3d-4022-91f0-74e3ce6c2990)

![image](https://github.com/user-attachments/assets/705b8519-23b3-4869-9890-3e67c1d8e807)

## Tableau
![image](https://github.com/user-attachments/assets/30dce459-5b13-4cec-b337-d5912fd65760)

![image](https://github.com/user-attachments/assets/b2e60212-512c-4efe-8c31-d01d1b25ac86)



# Conclusion 

After Analyzing are models we found that there are just to many variables to have a definite answer to what key metrics determine a good hitter. But it was very insightfull for what to lookout for!

# Presentation
[Google Slides](https://docs.google.com/presentation/d/1BNH8CO_rQZaWQNqcxG1-oTHkbTcTVgiaTj8rUcKy8hM/edit?usp=sharing)

# Sources

- [![Python 3.7.13](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)]([https://www.python.org/downloads/release/python-3713/) - Programming Language
- [![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/docs/#) - Data maniupulation library
- [![VScode](https://img.shields.io/badge/Vscode-777BB4?style=for-the-badge&logo=VScode&logoColor=white)](https://code.visualstudio.com/) - Integrated development environment 
- [![Sklearn](https://img.shields.io/badge/Sklearn-2C2D72?style=for-the-badge&logo=Scikit&logoColor=white)](https://scikit-learn.org/stable/) - Machine learning
- [![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=plotly&logoColor=white)](https://matplotlib.org/) - Visualization library for plots
- [![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/) - Notebook IDE
- [![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com/) - Data science platform
- [![Google](https://img.shields.io/badge/Google-3776AB?style=for-the-badge&logo=Google&logoColor=white)](https://www.google.com/) - Cloud-based storage and file-syncing service
- [![Seaborn](https://img.shields.io/badge/Seaborn-44A833?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/) - Data visualization
- [![Tableau](https://img.shields.io/badge/Tableau-3670A0?style=for-the-badge&logo=tableau&logoColor=ffdd54)](https://www.tableau.com/) - Data visualization

https://stackoverflow.com/

https://gemini.google.com/app

https://chatgpt.com/

https://baseballsavant.mlb.com/

# Authors 

Cole Sherwin, Tomas Banuelos, Robert Lawrence, Andrew Njogu, Noah Stevenson

