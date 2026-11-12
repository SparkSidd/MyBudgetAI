# ⚡ MyBudgetAI — Intelligent Financial Analytics & Expense Optimization Engine

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?style=for-the-badge&logo=python)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.35-FF4B4B.svg?style=for-the-badge&logo=streamlit)](https://streamlit.io)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E.svg?style=for-the-badge&logo=scikit-learn)](https://scikit-learn.org)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75.svg?style=for-the-badge&logo=plotly)](https://plotly.com)
[![License](https://img.shields.io/badge/License-MIT-purple.svg?style=for-the-badge)](LICENSE)
[![Author](https://img.shields.io/badge/Author-SparkSidd-orange.svg?style=for-the-badge&logo=github)](https://github.com/SparkSidd)

**AI-Driven Personal Financial Intelligence, Recurring Outflow Detection & Cash Flow Forecasting.**

[Overview](#-overview) • [System Features](#-features--capabilities) • [Technical Architecture](#-technical-architecture) • [Quick Start](#-quick-start)

</div>

---

## 📌 Overview

MyBudgetAI is an interactive personal wealth intelligence platform combining statistical cash flow modeling, machine learning clustering for automated merchant categorization, and AI-assisted financial advisory. It replaces cumbersome spreadsheets with predictive expense projection and interactive anomaly detection.

---

## 🚀 Features & Capabilities

- **📊 Dynamic Visual Analytics**: Real-time breakdown of cash flow velocity, burn rate, and category distributions using interactive Plotly charts.
- **🔄 Automated Recurring Charge Detection**: Fourier analysis and temporal recurrence algorithms to detect hidden subscriptions, SaaS fees, and recurring utility bills.
- **🎯 Dynamic Savings Goal Allocation**: Monte Carlo simulation evaluating portfolio achievement probabilities given historical income variance.
- **📈 Cash Flow Forecasting**: Time-series predictive modeling forecasting end-of-month liquidity balances.
- **🤖 AI Financial Strategist**: Context-grounded recommendations tailored to savings goals, discretionary spending limits, and emergency fund buffer targets.

---

## 🏗️ Technical Architecture

```mermaid
graph TD
    User([Financial User / Analyst]) <--> UI[Streamlit Interactive Dashboard]
    UI --> Engine[Analytics & Modeling Engine]
    
    subgraph Data & Processing Pipeline
        Engine --> Ingestion[CSV / Banking Telemetry Ingestion]
        Ingestion --> Cleaning[Sanitizer & Normalization Layer]
        Cleaning --> Recurrence[Recurrence Pattern Detector]
        Cleaning --> MLClustering[Expense Category Classifier]
    end
    
    subgraph Forecasting & Insights
        MLClustering --> Forecast[Time-Series Balance Predictor]
        Recurrence --> Advisor[AI Financial Advisory Engine]
        Forecast & Advisor --> UI
    end
```

---

## ⚡ Quick Start

```bash
# 1. Create and activate virtual environment
python -m venv mybudget-env
source mybudget-env/bin/activate  # Windows: mybudget-env\Scripts\activate

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch application
streamlit run app.py
```

---

## 📄 License
This project is open-source under the MIT License.
