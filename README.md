# The Sale Price Of Houses

**The Goal:**
 The goal of this project is predict the the sale price of homes based off of the zipcode of the homes.

**The Data:**
 The data used to acheive our goal is from the King County House Sales dataset. Within this file you will find information on homes that contribute to how much they cost, i.e. if the home was renovated. 

**The Plan:** 
 The way we plan on tackling this is by doing the following:
 
1. Cleaning the data
2. Exploring the data
3. Modeling data

**Cleaning & Exploring The Data:**
 The first thing we did was look at the data while keeping in mind the following questions:
 
 1. What information do we have?
 2. What information are we missing?
 3. What information do we need to get rid of?
 
From viewing the data we found that we had 22 columns which consisted of information on homes that played a roll in its price; size of the home, the year it was built, the year it was renovated, number of batherooms and bedrooms, etc. 

The missing values were represented with a *?* as well as a *NaN*, this was the issue we decieded to deal with first. After the missing values were taken care of we graphed a heatmap to view the correlation between each column vs the price column, with this we would be able to determine which columns were important and which columns were not. From the graph we decided on the following columns:

- price
- bedrooms
- bathrooms
- sqft_living (square foot of living space/actual house)
- sqft_lot
- sqft_living15
- sqft_lot15
- sqft_basement
- sqft_above
- grade 
- zipecode 
- lat
- long
 
 Now that we had clean data and the list of clumns we needed to model the data it was time to create a new dataset saving all of the work thatw as done. 
 
 The following csv file is where the cleaned data of the needed columns are found **(insert csv file link here)** The following notebook shows the cleaning & exploring of the data  **(insert notebook link here)**
 
 # Modeling The Data 

