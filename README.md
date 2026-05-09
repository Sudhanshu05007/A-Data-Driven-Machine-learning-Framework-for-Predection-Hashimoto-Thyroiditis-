Hashimoto’s Thyroiditis Prediction using XGBoost

A Machine Learning project that predicts thyroid-related conditions using the XGBoost Classifier. The model classifies patient data into:

Negative
Hypothyroid
Hyperthyroid
Features
Data preprocessing and cleaning
Multi-class classification using XGBoost
Model evaluation using Accuracy, Precision, Recall, and F1-Score
Confusion Matrix and Feature Importance visualization
ROC and Precision-Recall Curves
Model saving and loading using Pickle
Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Installation
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
Project Structure
├── hashimoto's thyroiditis.ipynb
├── train_data.csv
├── test_data.csv
├── model.pkl
└── README.md
Model Training
xgb_clf.fit(X_train, y_train)
Model Evaluation

The model is evaluated using:

Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix
Applications
Thyroid disease prediction
Healthcare analytics
Clinical decision support systems
Future Improvements
Deploy using Flask or Streamlit
Add a web interface
Hyperparameter tuning
Real-time prediction system
Author


