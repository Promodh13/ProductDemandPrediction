# Product Demand Prediction Models

This repository contains Jupyter Notebook files implementing three different regression models for predicting product demand based on historical data. The models included are Gradient Boosting Regression, Decision Tree Regression, and Random Forest Regression. All three models use the same dataset, `product_demand.csv`, as their data source.

## Dataset Description

The dataset provided for this task contains the following key information:

- **Product ID:** Each product in the company's inventory is assigned a unique identifier, allowing us to distinguish between different items.
- **Store ID:** This represents the specific store or location where the product was sold. It helps in understanding regional variations in demand.
- **Total Price:** This is the actual price at which the product was sold to customers during the sales transaction. It includes any discounts or promotions applied.
- **Base Price:** The base price is the original or standard price at which the product is typically sold before any discounts or promotions are applied.
- **Units Sold (Quantity Demanded):** This is the quantity of the product that was purchased by customers at a given price point. It reflects the demand for the product at that particular price.

## File Structure

- `gradiant_boosting_regression_model.ipynb`: Jupyter Notebook containing the implementation of the Gradient Boosting Regression model.
- `decision_tree_regression_model.ipynb`: Jupyter Notebook containing the implementation of the Decision Tree Regression model.
- `random_forest_regression_model.ipynb`: Jupyter Notebook containing the implementation of the Random Forest Regression model.
- `product_demand.csv`: CSV file containing the dataset for model training and testing.

## Running the Notebooks

To run the provided Jupyter Notebook files, follow these steps:

1. **Upload Dataset:**
   - Upload the `product_demand.csv` dataset file to your Google Colab environment.

2. **Open the Notebooks:**
   - Open the respective Jupyter Notebook file for the model you want to run (`gradiant_boosting_regression_model.ipynb`, `decision_tree_regression_model.ipynb`, or `random_forest_regression_model.ipynb`) in Google Colab.

3. **Execute the Cells:**
   - Run each cell in the notebook sequentially. Make sure to follow the comments and markdown instructions within the notebook to understand each step of the process.

### Steps Included in the Notebooks:

Each notebook includes the following steps:

- **Data Loading and Exploration:**
  - Load the dataset from `product_demand.csv`.
  - Explore the dataset to understand its structure and features.

- **Data Preprocessing:**
  - Handle missing values if any.
  - Perform feature scaling if necessary.

- **Data Visualization:**
  - Visualize the data to gain insights into the relationships between features and the target variable.

- **Train-Test Split:**
  - Split the dataset into training and testing sets.

- **Model Training:**
  - Train the regression model using the training data.

- **Model Testing:**
  - Test the trained model using the testing data.

- **Evaluation Metrics:**
  - Calculate the following evaluation metrics:
    - **R^2 Score:** Represents the proportion of the variance in the dependent variable that is predictable from the independent variables.
    - **Mean Absolute Error (MAE):** Measures the average absolute errors between predicted and actual values.
    - **Mean Squared Error (MSE):** Measures the average of the squares of errors between predicted and actual values.
    - **Root Mean Squared Error (RMSE):** Represents the square root of the average of squared errors, providing the error in the same unit as the target variable.

## Dependencies

The notebooks require the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
