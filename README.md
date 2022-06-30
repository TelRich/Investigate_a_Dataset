# Investigate a Dataset
Project 1 in ALX-T Data Analyst Nanodegree Program, Udacity.

## Project Overview
![The Movie Database Image](https://miro.medium.com/max/400/1*Y9-6_bh5a00rJWWoQ28NMQ.jpeg)

I analyzed the dataset (The Movie Database [TDMB]) and then communicated my findings. I used Python libraries Numpy, Pandas, and Matplotlib to make my analysis easier.
Hundreds of movies are released every year, but not all are profitable. The aim is to bring out insights from the TDMB dataset.

## Dataset
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time. The original document can be found on [Kaggle](https://www.google.com/url?q=https://www.kaggle.com/tmdb/tmdb-movie-metadata&sa=D&source=editors&ust=1656566257093142&usg=AOvVaw1I3RfpyO-4WYJVEai_SRwu)

## Package Required
* Pandas
* Numpy
* Matplotlib
* csv

## Summary of Investigation
>The analysis above has given us a lot of insight about the TMDb dataset. Below is a brief summary and a keypoint to note.

>1. As seen in the distribution of data, the vote average has a bell-shape which shows normal distribution. Budget,profit and revenue are skewed right.
>
>2. The popularity of movie has been increasing over the years but it seems the rating is decreasing.
>
>3. We can see that the popularity of a movie is not by how big the number of vote is or the rating.
>
>4. Movie with high profit falls within the rating of 6 to 8
>
>5. _**June**_ and _**December**_ is the month with most popular movies, but why is that? could it be because of the amount of movies produce in that month? Further analysis can be carried out to count popularity for each month and see if its because of how many movies was produced.
>
>6. _**Drama**_ is the most popular genre followed by Action genre.
>
>7. _**Avatar**_ is the movie with highest profit and revenue. _**The Warrior's Way**_ has the highest budget, yet its the movie with the least profit.
>
>8. _**The Karate Kid, Part II**_ did not have the highest budget, revenue or profit but it generated the highest ROI. 
>
>9. Based on the visualization madee, we find that profit made from a movie is not dependent on the budget for the movie, but profit has a positive correlation. 
>
>10. _**June**_ and _**December**_ is the month with the highest profit but further analysis showed that this is not dependent on the number of profit (count of movie) made in that month. September has the has the most number of movies produced.

**Limitation**
> This analysis was done based on assuption that the currency is in dollars, because the dataset did not specify which currency. Also some movies could have been produced in different countries and this would mean havig budget and revenue of different curencies. Also while making the analysis some rows were dropped, such as that of revenue and budget which affected the analysis.
