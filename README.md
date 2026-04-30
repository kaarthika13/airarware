# 🌍 AirAware –  Air Quality Monitoring & Prediction System

## 🚀 Overview

**AirAware** is an web application that monitors, analyzes, and predicts air quality using machine learning.
It provides real-time insights into pollution levels and helps users understand environmental conditions through data-driven predictions.

The system is designed to support **health awareness, pollution monitoring, and smart decision-making**.

---

## ✨ Key Features

* 🌫️ Air Quality Index (AQI) Prediction
* 🤖 Machine Learning Model for Pollution Analysis
* 📊 Interactive Data Visualization
* 🔔 AQI Alerts System (health-based warnings)
* 🌐 Web Application using Streamlit
* ⚡ Fast and user-friendly interface

---

## 🔄 System Workflow

1. 📥 Collect air quality data (PM2.5, PM10, CO, NO₂, etc.)
2. 🧹 Data preprocessing and cleaning
3. 📊 Feature extraction
4. 🤖 Model training (`train_model.py`)
5. 📈 AQI prediction (`predict.py`)
6. 🔔 Alert generation (`aqi_alerts.py`)
7. 🌐 Display results via Streamlit UI (`home.py`, `pages/`)

---

## 🛠️ Tech Stack

### 💻 Programming Language

* Python

### 📚 Libraries & Frameworks

* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Streamlit

### 🤖 Machine Learning

* Prophet model (for AQI prediction)
* Trained model stored as `model.pkl`

---

## 📁 Project Structure


AirAware/
│
├── data/                 # Dataset files  
├── pages/                # Streamlit multi-page UI  
├── home.py               # Main UI application  
├── train_model.py        # Model training script  
├── predict.py            # Prediction logic  
├── preprocessing.py      # Data cleaning & processing  
├── aqi_alerts.py         # AQI alert system  
├── model.pkl             # Trained ML model  
├── requirements.txt  
├── Procfile              # Deployment


## ⚙️ Installation

### 1️⃣ Clone Repository

git clone https://github.com/your-username/AirAware.git
cd AirAware

### 2️⃣ Install Dependencies

pip install -r requirements.txt

---

## ▶️ Usage

### 📌 Run the Application

streamlit run home.py

### 📌 Train Model (Optional)

python train_model.py

---

## 📊 How It Works

* Environmental data is collected and cleaned
* Machine learning model is trained on pollution data
* Input values are processed to predict AQI
* Alerts are generated based on AQI levels
* Results are displayed using an interactive dashboard

---

## 🔔 AQI Alerts

The system provides health-based alerts such as:

* 🟢 Good → Safe air quality
* 🟡 Moderate → Sensitive groups affected
* 🔴 Unhealthy → Health risk warning

---

## 📈 Applications

* 🌍 Smart City Monitoring
* 🏥 Public Health Awareness
* 🏭 Industrial Pollution Tracking
* 📱 Environmental Apps
* 🧪 Research & Analysis

---

## ⚠️ Limitations

* Depends on dataset accuracy
* Limited real-time sensor integration
* Model performance varies with data quality

---

## 🚧 Future Enhancements

* 📡 IoT sensor integration
* 📱 Mobile app development
* 🔔 Real-time notifications
* 🌐 Live API integration
* 🧠 Deep learning models

---

## 🤝 Author

**Kaarthika Manchirala**
🔗 GitHub: https://github.com/kaarthika13

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
