# 🫀 Heart Disease Power BI Dashboard  

## 📌 Table of Contents  
1. 📖 [Overview](#1-overview)  
2. 💼 [Business Problem](#2-business-problem)  
3. 📂 [Dataset](#3-dataset)  
4. 🛠 [Tools & Technologies](#4-tools--technologies)  
5. 🔍 [Research Questions & Key Findings](#5-research-questions--key-findings)  
6. 📊 [Dashboards](#6-dashboards)  
   - 🌍 Overall Insights  
   - 👨 Male Dashboard (Detailed)  
   - 👩 Female Dashboard (Detailed)  
7. 🎯 [Final Recommendations](#7-final-recommendations)  
8. 👤 [Author & Contact](#8-author--contact)  

---

## 1. 📖 Overview  
This project focuses on analyzing **clinical heart disease records** to identify patterns, risks, and critical factors influencing survival and mortality.  
The dashboard provides an **interactive view by Age Group, Gender, and Medical Conditions**, helping healthcare professionals better understand patient health outcomes and take **data-driven decisions**.  

---

## 2. 💼 Business Problem  
Heart disease is one of the leading causes of death worldwide. Hospitals and healthcare providers face challenges like:  
- 🔎 Identifying **high-risk groups** early  
- 👥 Understanding **gender & age impact** on mortality  
- 🧪 Tracking critical biomarkers like **serum sodium, ejection fraction, platelets**  

This project answers these questions by providing **actionable insights** through a Power BI dashboard that supports **early intervention and better planning**.  

---

## 3. 📂 Dataset  
📄 **Source:** Heart Disease Clinical Records (299 patients)  

**Key Columns:**  
- 👵 **Age**, 👤 **Gender**, ⚰ **Death Event**  
- 🩸 **Diabetes**, 🫀 **High Blood Pressure**, 🎗 **Cancer**  
- ❤️ **Ejection Fraction**, 🧬 **Platelets**, 🧪 **Serum Sodium**  
- 🧾 **Kidney Marker**, 💪 **Muscle Damage Scale**  

---

## 4. 🛠 Tools & Technologies  
- 📊 **Power BI** → Data Cleaning, DAX Calculations, Dashboard Design  
- 📑 **Excel** → Initial Dataset Preparation  
- 🧮 **DAX Functions Used:**  
  - `SWITCH()` for **Age Group Classification**  
  - `IF()` for **Gender Classification**  
  - Measures for **Total Patients, Death Rate, Survival %**  

---

## 5. 🔍 Research Questions & Key Findings  

### ❓ Research Questions  
✔ Which **age groups** have the highest mortality?  
✔ How does **gender** affect survival and death rates?  
✔ What is the impact of **ejection fraction, serum sodium, and platelets** on patient survival?  
✔ Which medical conditions (**diabetes, hypertension, cancer**) increase the risk?  

### ✅ Key Findings  
- 👨 **Males** show higher mortality in age groups **61-70** and **71+**  
- 👩 **Females** have lower death percentages overall but show vulnerability in **51-60** age group  
- ❤️ **Low ejection fraction (<40%)** & 🧪 **Low serum sodium (<135)** strongly correlate with higher mortality  
- 🧠 Medical conditions like **hypertension** and **diabetes** amplify risk significantly  

---

## 6. 📊 Dashboards  

### 🌍 Overall Insights Dashboard  
Provides a **bird’s-eye view** of all heart disease patients.  
- 📊 Age Group & Gender distribution  
- ⚰ Survival vs Death percentages  
- 🧪 Clinical markers (Platelets, Sodium, Kidney markers)  
- 🎛 Interactive filters for Age Group, Gender, and Conditions  

📸 **Overall Dashboard:**  
![Overall Insights](Heart%20Disease%20Insights.png)  

---

### 👨 Male Dashboard (Detailed)  
**Focus:** High-risk male patients  

- 📈 Mortality is **highest** in age groups **61-70** and **71+**  
- 👦 Younger males (<40) show **higher survival**, risk rises after 50  
- 🩸 Males with **diabetes & hypertension** show elevated death rates  
- ❤️ **Ejection Fraction < 35%** = highest death risk  

📸 **Male Dashboard:**  
![Male Dashboard](Heart%20Disease%20Dashboard%20(Male).png)  

---

### 👩 Female Dashboard (Detailed)  
**Focus:** Female-specific health patterns  

- 👩 Females have **better survival rates** than males in most groups  
- 📊 Slight mortality spike in **51-60 age group** (likely comorbidities)  
- 🎗 **Cancer presence** increases female mortality more than in males  
- 🧬 **High platelet count** correlated with longer survival  

📸 **Female Dashboard:**  
![Female Dashboard](Heart%20Disease%20Dashboard%20(Female).png)  

---

## 7. 🎯 Final Recommendations  
✅ **Early Screening:** Patients above 50 should undergo routine heart check-ups  
✅ **Male Patients (61+):** Immediate intervention for low ejection fraction & sodium  
✅ **Female Patients (50-60):** Extra care for cancer-affected patients  
✅ **Preventive Healthcare:** Lifestyle modification campaigns for younger patients  

---

## 8. 👤 Author & Contact  
👨‍💻 **Author:** Omkar Gaurav  
🎓 **Education:** B.Tech in Electronics & Communication (2022–2026)  
📊 **Skills:** Excel | SQL | Python | Power BI | Statistics  

📧 **Email:** [omkargaurav121@gmail.com](mailto:omkargaurav121@gmail.com)  
🔗 **GitHub:** [OmkarGaurav121](https://github.com/OmkarGaurav121)  
🔗 **LinkedIn:** [Omkar Gaurav](https://www.linkedin.com/in/omkar-gaurav-1508b6303)  

---
⭐ **If you found this project helpful, don’t forget to star ⭐ the repo!**
