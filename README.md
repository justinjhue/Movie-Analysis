# Movie-Analysis
Phase 1 Project Templates and Examples
# Title

**Authors**: Justin Hue

## Overview

This notebook will dive into which successful films a business interested in creating original movies should look into emulating. This notebook will give insight into what genres of films are most successful, what kinds of films are the highest rated, as well as which of the top films of the last decade are the highest grossing. With this information, a business would have actionable, tangible insights that they will be able to put to use in a multitude of ways.

## Business Problem

***
* I needed to find the films doing the best in the box and turn them into actionable insights for a company looking to get into the movie business. I chose the questions that I did based off of the data I had access to, and the solutions I thought I could provide with that information. These are important questions because they are crucial to a business finding their footing in the business.
***

## Data

Describe the data being used for this project.

***
We have 2 tables from IMDB, which include basic information about each title as well as the ratings each film received, as well as the amount of votes casted to rate each film.
This data represents the most successful movies over a recent time period (about the last 10 years).
The target variable here is the average rating of the movies cross-referenced with the number of votes the films received. We want to make sure the movie was well received by a large audience.
***

## Methods

***
* Were there variables you dropped or created? I wanted to isolate a few key variables in the dataset: the most popular genres, studios, and highest rated movies. I removed the duplicate movies, and only used values for domestic gross, getting rid of foreign gross.
***

## Results
***
* I personally believe these results yield actionable information that can be used to get a foot into the movie business as a major player. 
* Out of the top 10 studios, Disney(BV) makes the most domestic gross on average.
* I recommend Microsoft mimic Disney's business practices as much as possible. This includes collaborating with the actors, directors, and producers a part of their most successful titles.
* Out of the list of genres, Animation, Sci-Fi, and Adventure make up the greatest revenue across all titles collectively. If the end goal is maximum gross, I recommend creating titles in, at minimum, one of these three genres.
* Based off of my data, there is no direct correlation between the rating of a movie and gross.
***

### Visual 1
![graph1](https://github.com/justinjhue/Movie-Analysis/blob/template-mvp/images/gross_rating_scatter.png)

## Conclusions

*** 
* My analysis may not completely solve the business problems because there are multiple additional factors not completely taken into account, such as budget size, which cast and crew generate the most revenue consistently, which months are most popular for movies, as well as the fact that my data is mainly from one source, which most greatly impacts the reviews.

In order to improve this project in the future, I could use more data from more sources to create a greater pool of information used to answer more questions and give more suggestions.
***

## For More Information

Please review our full analysis in [my Jupyter Notebook](./Movie-Analysis.ipynb) or my [presentation](https://github.com/justinjhue/Movie-Analysis/blob/template-mvp/Slides%20Edit%20PDF.pdf).

For any additional questions, please contact **Justin Hue | justinhccnm@outlook.com**

## Repository Structure

```
├── README.md                           <- The top-level README for reviewers of this project
├── Movie-Analysis.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── Movie Analysis Project Slides.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
