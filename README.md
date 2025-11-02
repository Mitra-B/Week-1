# 🤖⚡ Week 1: EV Assistant Chatbot - Foundation & Dataset Setup

<div align="center">

![Week 1](https://img.shields.io/badge/Week-1/4-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-orange?style=for-the-badge&logo=streamlit)
![Generative AI](https://img.shields.io/badge/Generative-AI-green?style=for-the-badge)

**Foundation week for building a Generative AI-based Electric Vehicle Assistant Chatbot**

**Student:** Mitrasingh Bhandari  
**Duration:** Week 1 of 4  

</div>


## 🎯 Week 1 Objectives

### Primary Goals
- [x] ✅ Identify and collect relevant EV dataset  
- [x] ✅ Define chatbot use-case and core functionalities  
- [x] ✅ Learn basics of Generative AI & LLMs  
- [x] ✅ Set up project structure and Python environment  
- [x] ✅ Create initial prototype (chatbot CLI version)

### Summary  
Week 1 focused on defining the project roadmap, finalizing the dataset, and building a functional skeleton for the EV Assistant Chatbot.  
This stage lays the foundation for data-driven chatbot interactions to be developed in later weeks.

---

## ✅ Tasks Completed

| # | Task | Status | Details |
|:-:|------|:-------:|---------|
| 1 | Identify relevant dataset for EVs | ✅ Complete | Selected *Urvish Ahir – EV Specifications Dataset 2025* from Kaggle |
| 2 | Define project objective | ✅ Complete | Build a Generative AI chatbot that answers EV-related queries |
| 3 | Study Generative AI & LLM concepts | ✅ Complete | Explored OpenAI GPT and Hugging Face transformers APIs |
| 4 | Explore dataset structure & cleaning | ✅ Complete | Cleaned and saved as `cleaned_ev_data.csv` (handled missing values, renamed columns) |
| 5 | Set up Streamlit framework | ✅ Complete | Created `streamlit_app.py` as frontend base |
| 6 | Initialize repo & environment | ✅ Complete | Folder setup + `requirements.txt` ready |

---

## 📊 Dataset Information

**Dataset Name:** Electric Vehicle Specifications Dataset (2025)  
**Author:** [Urvish Ahir](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025)  
**Records:** 478 EV models  
**Attributes Include:**
- Brand, Model  
- Battery Capacity (kWh)  
- Range (km/mi)  
- Top Speed (km/h)  
- Power (kW)  
- Efficiency (Wh/km)  
- Fast Charging Support  
- Price (approx.)

🧹 **Cleaning Steps Done**
- Removed duplicates and null values  
- Standardized column names (`lowercase_with_underscores`)  
- Verified numeric data types  
- Exported to `data/cleaned_ev_data.csv`

---

## 💬 Problem Statement

> Build a Generative AI-powered chatbot that can answer queries about electric vehicles based on real specifications data.

### Example Queries
- “Which EV has the longest range?”  
- “Compare Tata Nexon EV and Hyundai Kona.”  
- “Show cars with battery capacity above 60 kWh.”  
- “Which EVs support fast charging?”

---

## 🧰 Tools & Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| Programming | Python 3.9+, Pandas, NumPy |
| AI / LLMs | OpenAI GPT, Hugging Face Transformers |
| Frontend | Streamlit |
| Data Cleaning | Pandas |
| Version Control | Git + GitHub |


