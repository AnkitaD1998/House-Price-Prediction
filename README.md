# House-Price-Prediction
# Problem Statement
A house's value is more than location and square footage. Like the features that make up a person, an educated party would want to know all aspects that give a house its value. For example, you want to sell a house and you don’t know the price you may expect — it can’t be too low or too high. To find house prices you usually try to find similar properties in your neighborhood and based on the gathered data you will try to assess your house price.

# Objective
Build a model that will predict the house price when required features are passed to the model. So we will find out the significant features from the given features dataset that affect the house price the most and Build the best feasible model to predict the house price

# Data Description
We have more than 21k records having 26 features. These columns provide the below information

- Cid: Notation for a house. Will not be of use, So we will drop this column
- day hours: Represents Date, when the house was sold
- price: It's our TARGET feature, that we have to predict based on other features
- room_bed: Represents the number of bedrooms in a house
- room_bath: Represents the number of bathrooms
- living_measure: Represents the square footage of the house
- lot_measure: Represents the square footage of the lot
- ceil: Represents the number of floors in the house
- coast: Represents whether the house has a waterfront view
- sight: Represents how many times sight has been viewed
- condition: Represents the overall condition of the house
- quality: Represents the grade given to the house based on the grading system
- ceil_measure: Represents the square footage of the house apart from the basement
- basement: Represents square footage of the basement
- yr_built: Represents the year when the house was built
- yr_renovated: Represents the year when the house was last renovated
- zipcode: Represents zipcode as the name implies
- State: Represents States
- City: represents cities
- lat: Represents Lattitude co-ordinates
- Long: Represents Longitude co-ordinates
- living_measure15: Represents the square footage of the house, when measured in 2015 year as the house area may or may not change after renovation if any happened
- lot_measure15: Represents the square footage of the lot, when measured in 2015 year as the lot area may or may not change after renovation if any done
- furnished: Tells whether the house is furnished or not
- total_area: Represents total area i.e. area of both living and lot

# Data Pipeline
- Exploratory Data Analysis (EDA): In this part, we have done some EDA on the features to see the trend.
- Data Preprocessing: In this part, we went through each attribute and encoded the categorical features using the pipeline.
- Model Creation: Finally in this part, we created the various models. These various models are being analyzed and we tried to study various models so that we can get the best 
  performance.
  
# Algorithms
1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. Decision Tree Regression
5. Random Forest Regression
6. Gradient Boosting Regression

# Conclusion
The best performance is given by the Gradient boosting model with training (score-0.93, RMSE-63611), testing (score-0.86, RSME-93794) 

# Recommendations for Sellers
- Conduct a thorough analysis of similar properties in the neighborhood to set a competitive and realistic price
- Emphasize the number of bedrooms and bathrooms, living area, and any unique features like waterfront views, quality ratings, and condition to justify the price
- Consider renovating outdated aspects of the house, especially if the property is old. Upgrading kitchens, bathrooms, and flooring can significantly increase the value
- Furnishing the house can attract higher prices, as furnished houses are perceived as more valuable
- If the house is in a sought-after location like Seattle or Medina, make sure to highlight this in the marketing materials

# Recommendations for Buyers
- Focus on properties with features that are important to you, such as the number of bedrooms, bathrooms, and overall condition
- Consider properties with high-quality grades and good condition, as they are likely to appreciate more over time
- Conduct thorough inspections to identify any potential issues, especially in older properties or those with basements that might have been undervalued

# General Recommendations
- Run educational campaigns to inform potential buyers and sellers about the key factors affecting property values and the importance of accurate pricing
- Pay attention to the correlation between various features (e.g., living measure, number of floors, condition, quality) and price to identify the most influential factors






