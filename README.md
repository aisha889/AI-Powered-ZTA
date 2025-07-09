# AI-Powered-ZTA
# User Behavior Anomaly Detection Lab

This project simulates how a SOC Analyst might use **AI** to detect abnormal user activity using **User & Entity Behavior Analytics (UEBA)** — a core concept in **Zero Trust Architecture (ZTA)**.

It started as a personal experiment and became a working lab to practice the kind of thinking, tools, and decisions analysts make in real-world environments.

---

## 🎯 Project Goals

- Simulate realistic user login activity (success/fail attempts, access types, etc.)
- Use **AI (Isolation Forest)** to detect behavior that deviates from the norm
- Visualize and report suspicious user actions like:
  - Odd login times
  - Failed RDP attempts
  - Unknown devices or locations

---

## 🧪 Environment

| Tool       | Purpose                      |
|------------|------------------------------|
| Python 3   | Main language                |
| Pandas     | Data manipulation            |
| Scikit-learn | ML model (Isolation Forest) |
| Matplotlib/Seaborn | Visualization         |
| Jupyter Notebook | Interactive lab format  |

---

## 📁 Files Included

- `ueba_lab.ipynb` → interactive notebook with full code & visuals  
- `simulated_user_activity_logs.csv` → generated user login logs  
- `README.md` → this document

---

## 🧠 What It Does

1. **Simulates** 1000+ normal user login records + 50 abnormal ones
2. **Encodes** categorical features like usernames, devices, and results
3. **Trains** an Isolation Forest to identify outliers
4. **Labels** anomalies for analyst review
5. **Visualizes** results like a mini SOC dashboard

---

## 🧑‍💻 Sample Output
### 📊 Anomaly Distribution (Bar Chart)
![Screenshot 2025-07-09 084741](https://github.com/user-attachments/assets/037a89ba-9332-44c4-a7d0-de39f96d3a8b)
### 🔍 Flagged Login Activity
![Screenshot 2025-07-09 084658](https://github.com/user-attachments/assets/d7791277-828d-4892-93d2-4dec61691138)


