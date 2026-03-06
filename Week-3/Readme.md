# Smart Irrigation System – Week 3 (Final Submission)

## Overview

This project represents the **final phase of the Edunet Foundation Smart Irrigation Internship**.
During this week, the Smart Irrigation Machine Learning model developed in previous weeks was finalized, tested, and prepared for submission.

The system predicts whether irrigation is required for multiple agricultural parcels based on environmental sensor readings, helping optimize water usage in smart farming.

---

## Project Objective

The objective of the final week was to:

* Complete the Smart Irrigation prediction system
* Finalize the machine learning model developed in previous weeks
* Validate predictions using sensor data
* Prepare the project for submission

---

## Dataset Description

The dataset used for the project contains environmental sensor readings collected from agricultural fields.

Dataset details:

* **Total Records:** 2000
* **Input Features:** 20 environmental sensor readings (`sensor_0` – `sensor_19`)
* **Target Labels:** 3 irrigation indicators

Target columns:

* `irrigation_machine_0`
* `irrigation_machine_1`
* `irrigation_machine_2`

Each target variable indicates whether irrigation is required for the corresponding farm parcel.

---

## Machine Learning Model

The irrigation prediction model was built using:

**MultiOutputClassifier with Random Forest**

This approach allows the model to predict irrigation requirements for **multiple farm parcels simultaneously**.

Model features:

* Handles multi-label outputs
* Learns patterns from sensor data
* Provides irrigation predictions for all parcels in one model

The model achieved **over 80% accuracy across most irrigation targets**.

---

## Final Implementation

During the final week:

* The machine learning model was **trained and tested**
* Remaining improvements from previous weeks were completed
* The trained model was **saved for reuse using Pickle (`.pkl`)**
* Final predictions were verified using sample sensor inputs

---

## Technologies and Tools Used

* **Python**
* **Jupyter Notebook**

---

## Example Prediction

Example sensor input:

```id="3d5b8g"
[2, 1, 3, 4, ..., 4, 1]
```

Model prediction output:

```id="p0l1ne"
[1, 0, 0]
```

Interpretation:

* **Parcel 0:** Irrigation required
* **Parcel 1:** No irrigation required
* **Parcel 2:** No irrigation required

---

## Project Files

| File                         | Description                                      |
| ---------------------------- | ------------------------------------------------ |
| `irrigation_machine.csv`     | Dataset containing sensor readings               |
| `Irrigation_System.ipynb`    | Jupyter notebook with model training and testing |
| `farm_Irrigation_System.pkl` | Saved trained machine learning model             |
| `README.md`                  | Documentation for Week-3 final submission        |

---

## Learning Outcome

Through this internship project, I gained practical experience in:

* Building machine learning models using real-world datasets
* Working with **multi-output classification**
* Implementing Random Forest models
* Saving trained models for reuse
* Applying AI techniques to **smart agriculture systems**

