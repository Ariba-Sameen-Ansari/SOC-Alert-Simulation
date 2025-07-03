# SOC Alert Simulation Tool 🔐

This Jupyter Notebook simulates real-time security alerts from security tools like Firewalls, IDS, Antivirus, and SIEM. The project mimics how a Level 1 SOC Analyst would handle different alerts based on severity.

## 💡 Features
- Simulates alerts with timestamps, sources, and messages
- Assigns severity: Low, Medium, High
- Simulates analyst response:
  - Low → Logged
  - Medium → Investigated
  - High → Escalated to Tier 2
- Includes logic for exporting alerts to CSV

## 📁 Files Included
- `SOC_Alert_Simulation.ipynb` – Contains all code, logic, and output

## 🧠 What I Learned
- How SOC teams handle alerts
- Severity-based triaging logic
- Real-world simulation of incident handling
- Python basics: random, datetime, pandas

## 🔧 Tools Used
- Python
- Jupyter Notebook
- datetime, random, pandas
