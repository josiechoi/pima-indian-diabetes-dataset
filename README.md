# pima-indian-diabetes-dataset

Dataset to use to try out Rapid Miner

Found in Kaggle 
https://www.kaggle.com/uciml/pima-indians-diabetes-database

Comment: 
- Small dataset with only 768 records. No missing values. All numerical; Outcome is the dependent variable. 
- Based on Lai H et al, age should probably be turned into categorical variable 
- Lai H et al tested their algorithm with this dataset and reported consistent results.
- Below is the variables in the model of Lai H et al. 
- Sex, Age (age at examination date), BMI (Body Mass Index) TG (Triglycerides), FBS(Fasting blood sugar), sBP (Systolic Blood Pressure), HDL (High Density Lipoprotein), LDL (Low Density Lipoprotein)  

Question: 
- Not sure how the test was conducted? 
- Patients in this dataset are all female, so Sex can be engineered. Age = Age (turned into categorical), BMI= BMI, FBS = Glucose(?), sBP != Blood Pressure (since this is distolic), Insulin & Pregnancies likely to be removed by Lai et al, DiabetesPedigreeFunction - not sure what this is ? 
- Therefore, this dataset does not have TG, sBP, HDL, LDL 
