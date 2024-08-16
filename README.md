### Heart Disease Classification Project

**Project Overview:**
- Developed an end-to-end machine learning pipeline to predict heart disease using patient health data, achieving a peak model accuracy of 89% during cross-validation.

**Data Preprocessing:**
- Conducted data cleaning and preprocessing on a dataset of **303 patients**, including handling missing values, encoding categorical variables, and scaling numerical features using StandardScaler.
- Engineered features to enhance model performance, including polynomial features and interaction terms, which improved model accuracy by **5%**.

**Model Selection and Evaluation:**
- Trained and evaluated multiple machine learning models using Scikit-Learn, including:
  - **Logistic Regression**: Achieved a peak accuracy of **89%** with an AUC score of **0.92**.
  - **Random Forest**: Tuned hyperparameters using GridSearchCV, leading to an accuracy of **87%**.
  - **Support Vector Machine (SVM)**: Achieved an accuracy of **85%**.
  - **Gradient Boosting**: Reached an accuracy of **88%**.

**Hyperparameter Tuning:**
- Performed extensive hyperparameter optimization using **GridSearchCV** and **RandomizedSearchCV**:
  - Evaluated **50+ combinations** of hyperparameters for Random Forest, including `n_estimators`, `max_depth`, and `min_samples_split`.
  - Optimized Logistic Regression's `C` parameter and solver, resulting in a **3%** improvement in cross-validated accuracy.

**Model Evaluation and Validation:**
- Utilized **5-fold cross-validation** to ensure model robustness and avoid overfitting, achieving consistent performance metrics across folds.
- Generated comprehensive evaluation reports, including confusion matrices, precision, recall, and F1-scores, with the Logistic Regression model achieving an F1-score of **0.88**.
- Plotted ROC curves and calculated AUC to assess model performance, with the best model achieving an AUC of **0.92**.

**Experimentation and Iteration:**
- Conducted multiple iterations of model training and evaluation, including experimenting with advanced models like **XGBoost** and **CatBoost** for potential future improvements.
- Proposed and explored the collection of additional data and feature engineering techniques to further enhance model accuracy.
