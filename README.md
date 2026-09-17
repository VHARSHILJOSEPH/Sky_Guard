# 🌦️ SkyGuard AI

### Explainable Real-Time Weather Station Anomaly Detection

SkyGuard AI is an intelligent weather station monitoring platform designed to detect, classify, and explain anomalies in Automatic Weather Station (AWS) observations.

The system combines Machine Learning, statistical analysis, and rule-based quality control to identify sensor faults, data inconsistencies, and unusual weather observations in real time.

Instead of treating every sudden weather change as a sensor failure, SkyGuard AI analyzes temporal patterns, multivariate relationships, and available spatial evidence to provide explainable anomaly assessments.

---

## 🚀 Key Features

- 🔍 **Real-Time Anomaly Detection**
  Monitor incoming weather observations and identify abnormal readings.

- 🤖 **Hybrid AI Detection**
  Combines rule-based validation, statistical detection, and machine learning.

- 📊 **Multivariate Analysis**
  Analyzes temperature, pressure, and humidity relationships.

- 🧠 **Explainable AI**
  Provides anomaly types, severity, confidence, and human-readable explanations.

- 🛰️ **Sensor Health Monitoring**
  Tracks sensor behaviour, missing data, communication gaps, and persistent anomalies.

- 🌍 **Weather Event Differentiation**
  Uses available neighbouring-station evidence to help distinguish genuine weather events from isolated sensor anomalies.

- 🧪 **Demo Simulation**
  Injects synthetic sensor faults through the detection pipeline for reliable demonstrations.

- 📈 **Interactive Dashboard**
  Visualizes live readings, anomaly history, and station health.

---

## 🧩 Anomaly Types

SkyGuard AI is designed to detect:

- Temperature Spikes
- Frozen Sensors
- Sensor Drift
- Missing Data
- Invalid Values
- Duplicate Readings
- Communication Gaps
- Multivariate Inconsistency
- Unusual Temporal Patterns

---

## 🏗️ System Architecture

Observation Sources
↓
Data Ingestion
↓
Validation & Cleaning
↓
Feature Engineering
↓
Rule-Based Detection
↓
Statistical Analysis
↓
Machine Learning Detection
↓
Evidence Fusion
↓
Anomaly Classification
↓
Explanation Generation
↓
FastAPI Backend
↓
React Dashboard

---

## 🛠️ Technology Stack

### Backend
- Python
- FastAPI
- Pandas
- NumPy
- SciPy
- Scikit-learn
- SQLAlchemy
- SQLite

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Recharts
- Axios

### Machine Learning
- Isolation Forest
- Statistical Anomaly Detection
- Temporal Feature Engineering
- Rule-Based Quality Control

### Data Sources
- IMD AWS Data (subject to approved access)
- Historical Meteorological Observations
- Synthetic Fault Injection

---

## ⚙️ Core Workflow

1. Collect weather observations.
2. Validate and clean incoming data.
3. Generate temporal and multivariate features.
4. Apply rule-based quality checks.
5. Run statistical and ML anomaly detectors.
6. Combine detector evidence.
7. Classify anomaly type and severity.
8. Generate an explainable assessment.
9. Display results on the monitoring dashboard.

---

## 📊 Example Detection Output

{
  "status": "ANOMALY",
  "anomaly_type": "TEMPERATURE_SPIKE",
  "severity": "HIGH",
  "affected_parameter": "temperature",
  "anomaly_score": 0.87,
  "reason": "Temperature changed sharply compared with the recent station baseline."
}

*Example output for demonstration purposes.*

---

## 🧪 Demonstration Mode

SkyGuard AI includes a controlled simulation mode for testing and evaluation.

### Supported Scenarios

- Temperature Spike
- Frozen Sensor
- Missing Data
- Sensor Drift
- Communication Failure
- Coordinated Weather Event

Synthetic faults are processed through the detection pipeline to demonstrate the system's anomaly identification and explanation capabilities.

---

## 🎯 Project Objective

To develop a reliable and explainable AI-powered platform that improves the monitoring and quality assessment of Automatic Weather Station observations.

SkyGuard AI aims to support early identification of suspicious sensor behaviour while reducing unnecessary false alarms through temporal, multivariate, and spatial evidence.

---

## 🔮 Future Enhancements

- Advanced spatial anomaly detection
- Improved model calibration
- Additional meteorological parameters
- Historical performance analytics
- Multi-station monitoring
- Cloud-based deployment
- Automated sensor maintenance alerts

---

## 👥 Team

**Project:** SkyGuard AI  
**Hackathon:** Smart India Hackathon 2026 (SIH 2026)

---

## 📄 Disclaimer

SkyGuard AI is a prototype developed for research, experimentation, and hackathon demonstration.

Anomaly classifications and confidence values require empirical validation before operational deployment.
