# 🚗⚡ EV Assist - Intelligent Electric Vehicle Chatbot

<div align="center">

![EV Assist Banner](https://img.shields.io/badge/EV%20Assist-AI%20Powered-00d26a?style=for-the-badge&logo=electric-vehicle)
![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge)

**An intelligent AI-powered chatbot for Electric Vehicle comparison, recommendations, and insights using Generative AI and real-world data.**

[🎬 Live Demo](https://your-app.streamlit.app) | [📊 Dataset](https://kaggle.com/dataset-link) | [📝 Documentation](#documentation) | [🐛 Report Bug](https://github.com/yourusername/ev-assist/issues)

</div>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [How It Works](#-how-it-works)
- [API Configuration](#-api-configuration)
- [Dataset](#-dataset)
- [Deployment](#-deployment)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 Overview

**EV Assist** is a cutting-edge Generative AI application that revolutionizes how users research and compare Electric Vehicles. Unlike traditional search engines or static comparison tools, EV Assist combines:

- 🤖 **GPT-4/Llama 3** for natural language understanding
- 📊 **Real-world EV data** from Kaggle (500+ vehicles)
- 🔍 **RAG (Retrieval-Augmented Generation)** for accurate, data-backed responses
- 📈 **Interactive visualizations** for market insights

### Why EV Assist?

Traditional EV research is time-consuming and scattered across multiple websites. EV Assist solves this by:

✅ Answering complex questions in natural language  
✅ Providing data-driven comparisons instantly  
✅ Offering personalized recommendations based on user needs  
✅ Visualizing market trends and insights  

**Example Query:**
> "I need an electric SUV for daily 80km city commute with fast charging support under ₹20 lakhs. What are my options?"

**EV Assist Response:**
> Based on your requirements, I recommend these 3 EVs:
> 
> 1. **Tata Nexon EV Max** (₹18.3L)
>    - Range: 437 km ✅
>    - Fast charging: Yes (0-80% in 56 min) ✅
>    - Type: Compact SUV ✅
>    - Best for: City + occasional highway trips
> 
> 2. **MG ZS EV** (₹19.5L)
>    - Range: 461 km ✅
>    - Fast charging: Yes (0-80% in 50 min) ✅
>    - Spacious cabin, premium features
> 
> [Detailed comparison table follows...]

---

## ✨ Features

### 🤖 AI-Powered Q&A
- Natural language processing for complex queries
- Context-aware responses using RAG architecture
- Factual answers grounded in real EV specifications
- Follow-up question handling with conversation memory

### ⚖️ Intelligent Comparison
- Side-by-side comparison of up to 3 EVs
- Multi-dimensional analysis (price, range, battery, features)
- Radar charts for visual comparison
- Pros/cons analysis with AI-generated insights

### 🎯 Smart Recommendations
- Personalized suggestions based on:
  - Budget constraints
  - Daily commute distance
  - Usage type (city/highway/mixed)
  - Charging infrastructure availability
  - Vehicle type preference
- AI-powered reasoning for each recommendation

### 📊 Interactive Visualizations
- Price vs Range scatter plots
- Market segmentation analysis
- Battery capacity trends
- Top 10 EVs by various metrics
- Price distribution histograms

### 🔍 Advanced Filtering
- Budget range slider
- Minimum range requirements
- Vehicle type selection (SUV, Sedan, Hatchback, 2W)
- Manufacturer filtering
- Sorting by multiple parameters

### 📥 Export & Share
- Download comparison reports (PDF/CSV)
- Share recommendations via link
- Save shortlisted vehicles
- Export filtered datasets

---

## 🎬 Demo

### Screenshots

<details>
<summary>Click to expand screenshots</summary>

#### 1. Main Chat Interface
![Chat Interface](assets/screenshots/chat-interface.png)
*Natural language Q&A with AI-powered responses*

#### 2. EV Comparison Tool
![Comparison](assets/screenshots/comparison.png)
*Side-by-side comparison with radar charts*

#### 3. Smart Recommendations
![Recommendations](assets/screenshots/recommendations.png)
*Personalized AI recommendations based on user needs*

#### 4. Market Analytics Dashboard
![Analytics](assets/screenshots/analytics.png)
*Interactive visualizations and market insights*

</details>

### 🎥 Video Demo

[![EV Assist Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

*2-minute walkthrough of key features*

---

## 🛠️ Tech Stack

### Core Technologies

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Language** | Python 3.8+ | Backend logic |
| **LLM** | OpenAI GPT-4 / Llama 3 | Natural language understanding |
| **AI Framework** | LangChain | RAG implementation |
| **Frontend** | Streamlit | Interactive web interface |
| **Data Processing** | Pandas | Dataset manipulation |
| **Visualization** | Plotly | Interactive charts |
| **Vector DB** | FAISS | Semantic search (optional) |

### Libraries

```python
langchain==0.1.0
openai==1.6.1
streamlit==1.29.0
pandas==2.1.4
plotly==5.18.0
python-dotenv==1.0.0
faiss-cpu==1.7.4  # Optional
sentence-transformers==2.2.2  # Optional
