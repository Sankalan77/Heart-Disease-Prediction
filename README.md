# Heart-Disease-Prediction
💓 **_Heart Disease Prediction Using Machine Learning_**

📘 **_Project Overview_**

This project focuses on building a predictive system that can determine the likelihood of a person having heart disease based on clinical and physiological parameters. Using multiple machine learning algorithms, the model helps in early diagnosis and risk assessment, supporting doctors and patients in making informed healthcare decisions.

🎯 **_Objectives_**

•	Analyze patient data to identify patterns associated with heart disease.<br>
•	Compare the performance of different machine learning models.<br>
•	Build a predictive model that can classify patients as “at risk” or “not at risk.”

🧩 **_Dataset_**

The dataset used contains various medical attributes such as:

•	Age<br>
•	Sex<br>
•	Chest Pain Type (cp)<br>
•	Resting Blood Pressure (trestbps)<br>
•	Cholesterol (chol)<br>
•	Fasting Blood Sugar (fbs)<br>
•	Resting ECG (restecg)<br>
•	Maximum Heart Rate (thalach)<br>
•	Exercise Induced Angina (exang)<br>
•	Oldpeak<br>
•	Slope<br>
•	CA<br>
•	Thal

These attributes help determine whether a patient is likely to have heart disease.

⚙️ **_Technologies Used_**

• Python<br>
•	NumPy, Pandas<br>
•	Matplotlib, Seaborn (for EDA)<br>
•	Scikit-learn<br>
•	XGBoost

🔍 **_Exploratory Data Analysis (EDA)_**

The notebook performs EDA to understand the distribution of features, detect correlations, and visualize the relationships between key attributes and the target variable (presence of heart disease).

🤖 **_Machine Learning Models Used_**

Several supervised classification algorithms are implemented and compared, including:

•	Logistic Regression<br>
•	Naive Bayes<br>
•	Support Vector Machine (SVM)<br>
•	K-Nearest Neighbors (KNN)<br>
•	Decision Tree<br>
•	Random Forest<br>
•	XGBoost

Each model is trained and evaluated to determine accuracy and robustness on test data.

🧠 **_Model Evaluation_**

The models are assessed using metrics such as:

•	Accuracy<br>
•	Precision<br>
•	Recall<br>
•	F1-Score

Finally, the best-performing algorithm is chosen based on its ability to correctly predict heart disease cases.

🏁 **_Results_**

After training and evaluating multiple models, the project found that ensemble-based algorithms such as **Random Forest** and **XGBoost** achieved the highest prediction accuracy. These models demonstrated strong generalization capability and effectively handled feature correlations within the dataset.<br>
Overall, the system was able to **accurately classify patients with and without heart disease**, showcasing the potential of machine learning in medical risk prediction and decision support.

🩺 **_Conclusion_**

The project demonstrates that **machine learning techniques can significantly enhance medical prediction systems**, helping in early diagnosis and preventive care.<br> By integrating AI-driven solutions, healthcare professionals can make faster and more accurate assessments of heart disease risk.
