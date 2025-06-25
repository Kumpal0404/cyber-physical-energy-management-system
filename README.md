## 📌 Project Title

**H1Cyber-Physical Energy Management System (CPEMS) – Load Simulation and Forecasting Platform**

📖 Description
This project implements a cyber-physical energy management system focused on industrial load simulation and energy forecasting. It integrates MATLAB/Simulink, Python, and InfluxDB with a Streamlit interface to simulate realistic industrial load profiles, generate synthetic measurement data, and forecast future energy consumption using a GRU-based neural network model.

⚙️ Technologies Used
Python (Streamlit, PyTorch, Pandas, NumPy, InfluxDB Client)

MATLAB/Simulink (for load simulation with harmonics)

InfluxDB (time-series database for storing measurement data)

GRU Neural Network (for load forecasting)

🧩 Features
Realistic 3-phase power system simulation with harmonics (3rd, 5th, 7th)

Load types: induction motors, furnaces, resistive loads

HMI dashboard (Streamlit) for simulation control and forecast visualization

Hybrid Python-MATLAB architecture using MATLAB Engine API

CSV upload and data preprocessing

Daily and weekly multi-horizon load forecasting
