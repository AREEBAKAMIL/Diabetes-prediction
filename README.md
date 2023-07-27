# Diabetes prediction

In this repository, I analysed the Diabetes dataset using pandas and tried various supervised ML models, using scikit-learn, to predict whether one has diabetes or not, given their symptoms. Finally, I compared the accuracy obtained from each model.

# About the dataset
The Diabetes dataset is a real dataset which consists of 9 columns and 768 rows. the column names are as follows:

1. Pregnancies
2. Glucose
3. BloodPressure
4. SkinThickness
5. Insulin
6. BMI
7. DiabetesPedigreeFunction
8. Age
9. Outcome
       
# Steps:
1. Download the csv file.
2. Load the csv into pandas dataframe
3. Check for missing/null values
6. split the dataset into test and train
7. Train supervised ML models and compare results

# Conclusion
Logistic Regression generalizes best for the given data set, with an accuracy score of 0.78
