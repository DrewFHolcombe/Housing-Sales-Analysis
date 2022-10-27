
# Westlake Realty Group Proposal

Authors: Drew Holcombe, Juan Acosta



## Overview

Our project presents data of house sale prices for King County, Washington. Using statistical analyses techniques in Python we are able to give our recommendations on which factors of a house are the most impactful to determine price, and how Westlake Realty Group could use this information to reduce risk and increase profit.


## Business Challenge

Westlake Realty Group (hypothetical example) is looking for recommendations on factors and characteristics of a house that are the most impactful to determine its price. Our group's objective is to find features that accurately predict the given target, driven by real world data from the housing market, and provide results and justification for them to consider in their decision making process.


## Data

Our project presents data of house sale prices in King County, Seattle, contained in the kc_house dataset. It includes houses sold between May 2014 and May 2015. The variables we found to be most useful for our research are price, bedrooms, bathrooms, sqft_living, floors, waterfront, view, condition and grade.


## Methods

Data exploration and descriptive analysis was performed in Python, using the Pandas data analysis and manipulation library, and the Matplotlib/Seaborn libraries to make plots, libraries for statistical models such as statsmodels and sklearn, were also implemented during the project. This was in order to identify, clean, organize, and find the most effective correlation with the house-price variable.


## Results



## Conclusions

Our model suggests the most impactful features to predict house prices within king county are waterfront, size of living area, the construction quality and view. We found that year built and bedrooms do not have as much of an impact as it could be expected.

Some key points to mention are:

- Adding a floor ups the price by 7.6%
- Being waterfront increases the price by 30%
- Adding a 3/4 bathroom increases price by 6%
- Adding 909 square feet to living area increases price by 17%
- Having a view can increase the price from 17 to 26%
- A home in poor condition can be nearly 13% cheaper, while a very good home can be 8% more expensive
- Construction quality has a massive impact; below-average homes sell 26 to 42% cheaper than average homes, while more luxury homes sell for as much as 88% more
- Year built, square footage of the lot, and number of bedrooms do not have significant impacts.


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

```
