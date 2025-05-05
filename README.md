# Regime Detection System

## 🧠 Project Overview

The primary goal here is to **identify distinct market regimes** (e.g., trending, ranging, volatile, quiet) using unsupervised and probabilistic learning techniques, without relying on manually labeled data.

The detected regimes will later be used to dynamically adjust trading behavior in the full trading system (e.g., strategy switching, risk adjustment).

---asdasdasdasds

## 🔍 Objectives

- Segment the market into **distinct regimes** using price, volume, and technical features.
- Use these regimes to guide **rule-based trading logic** (e.g., S/R behavior, volatility filters).
- Avoid manual or auto-generated labels; instead rely on **model-discovered structure**.
- Maintain lightweight architecture suitable for solo development and flexible scaling.

---
<!-- 
## 🧩 Project Stages

### Stage 1: Data Engineering
- Extract and clean OHLCV data for Silver (3H, 4H, 1D).
- Engineer key technical features (e.g., ATR, MA slope, ADX, HA candle color).
- Normalize and prepare datasets for model ingestion.

### Stage 2: Model Development
- Apply and compare unsupervised learning models:
  - ✅ KMeans
  - ✅ Gaussian Mixture Model (GMM)
  - ✅ Hidden Markov Model (HMM)
- Optional: Add Autoencoder-based clustering or LSTM later for more advanced temporal modeling.

### Stage 3: Evaluation & Visualization
- Visualize regime overlays on price charts.
- Track how regime shifts relate to price structure, volatility, and support/resistance.
- Assess how each model performs in capturing meaningful transitions.

---

## 📦 Tools & Libraries

- `pandas`, `numpy` – data manipulation
- `ta`, `technical-analysis-lib` – indicator computation
- `scikit-learn` – KMeans, GMM, preprocessing
- `hmmlearn` or `pomegranate` – HMM modeling
- `matplotlib`, `seaborn`, `plotly` – visualization

---

## 🧪 Output

- `regime_labels.csv` – predicted regimes aligned with timestamps
- `model_visuals/` – charts showing clustering overlaid on price
- `evaluation_report.md` – notes comparing model behavior

--- -->

## 📌 Notes

- Regime detection is fully unsupervised.
- This is a standalone module but will later integrate with a reinforcement-based rule-trading agent.
- All models are interpretable and evaluated based on market logic, not just statistical fit.

---

