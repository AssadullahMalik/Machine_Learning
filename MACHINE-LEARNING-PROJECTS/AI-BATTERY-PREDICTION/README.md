# 🔋 AI Battery State of Health (SOH) Predictor

An intelligent Machine Learning-based web application that predicts the **State of Health (SOH)** of a battery using real-world parameters like voltage, current, temperature, and cycle count.

---

## 🚀 Overview

Battery health is critical for devices like electric vehicles, smartphones, and energy storage systems. This project uses **Machine Learning** to estimate battery degradation and provide actionable insights.

The system allows users to input battery parameters and get:

* 📊 SOH Prediction (percentage)
* 📉 Health status (Good / Moderate / Poor)
* 💡 Smart recommendations for battery care

---

## 🧠 Features

* ✅ Real-time SOH prediction using trained ML model
* ✅ User-friendly web interface (built with Tailwind CSS)
* ✅ FastAPI backend for high performance
* ✅ Downloadable report (PDF/JSON)
* ✅ Input validation for accurate predictions
* ✅ Clean and minimal UI for non-technical users

---

## 🏗️ Tech Stack

**Frontend:**

* HTML, Tailwind CSS
* JavaScript

**Backend:**

* FastAPI

**Machine Learning:**

* Python
* Scikit-learn
* NumPy
* Pandas

---

## 📂 Project Structure

```
battery-soh-predictor/
│
├── backend/
│   ├── main.py
│   ├── model/
│   ├── routes/
│   └── utils/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── app.js
│
├── model/
│   ├── trained_model.pkl
│   └── scaler.pkl
│
├── data/
│   └── dataset.csv
│
└── README.md
```

---

## ⚙️ How It Works

1. User enters battery parameters:

   * Voltage
   * Current
   * Temperature
   * Cycle Count

2. Data is sent to the FastAPI backend

3. ML model processes input and predicts SOH

4. Result is displayed with insights and recommendations

---

## 📊 Model Performance

* **MAE:** 0.12
* **RMSE:** 0.19
* **R² Score:** 0.40

> Model trained on structured battery dataset and optimized for regression tasks.

---

## ▶️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/battery-soh-predictor.git
cd battery-soh-predictor
```

### 2️⃣ Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3️⃣ Frontend Setup

Simply open:

```
frontend/index.html
```

---

## 📸 Screenshots

<img width="1890" height="871" alt="image" src="https://github.com/user-attachments/assets/84bc8831-152f-42ad-b7c1-3681ba870425" />
<img width="768" height="870" alt="image" src="https://github.com/user-attachments/assets/00a55d08-05b2-4788-ad9d-2e22a9c08513" />
<img width="1854" height="861" alt="image" src="https://github.com/user-attachments/assets/b34201c7-4201-4803-b74f-2b8e0fb48311" />
<img width="1867" height="876" alt="image" src="https://github.com/user-attachments/assets/04b52c23-3de3-4e31-b422-c37d55f2576b" />


## 📥 Output Example

```
SOH: 87%
Status: Good
Recommendation: Maintain optimal charging cycles to extend battery life.
```

---

## 🌍 Real-World Applications

* 🔋 Electric Vehicles (EVs)
* 📱 Smartphones & Laptops
* ⚡ Energy Storage Systems
* 🏭 Industrial Battery Monitoring

---

## 🔮 Future Improvements

* 🔹 Deep Learning model (LSTM for time-series data)
* 🔹 Live battery sensor integration
* 🔹 Mobile app version
* 🔹 Cloud deployment (AWS/GCP)

---

## 👨‍💻 Author

**Asadullah Malik**
Aspiring AI Engineer

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share with others

---

## 📜 License

This project is open-source and available under the MIT License.
