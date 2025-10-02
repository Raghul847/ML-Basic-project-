# 🎥 Cinema Audience Forecasting — Kaggle Competition

> **Predict how many people will attend each cinema show** using real-world booking, theater, and calendar data.

[![Kaggle Competition](https://img.shields.io/badge/Kaggle-Competition-blue?logo=kaggle)](https://www.kaggle.com/competitions/cinema-audience-forecasting)

## 📌 Overview

This repository contains a reproducible end-to-end pipeline for the [**Cinema Audience Forecasting**](https://www.kaggle.com/competitions/cinema-audience-forecasting) Kaggle competition.

The goal is to predict the `audience_count` for each unique show (identified by `ID`) using:
- Booking records (`booknow_booking.csv`)
- Theater metadata (`booknow_theaters.csv`, `cinePOS_theaters.csv`)
- Daily visits (`booknow_visits.csv`)
- Calendar features (`date_info.csv`)
- Theater ID mappings (`movie_theater_id_relation.csv`)

- **Evaluation Metric**: Root Mean Squared Error (RMSE)  
- **Baseline Model**: Feature-engineered Linear Regression / Random Forest  
- **Best Public Score**: _[Insert your score here]_

> ⚠️ **Important**: You must **accept the competition rules on the Kaggle website** before downloading data or submitting predictions. This cannot be done via the API.

---

## 🗂️ Repository Structure

---

## ⚙️ Setup

### Prerequisites
- Python ≥ 3.9
- Git
- Kaggle account with API access

### 1. Clone & Install
```bash
git clone https://github.com/yourusername/cinema-audience-forecasting.git
cd cinema-audience-forecasting

# Create virtual environment
python -m venv env
source env/bin/activate  # Linux/macOS
# env\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt
