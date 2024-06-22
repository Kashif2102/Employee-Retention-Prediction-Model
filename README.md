# Employee Retention Prediction Model

This project demonstrates a multivariable logistic regression model to predict whether an employee is likely to stay or leave based on various features such as satisfaction level, average monthly hours, promotion status in the last 5 years, and salary.

## Data Source

The dataset used in this project is fictional and generated for demonstration purposes. It does not represent real-world employee data. The features and patterns within the dataset are synthetically created to showcase the functionality of the logistic regression model. Predictions made by the model on this fictional dataset are for illustrative purposes and may not accurately reflect real-world scenarios.

## Prerequisites

Ensure you have the following installed:

- [Python](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install)
- Required Python libraries: pandas, matplotlib, scikit-learn

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Kashif2102/Employee-Retention-Prediction-Model.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Employee-Retention-Prediction-Model
   ```

3. **Install the required libraries:**

   ```bash
   pip install pandas matplotlib scikit-learn
   ```

4. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open the notebook file** `Employee_Retention_Prediction_Model.ipynb` **and run the cells to execute the code.**

## Project Structure

The project consists of the following main steps:

1. **Data Loading and Exploration:**
   - Load the dataset using pandas.
   - Display the first few rows of the dataset for an overview.
   - Analyze the dataset to understand the distribution of employees who left and those who stayed.

2. **Data Visualization:**
   - Visualize data to identify patterns and relationships between features and the target variable (`left`).

3. **Feature Selection:**
   - Based on data analysis, select key features that influence employee retention: Satisfaction Level, Average Monthly Hours, Promotion in the Last 5 Years, and Salary.
   - Use one-hot encoding to handle categorical data in the `salary` column.

4. **Model Training:**
   - Split the dataset into training and testing sets.
   - Train a logistic regression model using the training data.

5. **Model Evaluation:**
   - Evaluate the model's performance using the testing data.
   - Calculate the accuracy of the model.

## Conclusion

This project showcases a basic example of how to build and evaluate a logistic regression model for predicting employee retention. The fictional dataset and the steps outlined provide a comprehensive demonstration of data loading, exploration, visualization, feature selection, model training, and evaluation. 

For real-world applications, ensure to use actual employee data, perform extensive data preprocessing, and consider additional features for improved model accuracy.
