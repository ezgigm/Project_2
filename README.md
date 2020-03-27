# Project_2The Sale Price Of Houses
The Goal: The goal of this project is to predict the the sale price of homes based off of the zip code the home is located in.

The Problem:

During our daily commute we tend to drive past homes that are either appealing to the eye or homes that just need a bit of work. After that moment of admiration or of making plans on how you would fix up a home, you drive on and forget about it.

But what if you didn't forget about it, what if you actually followed through with your idea and bought a brand new home, or even a fixer upper? Where would you even begin to bring such a thought to life? Most importantly, how much would it be to make it happen?

Once those questions are answered you will see that the more research you do the more the prices vary depending on the area you decide to purchase in. Not to mention the other factors that play a role in a homes price i.e. water front view and a basement. So now the price you had set for a budget begins to increase due to the lack of knowledge when looking into the value of the home you want to purchase.

The Solution:

Here at DS Borg Homes our team has spent the last year developing a model that will be able to tell how much a home is actually worth by just simply typing in the zip code! Voilà!! No more long nights of scouring through papers, websites, or phone numbers trying to find the answers you need. With our model, DS Borg Homes will help you find the perfect price for the perfect home.

The Data: The data used to achieve our goal is from the King County House Sales dataset.

The following link is the csv file of the original dataset we used:

(insert csv file link here)

The Plan: The way we plan on tackling this is by doing the following:

Cleaning the data
Exploring the data
Modeling the data
Cleaning & Exploring The Data:
The first thing we did was look at the data while keeping in mind the following questions:

What information do we have?
What information are we missing?
What information do we need to get rid of?
From viewing the data we found that we had 22 columns which consisted of information on a list of homes that played a role in its price for the years 2014 and 2015; size of the home, the year it was built, the year it was renovated, number of bathrooms and bedrooms, etc.

We also found that the missing values were represented with a ? or a NaN, this was the issue we decided to deal with first. After the missing values were taken care of we continued viewing the data for anything that would interfere with the modeling process. This included changing outliers and dropping columns. Afterwards the clean data was saved to a csv file, to work with.

The following csv file is where the cleaned data of the needed columns are found:

(insert csv file link here)

The following notebook shows the cleaning & exploring of the data as well as our findings from doing so:

https://github.com/ezgigm/Project_2/blob/Ezgi/.ipynb_checkpoints/STEP_1_Cleaning%20and%20Exploring%20Data-checkpoint.ipynb

Modeling The Data
When working with predictive Linear Regression Models you must first choose how you will measure the accuracy of your work. For this instance we chose to use the R-squared.

This R-squared score is used in statistics as a measurement of how close you can get your data to fit on a regression line. In other words, the closer you can get your data to fit on that line the better your model is doing at predicting the sale price of a home. The highest score you can get is a 1, in percentages that is 100% of accuracy. We chose this scoring metric because we knew that several models would be tested and the R-squared score would be compatible with those test models. The next step was to run our first model, our Baseline Model.

You can find more information on the R-squared score using the link below:

https://blog.minitab.com/blog/adventures-in-statistics-2/regression-analysis-how-do-i-interpret-r-squared-and-assess-the-goodness-of-fit

Baseline Model
look for correlations Choose linear regression for baseline improve base line by scaler look into more columns

README explains findings succinctly

README explains the final model and how it compares to an initial baseline

README outlines some recommendations and lists out future improvements and potential weaknesses in data/models

Both the original data and the version used for analysis are available in the repository
