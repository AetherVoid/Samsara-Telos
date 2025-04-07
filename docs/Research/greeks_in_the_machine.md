touch README.md
# 🧠 Greeks in the Machine (GIM)

### A Research Project on TQQQ Options Dynamics

---

## 📌 Overview

*Greeks in the Machine* (GIM) is a research project focused on analyzing **TQQQ options data** using intraday time-and-sales captures to explore:

- **Pricing dynamics**
- **Strike-level open interest aggregation**
- **Potential arbitrage opportunities**

This initiative blends real-world trading intuition with data science methods to explore how option Greeks and liquidity structures evolve throughout the trading day.

---

## 🎯 Objectives

- Quantify how **option Greeks (Delta, Gamma, Vega, Theta)** evolve intraday across key strikes
- Detect **volatility pockets** and **sentiment shifts** using strike-level Open Interest and volume aggregation
- Model the **impact of intraday events** on implied volatility and option premiums
- Investigate potential **mispricing or inefficiencies** across expiration dates and strike ladders
- Use this analysis to inform a future ML-based strategy for **predictive modeling or arbitrage detection**

---

## 🧠 Motivation

The rise of leveraged ETFs like TQQQ (3x Nasdaq) has led to highly active options markets with dynamic hedging needs. Understanding intraday patterns and market-maker behavior around these instruments offers insight not only for traders—but also for theorists studying the real-world feedback loop between pricing models and trader behavior.

This research bridges:
- 🧠 **Market psychology** (sentiment & positioning)
- 📊 **Quant mechanics** (Greeks and arbitrage)
- 🤖 **Human-AI symbiosis** (using LLMs to assist in exploratory analysis)

---

## ⏱️ Data Collection Plan

Due to workday constraints, the project will begin with **three daily data captures** from Fidelity Active Trader Pro:

| Capture Time  | Purpose                                       |
|---------------|-----------------------------------------------|
| 10:30 AM ET   | Post-market open adjustment                  |
| 1:00 PM ET    | Midday sentiment & positioning shift         |
| 3:55 PM ET    | Pre-close risk adjustments & gamma squeeze   |

**Captured Fields**:
- Bid/Ask, Last Price
- Volume, Open Interest (OI)
- IV, Delta, Gamma, Vega, Theta
- Strike Price, Expiration Date

---

## 🧰 Tech Stack

- 🐍 **Python** (Pandas, NumPy, Plotly/Matplotlib)
- 📓 **Jupyter Notebook**
- 🧠 **Obsidian** (linked research notes)
- 🗃 **GitHub** for version control
- 💹 **Fidelity ATP exports** for data ingestion

**Future additions:**
- LLM-assisted pattern recognition
- Real-time API integration
- ML modeling (scikit-learn or TensorFlow/Keras)

---

## 🚧 Project Status

- 🟢 Project scaffolded in GitHub
- 🟢 Cadence for data collection defined
- 🔄 Initial dataset gathering + exploratory analysis in progress
- 🔲 Next up: Strike-level aggregation functions + visualizations

---

## ✍️ Author

**Matt [Last Name Redacted]**  
- Portfolio Evaluation Analyst | Series 7 & 65  
- Prior Army Infantry Officer  
- Builder of Project Mnemosyne  
- Passionate about psychology, trading, and the evolution of time-conscious AI systems
