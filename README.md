RPC Stage Variable Predictor
A machine learning project focused on predicting the stage of a Rocket Propellant Component (RPC) using sensor data. This repository contains the complete pipeline for data preprocessing, model training, evaluation, and inference, demonstrating a practical application of ML in industrial and aerospace engineering.

📌 Project Overview
In industrial processes like rocket propellant manufacturing, components go through various stages (e.g., mixing, casting, curing). Accurately identifying the current stage is critical for process control and quality assurance.

This project develops a classifier to predict the operational stage of an RPC based on multivariate time-series sensor data (such as pressure, temperature, flow rate, etc.). The solution includes data cleaning, feature engineering, model selection, and hyperparameter tuning to achieve high predictive accuracy.

🚀 Features
End-to-End ML Pipeline: From raw data to a trained, serialized model.

Data Preprocessing: Handles missing values, outliers, and encodes the target variable.

Feature Engineering: Creates relevant time-series features to improve model performance.

Model Comparison: Evaluates multiple machine learning algorithms including:

Logistic Regression

Random Forest Classifier

Gradient Boosting Classifier (XGBoost)

Support Vector Machine (SVM)

Hyperparameter Tuning: Utilizes GridSearchCV for optimizing model parameters.

Model Persistence: Saves the trained model and scaler for future inference.

Comprehensive Evaluation: Provides detailed metrics, confusion matrices, and classification reports.



🤖 Models and Performance
The project compares several classification algorithms. Based on the analysis, the Random Forest or XGBoost model typically achieves the best performance for this task, with high accuracy and robustness to overfitting.

Example Performance Metrics (may vary):

Accuracy: ~98%

Precision: ~0.98

Recall: ~0.98

F1-Score: ~0.98



📈 Results
The project successfully demonstrates the capability of machine learning to accurately classify the stage of a rocket propellant component. Key outcomes include:

Identification of the most important sensor features for stage prediction.

A robust, production-ready model that can be integrated into a larger monitoring system.

A clear, reproducible workflow for similar industrial classification problems.

👨‍💻 Author
Navnit Mishra

GitHub: @Navnit24

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page (if any).

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Thanks to the contributors of the open-source libraries used in this project (Pandas, Scikit-learn, XGBoost, etc.).

Inspiration from industrial process monitoring and predictive maintenance use cases.
