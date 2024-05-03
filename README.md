# Nassau County Home Value Predictor
This project uses Sci-kit's Gradient Boosting Regressor to predict the value of homes in Nassau County. The data was scraped, cleaned, and wrangled from start to finish by me using BS4, pandas, and numpy. Every village/CDP was scraped unless there were no listings. The data also excluded homes over $2,000,000.

### Update 5/3/24 - Data fitted to Keras NN. R2 score remained similar.

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

# Tests (keras model)
<img width="623" alt="Screen Shot 2024-05-03 at 12 26 15 AM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/19b070f7-01bf-4390-9252-8e17b612be2a">
<img width="230" alt="Screen Shot 2024-05-03 at 12 27 43 AM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/04ffe4b6-2b77-41fe-88b3-4559632fd0d5">

<img width="623" alt="Screen Shot 2024-05-03 at 12 29 35 AM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/2962f466-0bb6-4bba-8fe9-dac66c0f421a">
<img width="230" alt="Screen Shot 2024-05-03 at 12 30 05 AM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/64c0838c-e26e-4883-be31-f79913f83741">

<img width="623" alt="Screen Shot 2024-05-03 at 12 33 36 AM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/8d3b9804-0f7e-4c30-9266-a24e2bd1907a">
<img width="230" alt="Screen Shot 2024-05-03 at 12 33 25 AM" src="https://github.com/AnthonyValle/Nassau-County-Home-Market-Value-Predictor/assets/66498197/083d97c4-407d-4d11-b74f-abe344464372">

