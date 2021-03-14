# UDACITY Project - Diamonds Dataset 
This document explores a dataset containing prices and attributes for approximately 54,000 round-cut diamonds.

## Data Wrangling and Data Visualisation

## by Lilla Szulyovszky


## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater Boston area. 

Table of Contents
- Introduction of the dataset and Analysis Plan
- Data Wrangling
- Univariate Explorations
- Bivariate Explorations
- Multivariate Explorations

**Variables**

**price** Price in dollars. Data was collected in 2008.

**carat** Diamond weight. 1 carat is equal to 0.2 grams.

**cut** Quality of diamond cut, affects its shine. Grades go from (low) Fair, Good, Very Good, Premium, Ideal (best).

**color**: Measure of diamond coloration. Increasing grades go from (some color) J, I, H, G, F, E, D (colorless).

**clarity**: Measure of diamond inclusions. Increasing grades go from (inclusions) I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF (internally flawless).

**x, y, z**: Diamond length, width, and depth, respectively, in mm.

**table**: Ratio of width of top face of diamond to its overall width, as a percentage.

**depth**: Proportional depth of diamond, as a percentage. This is computed as 2 * z / (x + y), or the ratio of the depth to the average of length and width.


**Insights to explore**

- correlations present between price and carat weight
- relationship between price and the three categorical quality features, cut, color, and clarity.
- how does carat weight change across the other three 'C' quality measures
- relationship between price, carat, and clarity

**Features in the dataset the will help support the investigation?**

price, carat, cut, color, clarity
