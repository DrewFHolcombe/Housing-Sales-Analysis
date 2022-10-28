
# Westlake Realty Group

Authors: Drew Holcombe, Juan Acosta
Phase 2 Project
(hypothetical example)

## Overview

Westlake Realty Group has grown into a diversified, real estate company that specializes in property management, commercial real estate, and relocation services. Our project presents data of house sale prices for King County, Washington. Using linear regression and data analysis techniques we are able to find which factors are the most impactful to determine the value of a house, and how Westlake Realty Group could use this information to help them and its clients make decisions.


## Business Understanding

As metropolitan areas keep growing in population and the housing market is constantly changing, the homebuying process can take longer than expected due to limited options. Westlake Realty Group is looking for factors and characteristics of a house that are the most impactful to determine its price, and be capable of helping homebuyers manage their options based on specific features vs their budget.

Our group's objective is to find features that accurately predict the sell price.



## Data

This project presents data from around 21 thousand houses sold between May 2014 and May 2015 in King county, Washington, contained in the kc_house dataset. The variables we found to be most useful for our research were:
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

Statistical analyses were performed in Python, using the Pandas data analysis and manipulation library, the Matplotlib/Seaborn libraries to make plots, and libraries for statistical models such as statsmodels were also implemented during the project. These were applied in order to detect, clean, organize, and find the ordinary least squares model that helps us best observe data patterns, draw conclusions, and ultimately answer questions to help Westlake Realty Group.



## Regression Results

Our model suggests the most impactful features to predict house prices within king county are size of living area and the construction quality, by adding 909 square feet to living area price increases by 17%. Construction quality has a massive impact, below-average homes sell 27 to 42% cheaper than average homes, while more luxury homes sell for as much as 88% more. 65% of the variability observed in price is explained by the regression model.


Some other key points to mention are:

- Adding a floor ups the price by 7.6%
- Being waterfront increases the price by 30%
- Adding a 3/4 bathroom increases price by 6%
- Having a view can increase the price from 17 to 26%
- A home in poor condition can be nearly 13% cheaper, while a very good home can be 8% more expensive
- Year built, square footage of the lot, and number of bedrooms do not have significant impacts.


## Conclusions


Homebuyers face a major choice, whether it is their first time buying or not, and it is when you, Westlake Realty Group, are just about to close a deal when they could change opinions and put all your efforts at risk if not handled properly. The results presented are useful to provide more confidence to Westlake clients and let them know they are actually going in the right direction. Our model provides specific features and their respective influence on price. Some measures to implement these results include establishing a redefined sales process in which the client's needs and wants can be adjusted to find a perfect fit between house features and budget. Showing interest in every quantitative aspect that brings value to a house sure can build trust between you and client, and the confidence this place on the deal could bring some advantage to you when looking for common ground on fees and commissions.



#### Limitatios and next steps

Our resource only included records from 12 months (may 2014 - may 2015), and are from seven years ago, the housing market changes constantly and certainly an analysis using more up to date data could end in different results.

The dataset used included details on a small fraction of houses were renovations got done, but it was far from being substantial enough to put it in a model, by researching more data about it, we could find the impact it has on price, and predict if its something you could use in favor of increasing profit or client satisfaction. In addition to, something to further explore is how other factors such as new developments in a certain area could inflict or benefit the value of a property, development for hospitals, open spaces, public buildings, or even the school district.



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
