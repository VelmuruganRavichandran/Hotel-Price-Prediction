# Hotel Price Prediction

## Project Description

In the ever-evolving hospitality industry, accurately predicting hotel prices is crucial for both consumers and hotel operators. Effective pricing strategies can enhance customer satisfaction and optimize revenue management. This project focuses on developing and evaluating various regression models to predict hotel prices based on several attributes, including hotel type, location, and customer reviews. The goal is to provide a reliable tool for forecasting prices and assisting in decision-making processes for both hotel operators and potential guests.

## Technologies Used

- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Plotting and visualization
- **scikit-learn**: Machine learning algorithms and model evaluation
- **Warnings**: Handling warnings in code
- **StandardScaler**: Feature scaling
- **train_test_split**: Splitting dataset into training and test sets
- **Counter**: Counting occurrences of items
- **CountVectorizer**: Converting text data into numerical features
- **LinearRegression**: Linear Regression model
- **Ridge**: Ridge Regression model
- **Lasso**: Lasso Regression model
- **RandomForestRegressor**: Random Forest Regressor
- **GradientBoostingRegressor**: Gradient Boosting Regressor
- **DecisionTreeRegressor**: Decision Tree Regressor
- **SVR**: Support Vector Regressor
- **mean_squared_error**: Evaluating model performance
- **r2_score**: R-squared metric
- **mean_absolute_error**: Mean Absolute Error metric

## Dataset Information

The dataset used for this project includes the following attributes:

- **Name**: Hotel Name
- **Place**: Place of the hotel
- **Type**: Type of the hotel
- **Price**: Price for 2 people in Rupees (₹)
- **ReviewsCount**: Total number of reviews
- **Ratings**: Ratings out of 10
- **City**: City in which the hotel is located
- **State**: State in which the hotel is located

## Results

The performance of the regression models was evaluated using the following metrics:

- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values. Lower values indicate better model performance.
- **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in predictions, without considering their direction.
- **R-squared (R²)**: Represents the proportion of the variance in the dependent variable that is predictable from the independent variables. Higher values indicate a better fit of the model.

## Acknowledgments

- **Open-source Libraries**: Thanks to Pandas, NumPy, Matplotlib, and scikit-learn for providing essential tools for data manipulation, visualization, and modeling.
- **Online Resources**: Appreciation to the tutorials, documentation, and forums that provided guidance and support throughout the project development.
- **Hospitality Data Providers**: Gratitude to the sources of the hotel data used in the project, which made this analysis possible.

