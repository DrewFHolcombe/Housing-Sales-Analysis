
# Westlake Realty Group

Authors: Drew Holcombe, Juan Acosta


## Overview

Westlake Realty Group is a real estate company that specializes in property management, commercial real estate, and relocation services. Our project presents data of house sale prices for King County, Washington. Using linear regression and data analysis techniques we are able to find which factors are the most impactful to determine the value of a house, and how Westlake Realty Group could use this information to help them and their clients make decisions.


## Business Understanding

As metropolitan areas keep growing in population and the housing market is constantly changing, the homebuying process can take longer than expected due to limited options at a reasonable price point. Westlake Realty Group is investigating which factors and characteristics have the most impact on a home's price. This will help homebuyers manage their options based on specific features vs their budget.

Our group's objective is to find features that accurately predict a home's final price.


## Data

This project presents data from around 21 thousand houses sold between May 2014 and May 2015 in King county, Washington, contained in the kc_house dataset. The variables we used in our final model are:
- price - the sale price of the home (our target variable)
- bedrooms - Number of bedrooms
- bathrooms - Number of bathrooms
- sqft_living - Square footage of living space in the home
- sqft_lot - Square footage of the lot
- floors - Number of floors (levels) in house
- waterfront - Whether the house is on a waterfront
- view - Quality of view from house
- condition - How good the overall condition of the house is. Related to maintenance of house.
- grade - Overall grade of the house. Related to the construction and design of the house.
- yr_built - Year when the house was built


## Methods

Statistical analyses were performed in Python, using the Pandas data analysis and manipulation library, the Matplotlib/Seaborn libraries to make plots, and libraries for statistical models such as statsmodels. These were applied in order to detect, clean, organize, and find the ordinary least squares model that helps us best observe data patterns, draw conclusions, and ultimately answer questions to help Westlake Realty Group.


## Regression Results

Our model suggests the most impactful features to predict house prices within king county are size of living area and the construction quality. Adding 909 square feet to living area increases the price of the home by 17%. Construction quality also has a massive impact: below-average homes sell 27 to 42% cheaper than average homes, while more luxury homes sell for as much as 88% more. 65% of the variability observed in price is explained by our regression model.


Some other key points to mention are:

- Adding a floor increases the price by 7.6%
- Being waterfront increases the price by 30%
- Adding a 3/4 bathroom increases price by 6%
- Having a view can increase the price from 17 to 26% (depending on quality of said view)
- A home in poor condition can be nearly 13% cheaper than a home in average condition, while a very well-maintained home can be 8% more expensive


## Conclusions

Homebuyers face a major choice, whether it is their first time buying or not. The results presented will provide more confidence to Westlake clients and let them know they are making the best decision to suit their budget and needs. Our model provides specific features and their respective influence on price, and finding a home that meets as many of the buyer's needs and wants as possible will be made easier by implimenting this resource. Showing interest in every quantitative aspect that brings value to a house can build trust between you and client, and that trust can positively impact Westlake's relations and reputation in the community.


#### Limitatios and next steps

Our resources only included records from 12 months (may 2014 - may 2015), and are from seven years ago. The housing market changes constantly, and an analysis using more up-to-date data could yield different results.

The dataset used included details on a small fraction of houses where renovations were completed, but it was far from being substantial enough to put it in a model. By obtaining more complete data, we could determine to what extent renovations impact the final price of the home. In addition, with additional time and resources, we could look into additional factors such as location, new developments, and proximity to hospitals, open spaces, public buildings, or schools.


## For More Information

Please review our full analysis in our Jupyter Notebook or our presentation.

For any additional questions, please contact Drew Holcombe at drew.holcombe7@gmail.com, or Juan Acosta at jmaa3108@gmail.com



## Repository Structure

```
├── README.md                                  <- The top-level README for reviewers of this project
├── Westlake_Realty_Group_Proposal.ipynb       <- Main notebook for project code
├── Project_Presentation.pdf                   <- PDF of slides for our presentation
├── Data                                       <- Data used in our analysis
├── Scratch Code                               <- Working notebooks for each author of the project
└── Images                                     <- images used and generated in the project
```
