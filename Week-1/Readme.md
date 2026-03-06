# Smart Irrigation System – Week 1

## Overview

This project is part of the **Edunet Foundation Smart Irrigation Internship (Week 1)**.
The objective of this task is to build a machine learning model capable of predicting whether irrigation is required for different agricultural land parcels based on sensor data.

The system analyzes environmental conditions collected from sensors and determines whether irrigation should be activated for each parcel.

---

## Project Objective

The goal of the model is to:

* Analyze sensor readings from agricultural fields
* Predict irrigation requirements for multiple farm parcels
* Support efficient water management using data-driven decisions

The model predicts irrigation requirements for **three farm parcels simultaneously**.

---

## Dataset Description

The dataset used for this project contains sensor readings collected from agricultural fields.

Dataset characteristics:

* **Total Records:** 2000
* **Sensor Features:** 20 environmental sensor readings
* **Target Variables:** 3 output columns representing irrigation decisions

Target columns:

* `parcel_0`
* `parcel_1`
* `parcel_2`

Each target variable represents whether irrigation is required for the corresponding parcel.

---

## Machine Learning Model

A **MultiOutputClassifier with a Random Forest algorithm** was implemented to predict irrigation requirements for all parcels simultaneously.

Key aspects of the model:

* Handles multiple output variables
* Learns relationships between sensor data and irrigation needs
* Provides predictions for all parcels in a single model

The model achieved **over 80% accuracy for most target labels**, demonstrating reliable prediction capability.

---

## Technologies and Tools Used

* **Python**
* **Jupyter Notebook** – Model development and experimentation

---

## Example Prediction

Example input sensor readings:

```id="8sd2qu"
[2, 1, 3, 4, ..., 4, 1]
```

Model prediction output:

```id="r44s9c"
[1, 0, 0]
```

Interpretation:

* **Parcel 0:** Irrigation required
* **Parcel 1:** No irrigation required
* **Parcel 2:** No irrigation required

---

## Project Files

| File                     | Description                                                        |
| ------------------------ | ------------------------------------------------------------------ |
| `irrigation_machine.csv` | Dataset containing sensor readings and irrigation labels           |
| `smart_irrigation.ipynb` | Jupyter Notebook containing data analysis and model implementation |
| `README.md`              | Project documentation                                              |

---

## Learning Outcome

Through this task, I gained hands-on experience in:

* Working with real-world sensor datasets
* Implementing multi-output machine learning models
* Applying Random Forest algorithms for predictive analysis
* Understanding the role of AI in smart agriculture and water resource management
