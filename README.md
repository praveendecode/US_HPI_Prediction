# Overview

  - This repository contains a data science project focused on understanding the key factors influencing US home prices over the last 20 years.
    
  - The project utilizes the S&P Case-Schiller Home Price Index as a proxy for home prices and explores various economic indicators to build a predictive model.
    
  - The chosen model is a Random Forest Regressor, achieving a remarkable R2 score of 99.87%.

# Problem Statement

  - The objective is to identify and analyze factors that significantly impact home prices in the United States.
    
  - By leveraging publicly available data, we aim to build a robust predictive model that explains the variations in the S&P Case-Schiller Home Price Index over the past two decades.

# Main Features

 The following features were selected for the predictive model:

  ### Zillow Home Value Index (USAUCSFRCONDOSMSAMID):
  
  - Median market value of all homes.
  - Reflects overall trends in home values, providing insights into market conditions and price movements.

  ### Average Sales Price for New Houses Sold (ASPNHSUS):
  
  - Reflects the average cost of newly constructed homes.
  - Influences perceptions of the affordability of new housing.

  ### Median Sales Price for New Houses Sold (MSPNHSUS):
  
  - Provides insights into the typical price of newly sold houses.
  - Helps understand the distribution of new home prices.

  ### Total Construction Spending: Residential (TLRESCONS):
  
  - Reflects the level of investment in residential construction.
  - Influences housing supply, potentially affecting home prices.

  ### Gross Domestic Income (GDI):
  
  - Influences economic conditions and affects consumer confidence in buying houses.

  ### Consumer Price Index for All Urban Consumers: Housing (CPIHOSNS):
  
  - Indicates inflation in housing costs, potentially impacting home prices.

  ### Total Population: All Ages (POP):
  - Population growth influences housing demand, potentially affecting home prices.

  ### National Totals of State and Local Tax Revenue: Property Taxes (QTAXT01QTAXCAT1USNO):
  
  - Property taxes influence the overall cost of living.

  ### New Privately-Owned Housing Units Authorized (PERMIT):    
  
  - Authorized housing units can influence home prices and increase demand.

  ### Monthly Supply of New Houses (MSACSR):
  
  - Reflects the balance between housing supply and demand.

 ### 30-Year Fixed Rate Mortgage Average (MORTGAGE30US):
 
  - Provides insights about a fixed interest rate for 30 years that buyers can afford for a loan.

### University of Michigan: Consumer Sentiment (UMCSENT):

  - Provides insights into consumer sentiment about the economy and the housing market.

### Unemployed Population: Aged 25-54 (LFUN25TTUSM647S) and Unemployment Rate (UNRATE):

  - Influences job security; more job security improves purchasing ability.

### Housing Inventory Estimate: Vacant Units (EVACANTUSQ176N):

  - Provides insights into vacant unit availability, market conditions, and supply and demand balance.

### Federal Funds Effective Rate (FEDFUNDS):

  - Changing in the federal reserve; adjusts the federal funds rate may influence the mortgage rate.

# Model Process

  ### Data Cleaning and Imputation:
  
   - Utilized machine learning models to impute missing values in the dataset.

  ### Exploratory Data Analysis (EDA):
  
   - Conducted thorough EDA to understand the relationships between features and the target variable.

  ### Feature Engineering:
  
   - Engineered relevant features to improve model performance.

  ### Model Selection:
  
   - Chose the Random Forest Regressor based on its outstanding R2 score of 99.87%.

  ### Model Evaluation:
  
   - Utilized R2 score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) for model evaluation.
     
  ### Feature Importance :

   -  After training the Random Forest Regressor model, the feature importance analysis has done to reveal the predictor variables that contributes more when predicting target variable.
   
 
