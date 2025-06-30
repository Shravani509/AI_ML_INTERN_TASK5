# AI_ML_INTERN_TASK5
#### 📊 Heart Disease Prediction Analysis Summary
This project uses a Decision Tree and Random Forest classifier to predict heart disease based on patient medical data.
### ✅ 1. Decision Tree & Visualization
A decision tree was trained to classify heart disease cases. The tree shows how features like chest pain (cp), number of blocked vessels (ca), and thalassemia type (thal) guide predictions.
### ✅ 2. Overfitting Analysis
By varying tree depth, we observed that:
Shallow trees underfit the data.
Deep trees overfit (perfect on training but worse on test).
Optimal depth is around 6–9, where test accuracy is highest.
### ✅ 3. Random Forest Comparison
A Random Forest model was trained and showed higher test accuracy than a single decision tree, confirming better generalization and performance.
#### ✅ 4. Feature Importance
The most important features identified by the Random Forest were:
ca (blocked vessels)
thal (thalassemia)
oldpeak (ST depression)
These had the greatest influence on predicting heart disease.
### ✅ 5. Cross-Validation
5-fold cross-validation was used to evaluate the Random Forest. It showed stable and high performance, making the model reliable.

