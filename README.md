<div align="center">

# Prashant Sulaniya

**Machine Learning Engineer — production ML systems, from raw data to deployed APIs**

[LinkedIn](https://www.linkedin.com/in/prashant-sulaniya-7a1710376/) · Jaipur, India

</div>

---

I build ML systems end-to-end — not just notebooks. That means proper train/test discipline, model explainability, containerized deployment, and CI/CD: the parts of the job that don't show up on a leaderboard but do show up in production.

Currently working on marketplace and economic-data problems, with a focus on ML engineering roles at Japan-based companies — Mercari among them — and in Germany.

---

## 🔭 Flagship Project

### [Flight Delay Prediction System](https://github.com/Prashant-4527/flight-delay-prediction)

End-to-end pipeline predicting 15+ minute arrival delays across 5.8M US domestic flights (DOT/BTS 2015), from raw data to a served, containerized model.

- **Data:** 5.8M rows cleaned to 5.2M; class imbalance (4.4:1) handled via `scale_pos_weight`, not resampling
- **Modeling:** Logistic Regression → Random Forest → XGBoost, tuned with 3-fold GridSearchCV → **AUC-ROC 0.696** (5-fold CV: 0.677 ± 0.0008)
- **Explainability:** SHAP TreeExplainer for per-prediction reasoning, not just global feature importance
- **Serving:** FastAPI + Pydantic validation, 8/8 tests passing, Dockerized, deployed via GitHub Actions CI/CD
- **Interface:** Streamlit dashboard with a live OpenSky air-traffic overlay

**[Live Dashboard](https://flight-delay-prediction-rbggjwfpafrechjrgbedoy.streamlit.app)** · **[API Docs](https://flight-delay-prediction-1.onrender.com/docs)** · **[Source](https://github.com/Prashant-4527/flight-delay-prediction)**

`Python` `XGBoost` `SHAP` `FastAPI` `Docker` `GitHub Actions` `Streamlit`

---

## 📂 Other Projects

| Project | Description | Stack |
|---|---|---|
| [japan-trade-intelligence](https://github.com/Prashant-4527/japan-trade-intelligence) | Bilateral trade intelligence system for Japan — 6-country comparison, HHI concentration-risk modeling, forecasts validated against real 2024–25 outcomes | Python, Pandas, NumPy |
| [mercari-price-analysis](https://github.com/Prashant-4527/mercari-price-analysis) | EDA and feature engineering on 50K Mercari marketplace listings — price-distribution and category/brand pricing signals | Pandas, NumPy, Seaborn |
| [mercaridb-mysql-30days](https://github.com/Prashant-4527/mercaridb-mysql-30days) | Applied MySQL project modeled on Mercari's schema — query design, indexing, normalization | MySQL |
| [awesome-japan-tech-blogs](https://github.com/Prashant-4527/awesome-japan-tech-blogs) | Curated list of engineering blogs from Japan's top tech companies (Mercari, CyberAgent, LINE, DeNA, and more) | Markdown / curation |

---

## 🛠️ Stack

**Languages:** Python, SQL
**ML / Data:** Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn
**Engineering:** FastAPI, Docker, GitHub Actions, Streamlit, Git
**Currently learning:** Deep learning fundamentals, LLM fine-tuning, LangChain

---

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Prashant-4527&show_icons=true&theme=dark)](https://github.com/Prashant-4527)

Open to ML engineering internships and collaboration — reach out on [LinkedIn](https://www.linkedin.com/in/prashant-sulaniya-7a1710376/)

</div>
