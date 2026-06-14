# 🩸 Blood Supply Forecasting Dashboard — Malaysia National Blood Centre

A time-series forecasting project predicting daily blood supply levels across Malaysia 
using Facebook Prophet, built as part of the Master of Data Science programme at 
Universiti Malaya (WQD7001).

---

## 📌 Problem Statement

Malaysia's National Blood Centre (Pusat Darah Negara) faces recurring challenges in 
anticipating blood supply shortages. This project builds a forecasting model on 7,000+ 
daily donation records (2006–2026) to predict future supply trends and support 
proactive inventory management decisions.

---

## 🎯 Objectives

- Forecast daily blood donation volumes for the next 30–90 days
- Identify seasonal patterns and long-term trends in blood supply
- Provide an interactive dashboard for real-time monitoring

---

## 🛠 Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python 3.10 |
| Forecasting | Facebook Prophet |
| Data Wrangling | pandas, NumPy |
| Visualisation | Matplotlib, Seaborn, Plotly |
| Dashboard | Streamlit |
| Environment | Google Colab, Jupyter Notebook |

---

## 📊 Dataset

- **Source:** [Malaysia Open Data — data.gov.my](https://data.gov.my)
- **Records:** 7,000+ daily entries (2006–2026)
- **Features:** Date, donation count, blood type breakdown, state

---

## 🔍 Key Findings

- Blood donations show a consistent **seasonal dip in Q1** (January–February), likely due to Chinese New Year and school holidays
- Long-term trend shows a **gradual upward trajectory** in donation volumes from 2015 onwards
- Prophet model achieved a **MAPE of ~8.3%** on the test set — suitable for operational planning purposes

---

## 📁 Repository Structure

```
bloodflow-malaysia-forecasting/
│
├── data/
│   └── blood_donation_malaysia.csv
│
├── notebooks/
│   └── bloodflow_forecasting.ipynb
│
├── app/
│   └── streamlit_app.py
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 🚀 How to Run

### Run the notebook
```bash
git clone https://github.com/[your-username]/bloodflow-malaysia-forecasting.git
cd bloodflow-malaysia-forecasting
pip install -r requirements.txt
jupyter notebook notebooks/bloodflow_forecasting.ipynb
```

### Run the Streamlit dashboard
```bash
streamlit run app/streamlit_app.py
```

---

## 📸 Dashboard Preview

> *(Add a screenshot of your Streamlit dashboard here)*

---

## 👥 Team

| Name | Role |
|---|---|
| Farah Annisa Binti Norhisham | Group Leader, Forecasting Model, Dashboard |
| [Teammate 2] | [Role] |
| [Teammate 3] | [Role] |
| [Teammate 4] | [Role] |

---

## 📚 References

- Taylor, S.J. & Letham, B. (2018). Forecasting at scale. *The American Statistician.*
- Pusat Darah Negara Malaysia — [pdn.gov.my](https://www.pdn.gov.my)
- Malaysia Open Data Portal — [data.gov.my](https://data.gov.my)

---

## 🎓 Academic Context

**Course:** WQD7001 — Data Science Project  
**Institution:** Universiti Malaya (UM)  
**Programme:** Master of Data Science  
**Year:** 2025
