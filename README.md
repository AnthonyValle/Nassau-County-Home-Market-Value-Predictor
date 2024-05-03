# Nassau County Home Value Predictor
This project uses Sci-kit's Gradient Boosting Regressor to predict the value of homes in Nassau County. The data was scraped, cleaned, and wrangled from start to finish by me using BS4, pandas, and numpy. Every village/CDP was scraped unless there were no listings. The data also excluded homes over $2,000,000.

# NOTE 
Most to all of this project's files is being kept private for personal reasons

# Features
Bedrooms

Full Bath

Half Bath

Total Bath (Full+Half Baths)

Sq Ft

Lot Size

Year Built

Town/City Median Income

Town/City Median Home Value

Property-Type (Single, Multi); This feature was encoded into numerical categories

Town/City (Every village/CDP in Nassau County); This feature  was encoded into numerical categories

# Target
Price

# Individual Score
~ 0.80 +- .05

# Cross-Val Score
~ 0.70 +- .05

