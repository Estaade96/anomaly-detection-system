# anomaly-detection-system
# Transaction Anomaly Detection System

##  Overview
This project implements a statistical anomaly detection system for financial transactions using Python.

It identifies unusual transaction patterns by analyzing deviations from normal behavior using mean and standard deviation.

---

##  Objective
To detect abnormal financial transactions and assign risk scores for decision-making and fraud monitoring.

---

##  Technologies Used
- Python
- Pandas
- Matplotlib

---

##  Methodology
The system applies statistical analysis:

- Calculates the **mean (average)** transaction value
- Computes the **standard deviation**
- Defines anomaly thresholds:
  
  Upper Limit = Mean + (2 × Std Dev)  
  Lower Limit = Mean - (2 × Std Dev)

- Classifies transactions into:
  - Normal
  - High Anomaly
  - Low Anomaly

- Assigns a **risk score**:
  
  Risk Score = (Transaction - Mean) / Std Dev

---

## Features
- Detects abnormal transactions
- Assigns anomaly categories
- Calculates risk scores
- Displays summary statistics
- Visualizes anomaly distribution
- Exports results to CSV

---

## Project Structure
anomaly-detection-system/

  anomaly_detection.py
  transactions.csv
  anomaly_report.csv
  README.md
  requirements.txt

---

# How to Run

1. Install dependencies:

2. Run the script:
python anomaly_detection.py


---

##  Output
The system generates:

- Anomaly classification for each transaction
- Risk score values
- Summary statistics
- Visualization chart
- Exported file: `anomaly_report.csv`

---

##  Use Cases
- Fraud detection
- Financial risk monitoring
- Transaction auditing
- Data analysis research

---

##  Author
Esther Adenike Adegbola





















