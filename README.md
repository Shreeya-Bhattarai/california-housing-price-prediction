## California Housing Prices Prediction
This project was part of an assignment for Advanced Machine Learning course. This project focuses on predicting California housing prices using machine learning models. Three regression models were tested: Kernel Ridge Regression (RBF), Bayesian Linear Regression, and Gaussian Process Regression (GPR). 

## Objectives
Accurately predicting housing prices can help businesses and investors make better decisions in areas such as pricing strategies, high growth areas, investment planning, and risk management. 

## Dataset
The dataset is published in Statistics and Probability Letters (1997), authored by R. Kelly Pace and Ronald Berry. There are 20640 observations and 9 variables. The independent variables are median income (MedInc), house age (HouseAge), average rooms (AveRooms), average bedrooms (AveBedrms), population (Population), average occupancy (AveOccup), latitude (Latitude) and longitude (Longitude). The dependent variable is median house value (MedHouseVal).

## Data Analysis Approach
- EDA: dentified strong positive correlation between Median Income and housing prices. Other relevant features included Average Rooms per Household, House Age, and Location (Latitude/Longitude).
- Models: Tested three regression models: RBF Kernel Ridge, Bayesian Ridge, and Gaussian Process Regression models; the Gaussian model performed best with an R² of 0.665 and MSE of 0.439, effectively predicting housing prices based on income and location. Based on the model performance evaluation, RBF under Kernel Ridge Regression seems to perform best followed by Gaussian Process Regression. The R-squared is 0.75 which is higher than the other techniques while MSE is lowest.

## Model Performance

| Model     | Mean Squared Error (MSE) | R² Score |
|-----------|---------------------------|----------|
| RBF-KRR   | 0.3153                    | 0.7593   |
| Bayesian  | 0.5558                    | 0.5758   |
| Gaussian  | 0.4393                    | 0.6647   |

Among the models tested, the RBF-KRR model delivered the best performance with an R² score of 0.7593, followed by the Gaussian model (0.6647) and Bayesian regression (0.5758), indicating strong predictive power for housing prices.
 
## Insights
- Target high-income regions for premium housing development and pricing strategies.
- Coastal and southern California areas (especially near Los Angeles and San Francisco) consistently show higher median house values.
- Larger household sizes and more rooms per house are associated with higher values. In growing urban areas, space optimization can enhance perceived value.
- High population alone doesn't guarantee higher prices—context and affordability influence demand more than raw population.

## Conclusion
This project demonstrated how machine learning can be leveraged to predict housing prices using demographic and geographic data. The findings offer actionable insights for urban planning, real estate investments, and marketing strategy. With RBF-KRR emerging as the top performer, it's evident that capturing non-linear and spatial effects is essential in modeling real estate markets.
  
