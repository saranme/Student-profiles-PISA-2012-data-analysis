# Student profiles _PISA 2012_ data analysis.

## Intro
This is a **student project** from the **Udacity Nanodegree "Data Analyst"**.
The goal of this project is to demonstrate the importance and value of data visualization techniques in the data analysis process in the exploratory and explanatory process.

#### Concepts to understand better when I am going to use data visualization:
- Exploratory data visualization: occurs during and after the data wrangling process. Is the main method to understand the patterns and relationships present in your data.
- Explanatory data visualization: after generating your findings, these visualizations help communicate the results.

#### Documents I received to explore the dataset:
- Dataset: _PISA 2012_ dataset, download [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip).
- Dataset dictionary, download [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv).
- Resources I used to know more about _PISA_ test: [pisaprodocuts](http://www.oecd.org/pisa/pisaproducts/) and [pisa_technical_report](http://docplayer.net/26487481-Pisa-2012-technical-report.html).

## Dataset relevant info
#### _PISA 2012_ dataset info:
I wanted to know the student profiles that took the PISA 2012 test.

_PISA 2012_ data has the tests of 485,490 student representatives from 64 countries. 635 variables are evaluated.
The variables I chose to analyze are the type of population (native or emigrant), countries, scores, wealth and truancy.

#### Main Feature of interest to investigate:
- Which continents and countries have the best and worst educational level?
- Immigrant students have a worse educational and social level than native students?
- Is absenteeism related to a worse educational and social level?
- Is wealth related to a better educational level?

#### Main findings I got from my exploratory data analysis:
- Scores are strong correlated: the higher a student's math score, the better the student's science or reading score.
- First Generation of immigrants is the type with the lowest scores in all the subjects while Natives are the type with the highest scores in Reading and Science.
- Immigrants observe 20% more differences between Host and Heritage Cultures than Natives.
- Asia has the top and 3 of the lowest scored countires.
- Most countries with fewer scores have less wealth.
- Natives have a longer poverty interval than immigrants.
- The greater the truancy, there is a small correlation with less wealth and a clear relationship with a lower score among immigrants.
- Scores are negative correlated with truancy.
- The smallest difference in scores between natives and immigrants occurs among those who skip classes once or twice.

#### My analysis documentation:
- **pisa_exploratory_data_analysis.ipynb** (**and** its **html version**) exploration of dataset using Python visualization libraries. 
Starting from plots of single variables and building up to plots of multiple variables.
- **pisa_slide_deck_ppt.html** (**and** its **ipynb version**) is a short presentation that illustrates relationships and properties that I discovered in the dataset.
- **pisa_slide_deck_presentation.ipynb** is another kind of presentation illustrating the same as pisa_slide_deck.html.
- **output-toggle.tpl** file to be able to create the pisa_slide_deck_ppt.html version.
