# Analysis in the correlation between different movie attributes
Original dataset by Daniel Grijalva: [Link to dataset](https://www.kaggle.com/datasets/danielgrijalvas/movies)
## Overview

The dataset includes a variety of information on 7,668 different movies with attributes such as genre, country produced, release date, gross revenue, production budget, IMDb score, number of votes and total runtime. The release dates of the movies ranges from 1980 to 2020. The data was scraped from IMDb.

An analysis is conducted on the data to look for the strength of correlation among different movie variables. A correlation coefficient that is greater than **0.5** will be
considered to be a significant relationship. 

## Findings

The results of a correlation test reveals that there is a high correlative relationship between budget and gross revenue as well as votes and gross revenue with 
correlation coefficients of **0.74** and **0.61** respectively. In contrast, the coefficient between score and year, runtime and year, and score and budget all fell below the **0.1** mark. The only result that seemed the most suprising to me was the low correlative relatioship between score and budget which I had initially assumed would result in a significantly higher coefficient than it actually did. 

This indicates that despite high film budgets correlating to higher gross revenue, a high budget does not have the same positive relationship for a film's IMDb score.
___________________________________________________
![Annotation 2023-07-01 104648](https://github.com/dylanhjiang/MovieFactorsCorrelation/assets/137730071/55590c35-581e-41ab-96b6-5c972c374637)
