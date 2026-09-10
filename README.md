Diabetes Risk Prediction using Machine Learning
About the Project
This project focuses on predicting diabetes risk levels using machine learning classification algorithms.,

The dataset was obtained from Kaggle and contains health, lifestyle, demographic, and medical information of 15,000 patients.

The main aim of this project is to apply different classification algorithms and compare how well they perform on the same dataset.

Dataset
The dataset was obtained from Kaggle and contains 15,000 records with 19 columns.

Some of the features include:

Age
Gender
City
BMI
Family History of Diabetes
Physical Activity Level
Diet Type
Smoking Status
Alcohol Consumption
Hours of Sleep per Night
Stress Level
Fasting Blood Sugar
HbA1c Level
Blood Pressure
Waist Circumference
Income Bracket
The target variable used for classification is:

diabetes_risk

The target variable contains three categories:

Low
Moderate
High
Data Preprocessing
Before applying the machine learning algorithms, the dataset was cleaned and prepared.

The following steps were performed:

Checked the dataset for missing values
Checked for duplicate records
Handled missing values using median imputation
Converted categorical variables into numerical values using One-Hot Encoding
Converted the target variable into numerical labels using Label Encoding
Divided the dataset into training and testing data
Applied StandardScaler for feature scaling
The dataset was divided into:

80% Training Data
20% Testing Data
This resulted in:

12,000 training records
3,000 testing records
Algorithms Used
The following machine learning algorithms were applied:

Gaussian Naive Bayes
Decision Tree
K-Nearest Neighbors (KNN)
Each model was trained using the training dataset and evaluated using the testing dataset.

Performance Comparison
The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Accuracy Comparison
Model	Accuracy
Naive Bayes	74.33%
Decision Tree	76.50%
KNN	68.37%

Result
Among the three algorithms, the Decision Tree performed the best.

It achieved an accuracy of:

76.50%
Naive Bayes achieved 74.33%, while KNN achieved 68.37%.

The Decision Tree also performed well in predicting the Moderate diabetes-risk category.

Confusion matrices were created for all three models to understand how the models classified the different diabetes-risk categories.

Tools Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Kaggle
The dataset and machine learning notebook were developed using Kaggle.

Conclusion
This project demonstrates how machine learning classification algorithms can be used to predict diabetes risk based on patient health and lifestyle information.

After comparing three different algorithms, the Decision Tree Classifier achieved the highest accuracy of 76.50% and was the best-performing model for this dataset.

