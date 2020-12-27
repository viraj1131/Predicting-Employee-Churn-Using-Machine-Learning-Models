# Predicting-Employee-Churn-Using-Machine-Learning-Models

**What is employee Turnover/churn?** </br>
**Answer**: Based on given employee characterstics predicting how many employees will leave the oragnization after certain period of time.


<p>The main objective of the project is to forecast employee turnover or churn using different machine learning classification models like Logistic Regression, Random Forest, SVM (Support Vector Machine), and Gradient Boosting Classifier. Also I have applied fully connceted nueral network model to see how it perform compare to supervised calssification models. The idea behind applying different models for solving the problem is to find which model perform better and then taking the best model for applying Cross Validation to get best accuracy.</p> 



### Things Which I have perfomed in whole Python Notebook are as below:

1. Basic Exploration Of Data
2. Data Visualization
3. Handling Categorical Features
4. Selecting Features Mannually
5. Selecting Features Automatically Using REF
6. Applying and Evaluating Models
7. Applying Cross Validation On Best Performing Model
8. Ploting ROC Curve
9. Feature Importance

## <p>For performing Employee turnover using machine learning I have used dataset from kaggle. Below is the brief description about data.</p>

Link to dataset: https://www.kaggle.com/giripujar/hr-analytics

## Data Description:

### This data is consist of 10 variables(columns) and 15,000 observation(rows).Each row represent a employee which has revelent values for each 10 variabales.More detail about columns is mentioned below:

* <b>satisfaction_level (Numerical):</b> This column represents employee satisfaction level between 0 to 1 where 0 represents least and 1 represents high.
* <b>last_evaluation (Numerical):</b> This column represents how much time since last evaluation of employee.</br>
* <b>number_project (Numerical):</b> This column reprsents how much projects employee has done so far.</br>
* <b>average_montly_hours (Numerical):</b> This column represents average monthly hours employee has spend in organization.</br>
* <b>time_spend_company (Numerical):</b> This column represents how many years employee has spend in organization</br>
* <b>Work_accident (Numerical):</b></b> This column represents while working whether they have any work accident or not where 1 means yes they have work accident and 0 means No they have not work accident.</br>
* <b>promotion_last_5years (Numerical):</b> This column represents whether employee got any promotion or not in last 5 years where 0 means No they got no promotion in last 5 years and 1 means Yes they got promotion in last 5 years.</br>
* <b>Department (Nominal Categorical):</b> This column represents in which department employee is/was working for example sales,IT,accounting etc. there are 10 total category or department exist in the column.</br>
* <b>Salary (Ordinal Categorical):</b> This column repersents salary of employee whether it is hight,low or medium.</br>
* <b>left (Numerical):</b> This column represents whether employee has left the organization or not where 0 means No employee has not left the organization and 1 means Yes employee has left the organization.</br>
