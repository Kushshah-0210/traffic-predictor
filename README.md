# 🚦 Traffic Congestion Prediction System

A smart web-based application that predicts traffic congestion, suggests optimal travel time, and recommends the best routes using Machine Learning, weather data, and real-time mapping.

---

## 📌 Features

### 🚗 Multi-Route Prediction

* Provides **Top 3 fastest routes** (not just shortest)
* Routes are ranked based on **predicted travel time**

### 🎨 Smart Traffic Visualization

* 🔵 Low traffic
* 🟡 Medium traffic
* 🔴 High traffic
* Routes are drawn **accurately on roads (not straight lines)**

### 🌦 Weather Integration

* Predicts:

  * Temperature 🌡
  * Rainfall 🌧
  * Weather condition ⛅
* Weather impacts congestion prediction

### 📊 Traffic Graph

* Displays **Congestion vs Time (24 hrs)**
* Fully **zoomable & interactive**
* Helps analyze daily traffic patterns

### 🟢 Best Time Recommendation

* Suggests **optimal departure time**
* Ensures **minimum travel time**
* Always suggests time **before user’s selected time**

### 🗺 Interactive Map

* Auto-focus on selected route
* Start (S) and End (E) markers
* Multiple route switching

---

## 🧠 Tech Stack

### Frontend

* HTML, CSS, JavaScript
* Google Maps API
* Chart.js

### Backend

* Python (Flask)

### Machine Learning

* Scikit-learn
* Models used:

  * Traffic Prediction Model
  * Weather Prediction Model

---

## 📂 Project Structure

```
traffic-predictor/
│
├── app/
│   ├── app.py
│   ├── model.pkl
│   ├── weather_model.pkl
│
├── data/
│   ├── traffic.csv
│   ├── weather.csv
│
├── templates/
│   ├── index.html
│
├── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/traffic-predictor.git
cd traffic-predictor
```

### 2️⃣ Install dependencies

```bash
pip install flask numpy pandas scikit-learn requests
```

### 3️⃣ Run the app

```bash
python app.py
```

### 4️⃣ Open in browser

```
http://127.0.0.1:5000
```

---

## 🔑 API Setup

Replace your Google API key in:

### `app.py` and `index.html`

```python
GOOGLE_API_KEY = "AIzaSyBWz8FvOq4Azo2QZujcxQFMzJrfoa2TmsY"
```

---

## 🎯 How It Works

1. User enters:

   * Date 📅
   * Time ⏰
   * Source & Destination 📍

2. System:

   * Fetches multiple routes
   * Predicts congestion using ML
   * Applies weather impact

3. Output:

   * Top 3 optimized routes 🚗
   * Traffic levels 🎨
   * Travel time ⏱
   * Interactive graph 📊
   * Best travel time suggestion 🟢

---

## 🏆 Key Highlights

* Combines **ML + Maps + Weather**
* Real-world problem solving
* Interactive and modern UI
* Multi-route optimization
* Decision-making system (not just prediction)

---

## 🚀 Future Improvements

* Live traffic API integration
* User location auto-detection
* Travel time savings comparison
* Route recommendation with AI scoring
* Mobile app version

---

## 👨‍💻 Authors

* Kush Shah
* Vidhi Rana

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

---
