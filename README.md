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

# Pretty Damn Accurate
### Test 1
<img width="853" alt="Screen Shot 2024-04-21 at 10 34 41 PM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/0a3cf5a6-0820-4c28-a4aa-d07b79f70ee3">
<img width="335" alt="Screen Shot 2024-04-21 at 10 34 23 PM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/512b9768-8d19-423a-9ac3-89aa841fb636">

### Test 2
<img width="859" alt="Screen Shot 2024-04-21 at 10 40 28 PM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/5632c2a2-8af9-4d2c-a962-22d8fd71bb56">
<img width="345" alt="Screen Shot 2024-04-21 at 10 40 03 PM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/39b3cabf-2121-46b9-8dc4-333c5aea3dc1">

### Test 3
<img width="687" alt="Screen Shot 2024-04-21 at 11 32 12 PM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/7c3f8186-7a18-4c66-91c1-116b32353729">
<img width="322" alt="Screen Shot 2024-04-21 at 11 32 28 PM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/33433323-e1c1-4089-868a-3d10b5a03ef6">
