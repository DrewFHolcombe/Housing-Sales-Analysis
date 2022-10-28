
# Westlake Realty Group

Authors: Drew Holcombe, Juan Acosta



## Overview

Westlake Realty Group has grown into a diversified, real estate company that specializes in property management, commercial real estate, and relocation services. Our project presents data of house sale prices for King County, Washington. Using linear regression and data analysis techniques we are able to find which factors are the most impactful to determine the value of a house, and how Westlake Realty Group could use this information to help them and its clients make decisions.
(hypothetical example)


## Business Understanding

As metropolitan areas keep growing in population, and the housing market is constantly changing, homebuyers could find themselves facing limited options. Westlake Realty Group is looking for factors and characteristics of a house that are the most impactful to determine its price, and be capable to help homebuyers manage their options based on specific features vs their budget.

Our group's objective is to find features that accurately predict the sell price, and provide results and justifications for Westlake Realty Group.


## Data

Our project presents data of around 21 thousand house-sale records in King county, Washington, contained in the kc_house dataset. It includes houses sold between May 2014 and May 2015. The variables we found to be most useful for our research were:
- bedrooms - Number of bedrooms
- bathrooms - Number of bathrooms
- sqft_living - Square footage of living space in the home
- floors - Number of floors (levels) in house
- waterfront - Whether the house is on a waterfront
- view - Quality of view from house
- condition - How good the overall condition of the house is. Related to maintenance of house.
- grade - Overall grade of the house. Related to the construction and design of the house.
- and price is our target variable for the model.


## Methods

Statistical analyses were performed in Python, using the Pandas data analysis and manipulation library, the Matplotlib/Seaborn libraries to make plots, libraries for statistical models such as statsmodels were also implemented during the project. These were applied in order to detect, clean, organize, and find the ordinary least squares model that helps us best observe data patterns, draw conclusions, and ultimately answer questions to help Westlake Realty Group.

We use 

## Final model



## Conclusions

#### Regression Results

Our model suggests the most impactful features to predict house prices within king county are waterfront, size of living area, the construction quality and view. We found that year built and bedrooms do not have as much of an impact as it could be expected.

Some key points to mention are:

- Adding a floor ups the price by 7.6%
- Being waterfront increases the price by 30%
- Adding a 3/4 bathroom increases price by 6%
- Adding 909 square feet to living area increases price by 17%
- Having a view can increase the price from 17 to 26%
- A home in poor condition can be nearly 13% cheaper, while a very good home can be 8% more expensive.
- Construction quality has a massive impact; below-average homes sell 27 to 42% cheaper than average homes, while more luxury homes sell for as much as 88% more
- Year built, square footage of the lot, and number of bedrooms do not have significant impacts.


#### Limitatios and next steps

Our resource only included records from 12 months (may 2014 - may 2015), and are from seven years ago, the housing market changes constantly and certainly more up to date data could result in interesting predictions.

The dataset included details on a small fraction of houses were renovations got done, but it was far from being substantial enough to put it in a model, by researching more data about it, we could find the impact it has on price, and predict if its something you could use in favor of increasing profit or client satisfaction. In addition to, something to further explore is how other factors such as new developments in a certain area could inflict or benefit the value of a property, development for hospitals, open spaces, public buildings, or even the school district.



## For More Information
Please review our full analysis in our Jupyter Notebook or our presentation.

For any additional questions, please contact Drew Holcombe drew.holcombe7@gmail.com, Juan Acosta jmaa3108@gmail.com



## Repository Structure


```
├── README.md                                  <- The top-level README for reviewers of this project
├── Westlake_Realty_Group_Proposal.ipynb       <- Main notebook for project code
├── Project_Presentation.pdf                   <- PDF of slides for our presentation
├── Data                                       <- Data used in our analysis
├── Scratch Code                               <- Working notebooks for each member of the authors of this project
└── Images                                     <- images used and generated in the project
```
