# Petrol Price Prediction

## Project Description

This project aims to predict petrol prices using a Random Forest Regressor model. It utilizes historical petrol price data and extracts features from the date to train the model.

## Workflow

1. **Data Loading and Preprocessing:**
   - Load the training and testing datasets (`train_data.csv` and `test_data.csv`).
   - Handle missing values by dropping rows with null values in the 'Petrol (USD)' column.
   - Convert the 'Date' column to datetime format and sort the dataframe by date.
   - Rename the 'Petrol (USD)' column to 'Price' for consistency.

2. **Feature Engineering:**
   - Extract features from the 'Date' column, including year, month, and day.

3. **Model Training:**
   - Split the data into training and validation sets.
   - Initialize and train a Random Forest Regressor model with specified parameters (e.g., `n_estimators=300`, `random_state=0`).

4. **Model Evaluation:**
   - Make predictions on the validation set.
   - Evaluate the model's performance using metrics like Mean Absolute Error (MAE), R-squared, and accuracy.

5. **Prediction and Submission:**
   - Load the sample submission file.
   - Make predictions on the test data.
   - Create a submission file with the predicted values.

## Execution

1. **Install Dependencies: **
2. **Run the Notebook:**
- Open the Jupyter Notebook (`Petrol_Price_Pridiction_iNeuron.ipynb`).
- Execute the code cells sequentially.

## Coding Standards

This project follows the PEP 8 coding style guide for Python code.

## Contributing

Contributions are welcome! Please follow the guidelines outlined in the `CONTRIBUTING.md` file (if applicable).

## License

This project is licensed under the MIT license.
