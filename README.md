# star-age-categorization

This project is a jupyter notebook which trained a random forest classifier on data for thousands of stars in the Gaia database pre-categorized as either "young" or "old" based on whether they are less than or greater than 100 million years old. The data avaible included both color data and position/velocity data. The trained RFC was then used to categorize a nearly 570,000 star subset of the Gaia database.

## Prerequisites

This notebook is written for Python 2.7, and it uses numpy, astropy, sklearn, matplotlib, and mpl_toolkits.
