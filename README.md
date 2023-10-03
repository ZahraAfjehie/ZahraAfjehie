## Hi there 👋

I'm Zahra!

I'm a data and business analyst with a strong passion for the world of data analysis.

Here are some projects from my ongoing data analysis learning journey:



## Selecting the Top Five Competitors for FMCG Products

The FMCG project involves the process of selecting the top five closest competitors in the market. This selection is based on both the fundamental attributes of weight/volume, price and category, as well as sales-related attributes, including market share, penetration rate, and distribution rate.

The initial step involves extracting volume/weight units from product names using regular expressions, requiring a few merges and concatenations to account for various cases (numeric/alphabetic).
Below is the result of this unit/value extraction from the product name:

<img width="193" alt="image" src="https://github.com/ZahraAfjehie/ZahraAfjehie/assets/13051084/1614d14a-ca71-4260-9a89-444e8c0b7ff0">




Subsequently, the units are standardized. In the following step, sales-related attributes are computed using multiple merge and group by techniques, and then normalized.The clustering process consists of two stages: first, clustering based on fundamental attributes, followed by clustering based on sales-related attributes. The final step encompasses the definition of two functions: the first function extracts the precise product name from the data frame, while the second function retrieves the top-five competitors cluster for that product.
Here is an example from the project's results, displaying the leading five competitors for a particular yogurt product:

<img width="304" alt="image" src="https://github.com/ZahraAfjehie/ZahraAfjehie/assets/13051084/93ecbe53-71b8-4a83-aac3-75ee5e82975a">


## Analysing the data related to Covid-19

