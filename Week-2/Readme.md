# 🌾 Smart Irrigation System - Week 2 


**🔍 Objective**

Build a machine learning model that predicts whether irrigation is required in 3 farm parcels based on 20 environmental sensor readings.


**📊 Dataset**

2000 records

20 sensor features: sensor_0 to sensor_19

3 target labels: irrigation_machine_0, irrigation_machine_1, irrigation_machine_2



**🧠 Model**

MultiOutputClassifier using Random Forest

Achieved accuracy above 80% for most irrigation targets



**🛠 Tools Used**

Python

Pandas

Scikit-learn

Jupyter Notebook



**📌 Sample Prediction**

Input: [2, 1, 3, 4, ..., 4, 1]

Output: [1, 0, 0] → Irrigation required in Parcel 0



**🗂 Files**

irrigation_machine.csv – Dataset

Irrigation_System.ipynb – Model training and prediction code

farm_Irrigation_System.pkl – Saved trained ML model

README.md – Project description and documentation

