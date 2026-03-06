# Smart Irrigation System – Week 2

## Overview

This project is part of the **Edunet Foundation Smart Irrigation Internship (Week 2)**.
The objective of this task is to develop a machine learning model that predicts irrigation requirements for multiple agricultural parcels based on environmental sensor data.

The system analyzes sensor readings and determines whether irrigation is needed for each farm parcel, helping optimize water usage in agriculture.

---

## Project Objective

The goal of this project is to:

* Build a predictive model using environmental sensor data
* Predict irrigation requirements for multiple farm parcels simultaneously
* Implement and store a trained machine learning model for future predictions

---

## Dataset Description

The dataset used in this project contains environmental sensor readings collected from agricultural fields.

Dataset characteristics:

* **Total Records:** 2000
* **Input Features:** 20 sensor readings (`sensor_0` to `sensor_19`)
* **Target Labels:** 3 irrigation indicators

Target variables:

* `irrigation_machine_0`
* `irrigation_machine_1`
* `irrigation_machine_2`

Each target label represents whether irrigation is required for the corresponding parcel.

---

## Machine Learning Model

A **MultiOutputClassifier using the Random Forest algorithm** was implemented to predict irrigation requirements for all farm parcels simultaneously.

Model capabilities:

* Handles multiple target outputs
* Learns relationships between sensor readings and irrigation needs
* Provides predictions for all parcels in a single model

The model achieved **over 80% accuracy for most irrigation targets**.

---

## Model Deployment Preparation

To enable reuse of the trained model, the model was saved as a serialized file using **Pickle (`.pkl`) format**.

This allows the trained model to be loaded later without retraining, enabling faster predictions in real-world applications.

---

## Technologies and Tools Used

* **Python**
* **Jupyter Notebook** – Model training and experimentation

---

## Example Prediction

Example sensor input:

```id="i1xyv3"
[2, 1, 3, 4, ..., 4, 1]
```

Model prediction output:

```id="p9ak6n"
[1, 0, 0]
```

Interpretation:

* **Parcel 0:** Irrigation required
* **Parcel 1:** No irrigation required
* **Parcel 2:** No irrigation required

---

## Project Files

| File                         | Description                                                    |
| ---------------------------- | -------------------------------------------------------------- |
| `irrigation_machine.csv`     | Dataset containing environmental sensor readings               |
| `Irrigation_System.ipynb`    | Jupyter Notebook containing model training and prediction code |
| `farm_Irrigation_System.pkl` | Saved trained machine learning model                           |
| `README.md`                  | Project documentation                                          |

---

## Learning Outcome

Through this task, I gained practical experience in:

* Building **multi-output machine learning models**
* Training and evaluating Random Forest classifiers
* Working with environmental sensor datasets
* Saving trained models for reuse in real-world applications
* Applying machine learning techniques for **smart agriculture systems**
