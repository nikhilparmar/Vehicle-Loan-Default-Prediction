# Vehicle-Loan-Default-Prediction

# --------------------INDEX OF THE SOLUTION-------------
# A. DATA INFORMATION
# B. BUSINESS OBJECTIVE
# C. MACHINE LEARNING OBJECTIVE
# 1. READING DATASET
- -> 1.1. Data Description
- -> 1.2. Renaming Columns for better readability.

# 2. EXPLORATORY DATA ANALYSIS
- -> 2.1. Checking whether the data is balanced or not¶
- -> 2.1. Descriptive Stats
- -> 2.1. Structure of the data

# 3. DATA PREPROCESSING
- -> 3.1. Missing/NaN value check
- -> 3.2. NAN Value Imputation with Backward Fill (bfill) method.
- -> 3.3. Converting PERFORM_CNS_SCORE_DESCRIPTION into Multiple Categories
- -> 3.4. Understanding all the Distinct Values of our features
- -> 3.5. Converting CREDIT HISTORY LEN and AVG ACCOUNT AGE into Numeric Format
- -> 3.6. CONVERTING THE DATE OF BIRTH TO AGE AND DISBURSALDATE TO LOAN_AGE

# 4. SPLITTING THE DATASET INTO TRAIN-TEST (70-30)

# 5. FEATURE SELECTION
- -> 5.1. Identifying Useless Features and dropping them.
- -> 5.2. Listing the Numerical and Categorical Type Features.

# 6. SELECTING THE TOP NUMERICAL FEATURES using SelectKBest (Annona)

# 7. STANDARDIZING THE TRAIN AND TEST DATA

# 8. ENCODING THE CATEGORICAL VARIABLE USING ONE HOT ENCODER

# 9. SELECTING THE TOP CATEGORICAL FEATURES

# 10. MERGING THE NUMERICAL AND CATEGORICAL PROCESSSED FEATURES
# 11. CORELATION MATRIX

# 12. MODEL IMPLEMENTATION
- -> 12.1. RANDOM MODEL as Benchmark.
- -> 12.2. Logistic Regression with hyperparameter tuning.
- -> 12.Creating Objects of the MODELS
- -> 12.DATASET Balancing using Classifier Parameter
- -> 12.3. Logistic Regression
- -> 12.4. DECISION TREE
- -> 12.5. KNN
- -> 12.6. BAGGING: RANDOM FOREST CLASSIFIER
- -> 12.7. BOOSTING: XGBOOST with Hyperparameter Tuning (scale_pos_weight) Parameter.
- ->-> 12.7.1. XGBoost with scale_pos_weight=3
- ->-> 12.7.2. XGBoost with scale_pos_weight=2

# 13. COMPARISION
