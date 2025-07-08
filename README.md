# IoT Based Health Monitoring System

An IoT-driven project aimed at developing a cost-effective, portable, and smart health monitoring system integrated with machine learning and cloud-based dashboards for real-time health tracking and early disease detection.

---

## 📘 Introduction

In an era where preventive healthcare is becoming vital, this project combines biotechnology, mechanical engineering, and IoT technologies to develop a holistic health monitoring solution. It integrates wearable biometric sensors, real-time data processing, cloud storage, and web-based dashboards, offering both users and healthcare providers the ability to access and respond to vital health data remotely.

The project’s core motivation lies in making healthcare more accessible to individuals who are immobile, elderly, or in remote areas, using smart technology to detect and respond to health anomalies in real-time.

---

## 🛠️ System Design

### 1. Architecture Overview
- **Sensor Layer**: Collects vital data like body temperature, heart rate, SpO2, and blood pressure using sensors like LM35, heartbeat sensor, PIR, and ultrasonic sensor.
- **Data Layer**: Arduino Uno and NodeMCU (ESP8266) are used to collect and transmit data.
- **Cloud Layer**: ThingSpeak and MongoDB are used for storage; APIs and ExpressJS are used for data routing.
- **Frontend**: Developed in React for dashboard visualization.
- **ML Integration**: Logistic Regression and SVM models are used for disease prediction.

### 2. Data Flow
1. Sensors collect health parameters.
2. Arduino Uno processes and forwards data to NodeMCU.
3. NodeMCU sends data to ThingSpeak or MongoDB via WiFi.
4. APIs fetch data to the React web interface.
5. Users view data in real-time with alert systems for abnormal values.

### 3. Wireframes and UI
- **Home Page**: Service overview and quick access links.
- **Dashboard**: Real-time charts for vitals.
- **Blog Page**: Educational content.
- **User Profile**: Device integration and customization.
- **Login/Signup**: Secure access with OAuth options.

---

## ⚙️ Implementations

### Hardware Components
- **LM35**: Measures body temperature.
- **Heartbeat Sensor**: Uses photoplethysmography to detect pulse rate.
- **Ultrasonic Sensor**: Measures proximity for social distancing.
- **PIR Sensor**: Detects motion.
- **NodeMCU (ESP8266)**: WiFi module for internet connectivity.
- **ThingSpeak**: IoT analytics platform for real-time monitoring.
- **GSM + GPS Module**: Sends alerts with real-time location in emergencies.

### Software Stack
- **ReactJS**: Frontend dashboard.
- **ExpressJS**: Backend server.
- **MongoDB**: Data storage.
- **MATLAB**: Simulation and modeling.
- **Machine Learning**: Logistic Regression and SVM for disease classification (Heart, Diabetes).

---

## 📊 Results and Discussions

### 1. Real-Time Simulations (MATLAB)
- **Simulation 1**: Time-series data of vitals over 24 hours showed dynamic physiological changes influenced by circadian rhythms and activity.
- **Simulation 2**: Abnormal events highlighted through area plots, allowing healthcare providers to intervene promptly.

### 2. Alert System
- Threshold-based alert mechanism for heart rate, body temperature, and SpO2 ensures early warning and preventive action.

### 3. Portable Health Guardian Kit
- Aerospace-grade casing with integrated sensors, NFC display, rechargeable battery, and emergency alert button.
- Enables remote diagnostics and emergency assistance, especially for rural and elderly users.

### 4. Machine Learning Models
- **Accuracy**: High performance in predicting diabetic and cardiac conditions.
- **Dataset**: Included features like glucose, insulin, BMI, blood pressure, and age.

---

## ✅ Conclusion

The system effectively combines real-time health tracking, predictive analytics, and emergency response into a compact, accessible format. It facilitates a proactive approach to healthcare, especially in under-resourced or remote communities.

Key highlights:
- **Affordable** and **portable**
- **Accurate** disease prediction using ML
- **User-friendly** interface
- **Secure** and **scalable** architecture

---

## 🔮 Future Scope

- Integration with additional biometric sensors (e.g., ECG, glucose monitoring).
- Mobile app for remote monitoring and doctor-patient chat.
- AI-based anomaly detection using larger datasets.
- Blockchain for secure and decentralized health record sharing.
- Enhanced signal filtering to reduce interference in wearable systems.

---

> 🧑‍💻 Developed by: Soham Karmakar, Mritunjay Kumar Singh, Riya Mishra
