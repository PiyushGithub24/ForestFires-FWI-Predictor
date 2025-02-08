# 🌲🔥 Forest Fires FWI Predictor 🔥🌲  

A machine learning model to predict the **Fire Weather Index (FWI)** using weather and environmental factors.  

## 🚀 Project Overview  
Forest fires are a major environmental concern. This project uses **machine learning** to predict the **Fire Weather Index (FWI)**, a key indicator of fire risk.  

- 🔥 **FWI** helps forecast the likelihood and severity of wildfires.  
- 📊 **Trained on real-world weather and fire behavior data.**  
- 🤖 **Deployed as an API for real-time predictions.**  

---

## 📜 Dataset Features  
The model is trained on a dataset containing:  

| Feature  | Description |
|----------|-------------|
| 🌡 **Temperature** | Air temperature (°C) |
| 💨 **Wind Speed** | Wind speed (km/h) |
| 💧 **Humidity** | Relative humidity (%) |
| 🌧 **Rainfall** | Rainfall (mm) |
| 🔥 **FFMC (Fine Fuel Moisture Code)** | Dryness of surface fuels (0-101, higher = drier) |
| 🔥 **DMC (Duff Moisture Code)** | Moisture content in moderate fuels (0-150, higher = drier) |
| 🔥 **ISI (Initial Spread Index)** | Fire spread potential (higher = faster spread) |
| 📍 **Region** | The geographical region where the fire occurred |
| 🔥 **FWI (Fire Weather Index)** | Target variable predicting fire risk |
| 🔥 **Class** | Fire severity classification (e.g., Low, Medium, High) |

---

## ⚙️ Model & Tech Stack  
- **Machine Learning Model:** Ridge Regressor 
- **Framework:** Flask 
- **Deployment:** Render 

---

## 🔧 Installation  
Clone the repository and install dependencies:  
```sh
git clone https://github.com/your-username/Forest-Fires-FWI-Predictor.git
cd Forest-Fires-FWI-Predictor
pip install -r requirements.txt
