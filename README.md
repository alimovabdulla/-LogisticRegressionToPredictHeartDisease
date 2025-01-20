## Logistic Regression Model for Heart Disease Prediction  

**Overview**:  
This model predicts the 10-year risk of developing heart disease based on individual characteristics such as demographics, clinical measurements, and lifestyle habits.  

**Features**:  
- **Demographics**: Gender, Age, Education level.  
- **Lifestyle**: Smoking habits, daily cigarette consumption.  
- **Clinical Factors**: Blood pressure (systolic/diastolic), cholesterol, glucose levels, BMI, and heart rate.  
- **Medical History**: Presence of diabetes, hypertension, prior stroke, and use of heart medications.  

**Key Highlights**:  
- Built using `LogisticRegression` from `scikit-learn`.  
- GridSearchCV was applied to fine-tune hyperparameters for improved accuracy.  
- The model uses `StandardScaler` for data normalization and ensures robust predictions.  

**Usage**:  
- Provides both binary predictions (risk/no risk) and probabilistic outputs for informed decision-making.  
- Suitable for educational purposes and exploratory research in predictive healthcare.  

**Metrics Evaluated**:  
- Accuracy, Confusion Matrix, Precision, Recall, and AUC-ROC scores.  

