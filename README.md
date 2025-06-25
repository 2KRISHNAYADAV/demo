
![main_title](https://github.com/user-attachments/assets/53952526-cbb8-44a7-9c4a-03cc2eec35ec)

# 🚀 Bharatiya Antariksh Hackathon 2025

## 👨‍🚀 Team: Zero Gravity Gurus  
**Team Leader:** Krishna  
**Problem Statement 10:** Identifying Halo CME Events Based on Particle Data from SWIS-ASPEX Payload onboard Aditya-L1

---

## 🧑‍🤝‍🧑 Team Members

- **Krishna** – Team Leader, Systems Integration, Visual Design, Documentation, Frontend Developer (Dashboard/UI)  
- **Sofia** – Transformer model, CME classification, signal processing (STFT), validation (CACTUS alignment), explainability (XAI)  
- **Yuvaraj** – Data Engineer, Preprocessing Expert, API Integration  

> A diverse team blending AI expertise with space science, data pipelines, and impactful design.

---

## 💡 Project Overview

We propose an **AI-powered early-warning system** that identifies **Halo Coronal Mass Ejections (CMEs)** in real-time using **SWIS-ASPEX** data from **Aditya-L1**.

By analyzing:
- **Proton flux**
- **Ion density**
- **Solar wind temperature**
- **Velocity**

We perform **multi-class classification** of CME types:
- Flare-type
- Shock-driven
- Streamer-blowout

Additionally, we incorporate **time-frequency signal analysis using STFT** to extract meaningful patterns.

🎯 **End Goal**:  
Live alerts and interactive dashboards to empower ISRO with actionable space weather intelligence.

---

## 🔍 Opportunity & Uniqueness

### ✅ What Makes It Different:
- Real-time CME detection from SWIS particle data
- Doesn’t depend on coronagraph images
- First to apply **multi-class transformer classification** on this data
- Enhanced signal analysis via **Short-Time Fourier Transform (STFT)**

### 🧠 Explainability:
- SHAP + Attention Maps for transparency
- Replay mode for **historical CME verification**

---

## ✨ Unique Selling Points (USP)

- First implementation of **multi-class Transformer classification** on SWIS data
- **STFT-enhanced** time-frequency signal analysis
- **Scientific explainability** using SHAP & attention visualization
- Replay mode for **CME verification**
- Live alert integration (Telegram, Email, etc.)
- Expandable for CME impact forecasting

---

## 🧰 Features of Our Solution

- Real-time CME detection
- Multi-class Transformer classifier
- Attention + SHAP visualizations
- STFT-based time-series analysis
- Onset prediction (optional module)
- Dashboard (Streamlit / Flask)
- Alert System Integration
- Modular design

---

## 🔁 Process Flow Diagram

```
   SWIS Level-2 Particle Data
             ↓
     Preprocessing Module
 (Alignment, Normalization, STFT Features)
             ↓
     Feature Extraction Engine
             ↓
     Transformer Model
(Positional Encoding + Multi-Head Attention)
             ↓
  CME Classification Output (Binary + Type)
             ↓
  XAI Module (SHAP + Attention Maps)
             ↓
   Dashboard & Alert Engine
             ↓
  Validation (CACTUS / NASA)
```

📷  
![Jun 24, 2025, 11_25_26 PM](https://github.com/user-attachments/assets/4c55e6ab-8cdf-46ed-8fc1-205af9aa026c)

---

## 🖼️ Wireframes & Mockups

- 📊 Real-time dashboard
- 📈 Signal graphs
- ⚠️ CME status panel
- 🔥 SHAP & attention visualizer
- 🔔 Alert settings (Telegram, Email)

![ChatGPT Image Jun 24, 2025, 11_30_44 PM](https://github.com/user-attachments/assets/97a0e001-32c4-4e8f-bbdc-b3ab240e391c)

---

## 🛠️ Technologies Used

| Component             | Technology                         |
|----------------------|------------------------------------|
| Programming          | Python                             |
| Data Handling        | Pandas, NumPy                      |
| ML Framework         | PyTorch or TensorFlow              |
| File Format Parsing  | NASA CDF Library                   |
| Signal Processing    | SciPy, STFT                        |
| Visualization        | Matplotlib, Plotly                 |
| Model                | Transformer                        |
| Deployment           | Streamlit or Flask                 |
| Alert System         | Telegram Bot API, SMTP, Twilio     |
| Explainability       | SHAP, Attention Mechanisms         |

---

## 📂 Data & Documentation Drive

All source code, models, diagrams, and research are available at:  
**[Google Drive](https://drive.google.com/drive/folders/1fy_ogaIfN6eL3vpw98z5CkRewGwquCxY?usp=drive_link)**

---

## 💸 Estimated Implementation Cost (Optional)

![astronote](https://github.com/user-attachments/assets/cbd57960-f1ea-4a7c-ae77-92c3d75acb02)
