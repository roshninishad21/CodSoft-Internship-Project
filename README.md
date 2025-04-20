🚢 Titanic Survival Prediction

This project is part of my CodSoft Data Science Internship, where I built a predictive model to determine passenger survival in the Titanic disaster using supervised machine learning algorithms: Logistic Regression and Random Forest Classifier.

📌 Objective
To predict whether a passenger survived the Titanic shipwreck based on features like gender, age, class, fare, and more using classification models.

📁 Dataset
Source: Kaggle - Titanic: Machine Learning from Disaster

The dataset contains information about:

PassengerId, Name, Sex, Age

Pclass (ticket class), Fare, Embarked

SibSp (siblings/spouses aboard), Parch (parents/children aboard)

Survived (target variable: 0 = No, 1 = Yes)

🧪 Models Used

. Logistic Regression – A linear model for binary classification.

. Random Forest Classifier – An ensemble method based on decision trees.

⚙️ Steps Involved

. Exploratory Data Analysis (EDA)

. Visualizing survival distribution

. Analyzing feature impact (e.g., gender, class)

. Data Preprocessing

. Handling missing values

. Encoding categorical variables

. Feature scaling

. Model Training & Evaluation

. Splitting dataset into train and test sets

. Training Logistic Regression and Random Forest models

Evaluating using:

. Accuracy

. Confusion Matrix

. Classification Report

📊 Results

Model	Accuracy
Logistic Regression	~80%
Random Forest	~83%
Random Forest slightly outperformed Logistic Regression in accuracy and overall robustness.

🧰 Libraries Used

. Python

. Pandas, NumPy

. Matplotlib, Seaborn

. Scikit-learn (sklearn)

🧠 Key Learnings

Importance of data preprocessing in model performance

Comparison between a simple linear classifier and an ensemble method

How to handle missing and categorical data effectively

📌 Conclusion
This project helped strengthen my foundational understanding of classification algorithms and data handling in machine learning. It demonstrates how basic ML techniques can be applied to real-world historical data to make insightful predictions.

