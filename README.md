# CLASSIFICATION USING DIABETIC DATASET

# Data Set Information:

The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. The Information was extracted from the database for encounters that satisfied the following criteria.
 (1) It is an inpatient encounter (a hospital admission).
 (2) It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
 (3) The length of stay was at least 1 day and at most 14 days.
 (4) Laboratory tests were performed during the encounter.
 (5) Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

# Objective

Using Machine Learning we are aiming to classify the patient into 1 of 3 categroies
1) Readmitted within 30 days.
2) Readmitted after 30 days.
3) Not been Readmitted.

# Results And Conclusion

We tried a lot of variations for Random Forest and Decision Tree, and we were able to predict if a patient is
1) Readmitted within 30 days.
2) Readmitted after 30 days.
3) Not been Readmitted.
with ~55% of Accuracy.

We also observed that ~40 features were adding up for 70% feature importance using Random Forest.
