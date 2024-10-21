Bank Customer Churn Prediction
<b>Overview</b><br> This project focuses on predicting customer churn for a bank. Churn refers to the scenario when a customer decides to stop using the services of a company. Predicting churn is crucial for banks to retain customers and maintain profitability.

<br>
<b>Table of Contents</b><br>

<a href="#overview">Overview</a><br>
<a href="#dataset">Dataset</a><br>
<a href="#installation">Installation</a><br>
<a href="#data-preprocessing">Data Preprocessing</a><br>
<a href="#exploratory-data-analysis">Exploratory Data Analysis</a><br>
<a href="#modeling">Modeling</a><br>
<a href="#evaluation">Evaluation</a><br>
<a href="#results">Results</a><br>
<br>
<b id="overview">Overview</b><br> The goal of this project is to build a machine learning model that predicts whether a customer will leave the bank (churn) based on various factors such as credit score, age, tenure, and the number of products the customer uses. This model can help the bank take preventive measures to retain customers at risk of churning.

<br>
<b id="dataset">Dataset</b><br> The dataset used in this project is the <b>Churn_Modelling.csv</b> file, which contains customer information, including:

<ul> <li>Customer ID, Surname</li> <li>Credit Score, Geography, Gender, Age</li> <li>Tenure, Balance, Number of Products</li> <li>Whether they have a credit card or not (HasCrCard)</li> <li>Whether they are an active member (IsActiveMember)</li> <li>Estimated Salary</li> <li>Whether they have churned or not (Exited)</li> </ul> <br>
<b id="installation">Installation</b><br> To run this project locally, follow these steps:

<ol> <li>Clone the repository:</li> <pre><code>git clone https://github.com/lagyal/Predicting_Churn_for_Bank_Customers.git</code></pre> <li>Navigate to the project directory:</li> <pre><code>https://github.com/lagyal/Predicting_Churn_for_Bank_Customers</code></pre> </ol> <br>
<b id="data-preprocessing">Data Preprocessing</b><br> The preprocessing steps include:

<ul> <li>Handling missing values</li> <li>Encoding categorical variables</li> <li>Feature scaling</li> </ul> <br>
<b id="exploratory-data-analysis">Exploratory Data Analysis</b><br> We explore various relationships between customer demographics, behavior, and churn. Visualizations include:

<ul> <li>Distribution of churn across different features</li> <li>Correlation between features</li> </ul> <br>
<b id="modeling">Modeling</b><br> The following machine learning models were used to predict customer churn:

<ul> <li>Logistic Regression</li> <li>Random Forest</li> <li>Gradient Boosting</li> </ul> We employed cross-validation and hyperparameter tuning to select the best model. <br>
<b id="evaluation">Evaluation</b><br> The models were evaluated based on the following metrics:

<ul> <li>Accuracy</li> <li>Precision</li> <li>Recall</li> <li>F1 Score</li> </ul> <br>
<b id="results">Results</b><br> The final model achieved a satisfactory accuracy and F1 score. The most important features influencing churn prediction were credit score, age, and number of products.

<br>
<b>Conclusion</b><br> This project successfully demonstrates how machine learning can be used to predict bank customer churn. With proper deployment, the model can assist the bank in retaining high-risk customers and improving its customer relationship management strategies.
