# Flight Price Prediction

## Business Case	

The Flight Price Prediction project aims to predict flight ticket prices based on given data. Flight ticket prices are notoriously unpredictable, fluctuating frequently and making it challenging for travelers to plan their journeys effectively. By leveraging machine learning techniques, we can develop models that predict future flight prices, aiding both customers in planning their trips and airlines in setting competitive prices.

### Tasks

1. **Data Analysis Report**: Prepare a comprehensive data analysis report on the provided dataset, exploring the features and patterns within the data.
   
2. **Predictive Model**: Develop a predictive model that accurately forecasts flight ticket prices, enabling customers to plan their journeys based on predicted fares.

## Domain Analysis

The dataset includes various features related to flight information:

1. **Airline**: The name of the airline company operating the flight.
2. **Date of Journey**: The date on which the flight departs.
3. **Source**: The city from which the flight originates.
4. **Destination**: The city where the flight is expected to land.
5. **Route**: The path or stops the flight will take.
6. **Departure Time**: The scheduled departure time.
7. **Arrival Time**: The scheduled arrival time.
8. **Duration**: The total travel time in hours.
9. **Total Stops**: The number of stops or layovers.
10. **Additional_Info**: Additional information about the flight.
11. **Price**: The target variable containing the ticket price.

## Model Evaluation

Several machine learning models were evaluated for their performance in predicting flight ticket prices:

- Linear Regressor: CV Score - 0.63
- K Neighbors Regressor: CV Score - 0.57
- Decision Tree Regressor: CV Score - 0.75
- Random Forest Regressor: CV Score - 0.83
- Gradient Boosting Regressor: CV Score - 0.85

## Conclusion

Applying machine learning to predict flight ticket prices offers benefits for both travelers and airlines. The Gradient Boosting model emerged as the best performer, achieving an R-squared (r2_score) of 0.85. This high accuracy level demonstrates the model's capability to accurately predict flight fares, providing valuable insights for travelers and assisting airlines in optimizing pricing strategies.

Key findings include identifying influential features such as total stops, duration, airline, and route, which significantly impact flight prices. Despite challenges such as working with date and time data, analyzing feature correlations, and hyperparameter tuning, machine learning-based flight fare prediction offers a powerful method for optimizing pricing in the airline industry.

## Challenges Faced

Challenges encountered during the project included converting date and time data, analyzing feature correlations, and hyperparameter tuning. Overcoming these challenges required careful parsing of data, exploration of feature relationships, and optimization of model parameters to achieve the best performance.
