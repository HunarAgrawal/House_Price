# House Price Prediction using Linear Regression

This project demonstrates how to use **Linear Regression** to predict house prices in California based on various features like average rooms, median income, house age, etc. The dataset used is the **California Housing Dataset** available in sklearn. The project also includes model evaluation, assumptions checking, and outlier detection.

---

## Features

### 1. **Data Preprocessing**
- Load the **California Housing Dataset**.
- Handle missing values and check the data structure.
- Split the data into features (X) and target (y).

### 2. **Multicollinearity Check (VIF)**
- Use **Variance Inflation Factor (VIF)** to check for multicollinearity among features.

### 3. **Linear Regression Model**
- Fit a **Linear Regression** model to the training data.
- Display model coefficients and intercept to understand the relationships between features and target.

### 4. **Model Evaluation**
- Evaluate model performance using:
  - **Mean Squared Error (MSE)**
  - **Mean Absolute Error (MAE)**
  - **R-squared (R2)**

### 5. **Assumptions Checking**
- **Linearity**: Check for linear relationship between residuals and fitted values.
- **Homoscedasticity**: Check if the residuals have constant variance.
- **Normality**: Use Q-Q plot to check if residuals follow a normal distribution.
- **Autocorrelation**: Perform **Durbin-Watson** test to check for autocorrelation in residuals.
- **Outliers Detection**: Use **Cook's Distance** to detect influential data points.

### 6. **Final Prediction**
- Make predictions on the test data and add the predicted house prices to the dataset.
- Save the results to a CSV file (`predicted_house_prices.csv`).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HunarAgrawal/House_Price_Prediction.git
   cd House_Price_Prediction

2. Install required Python libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn statsmodels

---

## Usage

1. Run the script:
   ```bash
   python california_housing_regression.py

2. View the results:

- Model evaluation metrics (MSE, MAE, R2) will be displayed in the terminal.
- Visualizations of residuals, homoscedasticity, normality, and Cook's distance will be shown.
- The predicted house prices will be saved to predicted_house_prices.csv.

---

## File Descriptions

- california_housing_regression.py: Main Python script that loads the dataset, trains the model, performs evaluations, and saves predictions.
- predicted_house_prices.csv: CSV file containing the predicted house prices based on the features.

---

## Dependencies

- Python 3.7 or higher
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - statsmodels
 
---

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository, make changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author

Hunar Agrawal

---

## Acknowledgments

- California Housing Dataset: Available in sklearn's datasets module.
- scikit-learn: For providing tools for data analysis and modeling.
- statsmodels: For statistical testing and model diagnostics.
- pandas, numpy, seaborn, and matplotlib: For data manipulation, visualization, and plotting.
