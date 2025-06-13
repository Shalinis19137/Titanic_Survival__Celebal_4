# Titanic_Survival__Celebal_4

🚢 Titanic Survival Prediction – Exploratory Data Analysis & ML
This project performs an in-depth Exploratory Data Analysis (EDA) and builds a Machine Learning model to estimate the probability of survival of passengers aboard the Titanic.

The goal is to analyze patterns behind who survived and who didn't using visualizations, feature engineering, and a logistic regression model. The final script also allows user input to predict the survival probability for any hypothetical passenger.

📁 Dataset
The dataset used is the classic Titanic dataset, containing passenger information such as:

Pclass – Ticket class

Sex – Gender

Age – Age of the passenger

SibSp – # of siblings/spouses aboard

Parch – # of parents/children aboard

Fare – Ticket fare

Embarked – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived – Survival (1 = Yes, 0 = No)

🛠️ Technologies & Libraries
Python 🐍

pandas, numpy – Data wrangling

matplotlib, seaborn – Data visualization

scikit-learn – Model training & evaluation

🔍 Exploratory Data Analysis (EDA)
Key steps in the analysis include:

Checking and handling missing values

Exploring data distributions using histograms

Detecting outliers using box plots

Analyzing correlations with a heatmap

Visualizing the relationship between features and survival

🧠 Machine Learning Model
Model used: Logistic Regression

Target: Survived

Features: Cleaned and encoded values of Pclass, Sex, Age, SibSp, Parch, Fare, and Embarked

Evaluation metrics: Confusion Matrix, Accuracy, Classification Report

🧮 User Prediction Feature
The project includes a feature where users can enter their own data (e.g., age, gender, fare, etc.) and get an estimated survival probability based on the trained model.

Example input:

text
Copy
Edit
Class: 2  
Sex: female  
Age: 28  
Siblings/Spouses: 0  
Parents/Children: 0  
Fare: 13  
Embarked: C
Output:

yaml
Copy
Edit




🧮 Estimated Probability of Survival: 79.48%





📈 Sample Visualizations
Age distribution

Survival counts

Box plots for Age vs Survival

Correlation heatmap

Survival prediction probabilities

📂 How to Run
Clone this repository

Install dependencies

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Python script:

bash
Copy
Edit
python titanic_survival_analysis.py
📊 Project Outcomes
Identified key survival factors like gender, passenger class, and fare

Built a model with reasonable predictive power

Created an interactive survival estimator for user-defined passengers

🙌 Contributions
Feel free to fork the repository, raise issues, or create pull requests. All contributions are welcome

