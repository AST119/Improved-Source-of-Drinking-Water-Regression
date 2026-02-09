# Improved-Source-of-Drinking-Water-Regression
This project is made over IBM Watsonx to build a model to train over drinking water source dataset .

# 💧 Improved Source of Drinking Water Prediction

[![Platform: watsonx.ai](https://img.shields.io/badge/Platform-IBM%20watsonx.ai-blue)](https://www.ibm.com/watsonx)
[![Model: SnapML](https://img.shields.io/badge/Model-Snap%20Boosting%20Machine-orange)](https://github.com/IBM/snapml)

## 📌 Project Overview
This project addresses **Problem Statement No. 5** regarding the access to safe drinking water in India. Using data from the **78th Round of the Multiple Indicator Survey (MIS)**, I developed a machine learning solution to analyze and predict the percentage of the population with access to improved drinking water sources.

The goal is to provide actionable insights for **SDG Goal 6 (Clean Water and Sanitation)** by identifying regional disparities and socio-economic correlations.

---

## ⚙️ Technical Architecture
The solution was built using the **IBM watsonx.ai** ecosystem, leveraging automated machine learning (AutoAI) to find the most efficient pipeline.

* **Data Preprocessing:** Handled missing values and encoded categorical variables from the MIS 78th Round.
* **Model Selection:** The **Snap Boosting Machine Regressor** was selected for its high performance and scalability.
* **Optimization:** Applied Hyperparameter Optimization (HPO) and automated Feature Engineering (FE).
* **Deployment:** Successfully promoted to a deployment space for real-time inference.

---

## 📊 Performance Metrics
The model achieved top-tier performance on the Watsonx AutoAI leaderboard:

| Metric | Result |
| :--- | :--- |
| **Algorithm** | Snap Boosting Machine Regressor |
| **Pipeline** | Pipeline 5 (Best Performing) |
| **RMSE** | **4.391** |
| **Enhancements** | HPO + Batched Tree Ensemble |

---

## 🚀 Deployment Status
The model is successfully promoted to the **Deployment Space** and is active.
* **Deployment Type:** Online / Real-time.
* **API Type:** REST Endpoint.
* **Environment:** watsonx.ai Runtime Environment.

---

## 🔮 Future Scope
* **🛰️ IoT Integration:** Incorporating live sensor data from rural water pumps for real-time monitoring.
* **📈 Socio-Economic Deep-Dive:** Correlating water access with migration trends and clean fuel usage.
* **🗺️ Geospatial Analysis:** Implementing GIS mapping to identify regional "dark zones" or hotspots.
* **📋 Policy Simulators:** Creating "What-If" dashboards for government resource allocation based on model predictions.
* **📱 Edge Deployment:** Optimizing models for offline mobile apps for field officers in remote areas.

---

## 📚 References
* **NSSO MIS 78th Round:** Ministry of Statistics and Programme Implementation (MoSPI), Govt. of India.
* **IBM watsonx.ai:** Documentation for AutoAI and Snap Machine Learning libraries.
* **Sustainable Development Goals:** UN SDG Goal 6 & 7 Monitoring Frameworks.

---

### 🎓 Acknowledgments
* **Institute:** Haridwar University, Roorkee
* **Training:** Special thanks to **Edunet Foundation** and **Mr. Aman** for the insightful induction session on IBM watsonx and career-ready AI skills.

---
**Author:** [Aaditya Singh Tariyal]
*B.Tech 3rd Year, CSE (AI/ML)* *MIET, Meerut*
