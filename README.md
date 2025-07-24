# 🌾 Data-Driven Crop Advisory System 🌱

**Using Soil and Environmental Parameters**

---

## 📘 Overview

This is a smart crop advisory web application that helps farmers and researchers recommend the most suitable crops and fertilizers based on soil and climate parameters like nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, moisture, and rainfall. Powered by machine learning, it supports sustainable and precision agriculture.

---

## 🎯 Features

✅ Crop recommendation using ML
✅ Fertilizer recommendation
✅ User-friendly web interface
✅ Real-time input support
✅ Clean and minimal frontend
✅ Ready for integration with IoT and weather APIs

---

## 🧪 Dataset Features

| Parameter   | Unit | Description                |
| ----------- | ---- | -------------------------- |
| N           | ppm  | Nitrogen content in soil   |
| P           | ppm  | Phosphorus content in soil |
| K           | ppm  | Potassium content in soil  |
| Temperature | °C   | Ambient temperature        |
| Humidity    | %    | Relative humidity          |
| Moisture    | %    | Soil moisture level        |
| Rainfall    | mm   | Recent rainfall data       |

---

## 🧐 Machine Learning Model

* Algorithm used: `RandomForestClassifier` (can be switched with Decision Tree, SVM, etc.)
* Training data: CSV dataset with 1000+ synthetic and real field entries
* Accuracy: \~95% on validation set

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JS
* **Backend:** Python + Flask
* **Machine Learning:** scikit-learn, pandas, numpy
* **Deployment:** Localhost or cloud (Heroku, Render, etc.)
* **Version Control:** Git & GitHub

---

## 🚀 Installation Guide

 1. Clone the Repository

bash
git clone https://github.com/your-username/crop-advisory-system.git
cd crop-advisory-system


 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

 3. Run the App

```bash
python app.py
```

Visit `http://127.0.0.1:5000` in your browser.

💡 Future Improvements

* Integration with live weather APIs
* Multilingual farmer support (Hindi, Odia, etc.)
* Real-time soil sensor integration
* Android app version using Flutter or React Native

 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Developed By- Niranjan Nanda
              Supratika Padhi
              Gudla Vivek 
              Durga Prasad Rath

TEAM NAME- Team(SC2)_1

