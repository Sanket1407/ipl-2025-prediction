
# 🏏 IPL 2025 Prediction — Match & Toss Winner Forecasting

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)
![License](https://img.shields.io/badge/license-MIT-green)
![ML](https://img.shields.io/badge/Machine%20Learning-Random%20Forest-lightgrey)

This repository contains a complete machine learning pipeline to forecast **Toss Winners** and **Match Winners** for the **IPL 2025** season. It uses historical IPL data from 2008–2023 and generates match-by-match predictions along with storytelling-style explanations.

---

## 📁 Project Structure

```
📦 IPL-2025-Prediction
├── IPL_2025_Storytelling_Report.md   # Markdown with match-by-match predictions & insights
└── README.md                         # This file
```

---

## 📊 Features

- Predict toss winners using toss trends and venue/captain history
- Predict match winners using:
  - Historical team performance
  - Toss results
  - Venue-specific advantages
  - Batting vs bowling trends
- Generate a Markdown report with:
  - Match insights
  - Model rationale
  - Head-to-head stats
  - Toss and chasing advantages

---

## 📈 Visualizations

The project also includes:
- Bar and line plots for team trends
- Heatmaps for win distribution
- Cumulative win graphs for 2025 predictions

---

## 🧠 ML Model

- RandomForestClassifier (sklearn)
- Categorical encoding for team/venue/toss_winner
- Feature engineering: win %, toss %, avg scores, venue win rate

---

## 🙌 Credits

Created as part of a Major Capstone Project by [Sanket Parmar]  

---

