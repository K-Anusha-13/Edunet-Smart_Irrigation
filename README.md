# 🌾 Smart Irrigation System using Soil Moisture and Weather Data

This project is a machine learning-based irrigation control system that automates the ON/OFF status of 20 farm sprinklers based on real-time soil moisture and weather sensor inputs. Built with a Random Forest model and wrapped in a MultiOutputClassifier, the system predicts irrigation needs efficiently and displays the results using an interactive Streamlit web interface.

---

## 🚀 Features

- Takes 20 real-time sensor inputs from farm parcels  
- Predicts sprinkler ON/OFF status using a trained ML model  
- Interactive UI with sliders, emoji feedback, and charts  
- Visual summaries using bar and line plots  
- Accurate and user-friendly irrigation decision system

---

## 🛠️ Technologies Used

- **Python** – Core programming  
- **Pandas, NumPy** – Data manipulation  
- **Scikit-learn** – Model training and evaluation  
- **Random Forest + MultiOutputClassifier** – For multi-sprinkler control  
- **MinMaxScaler** – Input normalization  
- **Joblib** – Model saving/loading  
- **Streamlit** – Interactive frontend  
- **Matplotlib** – Chart visualization

---

## 📁 Files Included

- `irrigation_machine.csv` – Dataset with sensor and sprinkler data  
- `Smart_Irrigation.ipynb` – Model training and preprocessing notebook  
- `Farm_Irrigation_System.pkl` – Saved machine learning model  
- `app.py` – Streamlit-based web application  

---

## 🔮 Future Improvements

- Integrate real-time IoT sensor and weather data  
- Add cloud storage and mobile compatibility  
- Enable full automation of physical sprinkler hardware
