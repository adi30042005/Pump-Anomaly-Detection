# Pump Anomaly Detection with Isolation Forest

A simple prototype for detecting anomalies in pump-set sensor data using an Isolation Forest.

---

## 📋 Project Overview

This notebook applies an unsupervised Isolation Forest model to identify unusual patterns in pump-set measurements (e.g., vibration, temperature, pressure). It includes:
- Data loading & preprocessing  
- Model training & evaluation  
- Visualizations of normal vs. anomalous points  

---

## 🗂️ Repository Structure

/ ├── isolation_forest_pumpset.ipynb # Jupyter notebook with code and analysis ├── Pump_data.xlsx # Raw dataset exported from sensors └── README.md # This file

yaml
Copy
Edit

---

## ⚙️ Requirements

- Python 3.8+  
- pandas  
- scikit-learn  
- matplotlib  
- jupyterlab or notebook

---

## 💾 Installation

```bash
pip install pandas scikit-learn matplotlib jupyterlab
🚀 Usage
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/pump-anomaly-detection.git
cd pump-anomaly-detection
Launch Jupyter

bash
Copy
Edit
jupyter lab
Run isolation_forest_pumpset.ipynb and follow the analysis.

📊 Data
Pump_data.xlsx: time-series sensor readings (timestamp, vibration, temperature, etc.).

You may convert to CSV or filter columns before modeling.

📝 Results
Includes ROC curves, anomaly score distributions, and flagged sample readings.

Tweak the contamination parameter in the Isolation Forest to adjust sensitivity.

🤝 Contributing
Fork the repository

Create a feature branch (git checkout -b feature-name)

Commit your changes (git commit -m "Add feature")

Push to your branch (git push origin feature-name)

Open a Pull Request

📄 License
This project is licensed under the MIT License. See LICENSE for details.

