# Box-Office-Analysis

The Aim of this Project is to:

1.	Produce interactive data visualizations with Plotly Python.
2.	Use Plotly Python and Seaborn during EDA and feature engineering.
The TMDB data set used in this project contains 7400 movies and a variety of metadata. The data is derived from https://www.themoviedb.org/ . The data train and test file can be found on Kaggle.

## Visualizing the Target Distribution
To proceed to feature analysis, the distribution of movie revenues and budget is plotted. To illustrate the skew, the distribution of revenue and budget on a logarithmic scale using np.log1p is also plotted
It is identified that the release_date column can be a ripe for feature engineering. Using different EDAs

## Pre-processing
a standard datetime format is created and filling in missing values and also new feature columns for the year, weekday, month, week of the year, day, and quarter are created

## Visualisation
Plotly was used to create an interactive visualization of the number of films released per year in both the training and test sets.
the number of films and total revenue per year is visualised, and the number of films vs the average revenue per year.


## The questions that were asked for the EDA are as follows:

Do release days impact revenue?
Is it reasonable to assume that movies released on weekends will gross higher revenues?
Is there any Relationship between Runtime and Revenue?
Do official homepages impact revenue?
What is the distribution of languages across films?
What are the common words in film titles and descriptions?
Can we identify trends across movie titles and descriptions and their effect on revenue?
How do film descriptions impact revenue?





