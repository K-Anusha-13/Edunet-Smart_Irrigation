# 🌾 Smart Irrigation System – Machine Learning Project

## Overview

This repository contains the work completed during the **Edunet Foundation Smart Irrigation Internship**.
The project focuses on developing a **machine learning-based irrigation prediction system** that helps automate irrigation decisions using environmental sensor data.

The system analyzes soil moisture and weather-related sensor inputs and predicts whether irrigation should be activated for different farm parcels. The final implementation also includes a **Streamlit-based interactive interface** for testing irrigation predictions.

This project demonstrates how **machine learning can support smart agriculture and efficient water resource management**.

---

## Internship Details

**Organization:** Edunet Foundation
**Program:** Smart Irrigation Internship
**Duration:** 15 July 2025 – 16 August 2025

During this internship, I developed a machine learning model that predicts irrigation requirements based on environmental sensor data and implemented an interactive application for real-time predictions.

---

## Repository Structure

```id="repo_structure"}
Edunet-Smart_Irrigation
│
├── Week-1
│   ├── irrigation_machine.csv
│   ├── smart_irrigation.ipynb
│   └── README.md
│
├── Week-2
│   ├── irrigation_machine.csv
│   ├── Irrigation_System.ipynb
│   ├── farm_Irrigation_System.pkl
│   └── README.md
│
└── Week-3
    ├── irrigation_machine.csv
    ├── Smart_Irrigation.ipynb
    ├── Farm_Irrigation_System.pkl
    ├── app.py
    └── README.md
```

Each folder represents the work completed during a specific week of the internship.

---

## Weekly Progress

| Week       | Focus Area                                                                                           |
| ---------- | ---------------------------------------------------------------------------------------------------- |
| **Week 1** | Data exploration and building a machine learning model to predict irrigation needs using sensor data |
| **Week 2** | Model training, evaluation, and saving the trained machine learning model                            |
| **Week 3** | Final project completion with an interactive Streamlit application for irrigation prediction         |

---

## Dataset Description

The dataset used for this project contains environmental sensor readings collected from agricultural fields.

Dataset characteristics:

* **2000 records**
* **20 environmental sensor inputs**
* **Multiple irrigation outputs representing sprinkler activation**

Sensor readings are used as input features, while irrigation decisions are predicted for different farm parcels.

---

## Machine Learning Model

The irrigation prediction system was implemented using:

**Random Forest + MultiOutputClassifier**

Key capabilities:

* Predicts irrigation requirements for multiple farm parcels simultaneously
* Handles multi-label classification problems
* Provides accurate predictions based on environmental conditions

The model achieved **over 80% accuracy for most irrigation outputs**.

---

## Streamlit Application

The final project includes a **Streamlit-based web application** that allows users to interact with the irrigation model.

Application features:

* Adjustable sensor input sliders
* Real-time irrigation predictions
* Visualization of sprinkler activation results
* User-friendly interface for testing irrigation scenarios

This makes the system easier to test and demonstrates a practical **AI-powered irrigation solution**.

---

## Technologies and Tools Used

* **Python**
* **Streamlit**
---

## Key Skills Demonstrated

* Machine Learning model development
* Multi-output classification
* Data preprocessing and feature scaling
* Model training and evaluation
* Model serialization and reuse
* Building interactive ML applications
* Applying AI techniques in smart agriculture

---

## Future Improvements

* Integration with real-time **IoT soil moisture sensors**
* Deployment of the model on **cloud platforms**
* Mobile-friendly irrigation dashboard
* Direct integration with automated irrigation hardware

---

## Author

**Anusha K**

Machine Learning & Data Enthusiast
