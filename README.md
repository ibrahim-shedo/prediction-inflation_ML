

Inflation Prediction using Linear Regression
Overview
This project aims to predict Inflation Rates using Linear Regression with historical data that includes variables such as:

YEARS (Time/Years)
Growth Rates (Annual growth of the economy)
Exchange Rates (Foreign currency exchange rates)
CPI Rates (Consumer Price Index)
Lending Rates (Interest rates for loans)
Inflation Rates (Target variable for prediction)
The project uses the CPI Rate (Consumer Price Index) as the primary predictor (feature variable) to estimate the Inflation Rates.

Dataset Description
The dataset contains six columns:

YEARS: The year of the data point.
Growth_Rates: The annual economic growth rate in percentage (%).
Exchange_Rates: The exchange rate of the local currency against a benchmark currency (e.g., USD).
CPI_Rates: The Consumer Price Index, representing the average change in prices over time for goods and services.
Lending_Rates: The interest rate applied by financial institutions for loans.
Inflation_Rates: The target variable, representing the inflation rate in percentage (%).
The target variable for prediction is the Inflation Rate, and the primary predictor used in this model is the CPI Rate.

Objective
The objective of this project is to build a simple linear regression model that can predict future inflation rates based on the CPI Rate.

Files in the Repository
data.csv: The dataset file containing historical data for inflation, CPI rates, growth rates, exchange rates, and lending rates.
inflation_prediction.py: The Python script that implements the linear regression model.
README.md: Project overview and instructions (this file).
requirements.txt: A list of dependencies required to run the project.
inflation_prediction.ipynb: Jupyter notebook implementing the same model in an interactive environment (optional).
Linear Regression Model
Steps for the Model:
Data Preprocessing:

Load the dataset.
Handle missing data (if any).
Select features and target variables.
Split the data into training and testing sets.
Feature Selection:

The primary feature for this model is CPI Rate, as it has a strong correlation with inflation.
Inflation Rate is the target variable.
Model Training:

Fit a Linear Regression model to predict inflation based on CPI rates.
Model Evaluation:

Use metrics such as Mean Squared Error (MSE) and R-squared to evaluate the model's accuracy.
Requirements
To run this project, you'll need:

Python 3.x
pandas
numpy
scikit-learn
matplotlib (for plotting, optional)
Install the required dependencies by running:

bash
Copy code
pip install -r requirements.txt
How to Run the Project
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/inflation-prediction.git
Navigate to the project folder:

bash
Copy code
cd inflation-prediction
Run the Python script:

bash
Copy code
python inflation_prediction.py
Optional: Run the Jupyter notebook:

bash
Copy code
jupyter notebook inflation_prediction.ipynb
Example Workflow
Load Data: Load the dataset and preview it to understand the structure.

Visualize: Plot CPI rates vs. inflation rates to visualize their correlation.

Train the Model: Train the linear regression model on the training data.

Evaluate the Model: Test the model using the testing data and visualize the results.

Make Predictions: Use the model to predict inflation rates for future years based on CPI rates.

Results
The linear regression model predicts inflation rates using CPI rates with reasonable accuracy. The model's performance may depend on the quality of the data, and additional features such as Growth Rates and Exchange Rates could further enhance the prediction.

Future Improvements
Multivariate Regression: Include more features like Growth Rates, Exchange Rates, and Lending Rates for a more robust model.
Data Collection: Collect more up-to-date data to enhance model accuracy.
Hyperparameter Tuning: Explore advanced regression techniques and hyperparameter optimization for better predictions.
Conclusion
This project demonstrates how to use Linear Regression to predict inflation rates based on historical CPI Rates. The relationship between inflation and CPI is crucial for economic forecasting and decision-making.

License
This project is open-source and available under the MIT License.

