# Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
## Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations

### Data Preparation and Exploration
* **Data Cleaning:** Removed unnecessary columns.
* **Feature Engineering:** Converted relevant features into categorical strings for better analysis.
* **Univariate Analysis:** Analyzed temperature distribution and categorical feature value counts.
* **Bivariate Analysis:** Examined relationships between year, season, month, weekday, weather, and bike rentals.
* **Correlation Analysis:** Identified positive correlations between temperature, apparent temperature, and bike rentals.

### Model Development
* **Data Preparation:** Created dummy variables for categorical features, scaled numerical features, and split data into training and testing sets.
* **Feature Selection:** Utilized Recursive Feature Elimination (RFE) to select the most important features.
* **Model Building:** Developed a linear regression model using selected features.
* **Model Evaluation:**
    * Assessed model performance using metrics like R-squared and mean squared error.
    * Conducted residual analysis to check for homoscedasticity.

### Key Findings
* **Seasonal Patterns:** Bike rentals are highest in fall and lowest in spring.
* **Year-over-Year Growth:** Bike rentals have increased over time, with higher demand in 2019 compared to 2018.
* **Monthly Trends:** Rentals generally increase from May to September.
* **Weekday Patterns:** Weekends (especially Saturdays) see higher demand.
* **Weather Influence:** Clear weather is associated with higher rentals, while light rain leads to lower demand.
* **Temperature Impact:** Higher temperatures correlate with increased bike rentals.

### Conclusion
The linear regression model effectively captures the relationship between various factors and bike rental demand. 
