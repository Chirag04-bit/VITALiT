# 🩺VITALiT
🩺 A Digital Twin framework using Raspberry Pi &amp; biomedical sensors for real-time health monitoring. Features cloud sync, AI-based anomaly detection, dashboards, and caregiver alerts. Scalable for home care, ICUs, and rural healthcare.


📂 The repository contains a Digital Twin framework for real-time physiological monitoring using Raspberry Pi and biomedical sensors. Includes sensor integration, cloud sync (MQTT/REST), AI models (LSTM), dashboards, and alert mechanisms for healthcare applications.

---
## 🏗️ Architecture

The repository contains the following core components of the Digital Twin framework for healthcare monitoring:

Sensors – Collect physiological signals such as heart rate, SpO₂, ECG, respiration, and temperature.

Raspberry Pi – Interfaces with sensors, preprocesses data, and ensures secure transfer using MQTT/REST.

Cloud Digital Twin Model – A virtual patient model hosted on AWS, Azure, or Eclipse Ditto that mirrors real-time health data.

AI Engine – LSTM-based predictive analytics to detect anomalies like arrhythmia, hypoxia, or abnormal breathing.

Dashboard – Real-time visualization of patient vitals using Node-RED or Grafana.

Feedback & Alerts – Sends notifications to caregivers and optionally connects to actuators such as oxygen concentrators or medicine dispensers.

---
## 📂 Repository Structure
```bash
📦 digital-twin-healthcare
│
├── 📁 hardware
│   ├── sensor_specs/          # Datasheets & wiring diagrams
│   ├── raspberry_pi_setup.md  # Pi configuration & OS setup
│   └── circuits/              # Circuit diagrams
│
├── 📁 software
│   ├── data_collection/       # Sensor reading scripts (Python)
│   ├── preprocessing/         # Signal filtering, feature extraction
│   ├── cloud_integration/     # MQTT/REST scripts
│   └── ai_models/             # ML models (LSTM, anomaly detection)
│
├── 📁 dashboard
│   ├── grafana_dashboards/    # JSON configs for Grafana
│   ├── node_red_flows/        # Node-RED flow files
│   └── screenshots/           # Dashboard images
│
├── 📁 docs
│   ├── architecture.png       # Block diagram / flowcharts
│   ├── methodology.pdf        # Project methodology
│   └── references.md          # Literature survey & citations
│
├── 📁 datasets
│   └── physionet/             # Links/scripts to fetch training data
│
├── 📁 tests
│   ├── unit_tests/            # Scripts for module-wise testing
│   └── validation_reports/    # Accuracy, metrics, calibration logs
│
├── LICENSE
├── README.md                  # Project intro & usage
└── requirements.txt           # Python dependencies
```
---
### 👥 Members

👤 Member 1 – CHIRAG SHARMA

👤 Member 2 – DEBAPRIYA KARMAKAR

---

