# Comparing Multiple Machine Learning Models for Regression

This project demonstrates how to train and compare multiple machine learning models to predict house prices based on various features. The process involves data preprocessing, model training, evaluation, and comparison to identify the most effective algorithm for this regression task.

## Dataset

The dataset used in this project contains information on real estate transactions. It includes the following features:

- **Transaction date**: The date of the house sale.
- **House age**: The age of the house in years.
- **Distance to the nearest MRT station**: Distance to the nearest mass rapid transit station.
- **Number of convenience stores**: Number of convenience stores in the vicinity.
- **Latitude**: Geographical latitude of the property.
- **Longitude**: Geographical longitude of the property.
- **House price of unit area**: The target variable representing the house price per unit area.

You can download the dataset from [here](https://statso.io).

## Project Workflow

1. **Data Preprocessing**:
   - Load the dataset using pandas.
   - Check for missing values and data types.
   - Convert the 'Transaction date' to a datetime object and extract useful features like year and month.
   - Split the data into features (X) and target variable (y).
   - Standardize the features to ensure all variables contribute equally to the analysis.
   - Split the dataset into training and testing sets.

2. **Model Selection**:
   - Choose a diverse set of regression models for comparison:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - Gradient Boosting Regressor

3. **Model Training and Evaluation**:
   - Train each model on the training data.
   - Evaluate the performance of each model using the testing data.
   - Use evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to assess model performance.

4. **Model Comparison**:
   - Compare the models based on their performance metrics.
   - Identify the model with the best balance of accuracy and computational efficiency.
  
## Acknowledgements
Special thanks to Aman Kharwal for his insightful blog post that guided the development of this project.

## Dependencies

- Python 3.12
- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn

You can install the required packages using pip:

```bash
pip install pandas scikit-learn numpy matplotlib seaborn
