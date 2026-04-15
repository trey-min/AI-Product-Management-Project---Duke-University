# AI-Product-Management-Project---Duke-University

This repository documents my journey and technical projects completed during the Duke University AI Product Management Specialization. It showcases my ability to manage the ML lifecycle, from problem definition and data analysis to model evaluation and stakeholder communication.

🏗️ Project 1: Predictive Modeling for CCPP Energy Output

📌 Project Overview

The goal of this project is to build a high-precision model to forecast the Net Hourly Electrical Energy Output (PE) of a Combined Cycle Power Plant (CCPP) using ambient environmental sensor data.

🛠️ Technical Implementation

Modeling Approach: Identified as a Supervised Regression task to minimize forecasting error for economic dispatch.

Data Features: Utilized 9,568 readings of Temperature (T), Ambient Pressure (AP), Relative Humidity (RH), and Exhaust Vacuum (V).

Model Building: Evaluated Multiple Linear Regression and Ensemble Random Forest models using a fixed validation split.

Results: Achieved an $R^2$ of 0.929 and a MAPE of 0.008 (less than 1% error).

💡 Business Value

The model identifies Ambient Temperature as the critical driver of output loss, enabling "Temperature-Aware" scheduling and more accurate market bidding strategies.

👉 View Interactive Presentation

🚀 Project 2: DVVI Predictive Inventory & Demand Forecaster
📌 Project Overview
The objective of this project is to extend the DVVI pricing engine by developing a predictive model for Inventory Velocity. By analyzing regional micro-market shifts and macroeconomic triggers, the platform forecasts vehicle demand to optimize dealership stock acquisition and turnover rates.

🛠️ Technical Implementation

Modeling Approach: Identified as a Time-Series Forecasting and Classification task to categorize inventory based on "Liquidity Risk" and seasonal demand.

Feature Engineering: Integrates historical sales velocity with external datasets, including fuel price volatility, interest rate fluctuations, and localized supply-to-demand ratios.

System Design: Developed using Python (Prophet) and BigQuery ML to process large-scale transactional data, providing a scalable infrastructure for multi-region demand heatmapping.

Performance Targets: Aiming for a 15% reduction in MAPE for inventory turnover predictions compared to traditional 30-day moving average methods.

💡 Business Value
The model enables "Demand-First" Acquisition, directly increasing dealership ROI by reducing the Days-to-Turn metric. By identifying high-liquidity vehicle segments before market shifts, the platform minimizes "lot aging" costs and maximizes cash flow efficiency.

👉 View Interactive Presentation

📈 Project 3: [Upcoming Project Title]

Status: Planned

Objective: Describe the final capstone or ethical AI project here.

Key Skills: e.g., AI Ethics, Human-in-the-loop systems.

📂 Repository Structure

├── index.html              # Presentation for Project 1
├── README.md               # Main Portfolio Index
├── Project_1_CCPP/         # Data and Notebooks for CCPP
│   ├── data/
│   └── notebooks/
├── Project_2_Name/         # Future Project Assets
└── Project_3_Name/         # Future Project Assets


📜 Credits

Institution: Duke University via Coursera
Specialization: AI Product Management
