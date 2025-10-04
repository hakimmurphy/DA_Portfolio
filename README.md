# 📊 Data & ML Portfolio — Hakim Murphy

Actionable analytics and ML projects focused on real-world business impact: forecasting, classification, NLP, and dashboards. Built with Python, SQL, and Tableau — wrapped in clean narratives and reproducible code.

> Web Dev portfolio site: https://hakimmurphy.github.io/portfolio/

---

## 🧭 What’s inside

- **Featured projects** with problem → approach → outcome, plus code & demo links
- **Reproducible notebooks** (env + data instructions)
- **Dashboards & apps** (Tableau / Streamlit)
- **Write-ups** for non-technical stakeholders

---

## 🏆 Featured Projects

| Project | Domain / Goal | Stack | Live | Repo |
|---|---|---|---|---|
| **Grocery Sales Forecaster (Corporación Favorita)** | Time-series forecasting for weekly demand (inventory & promo planning) | `Python` `pandas` `darts` `XGBoost` `Streamlit` | [Demo](https://forecasterapp-re6sa3sspcdsceht7piq9s.streamlit.app/) | [Repository](https://github.com/hakimmurphy/time_series_corporacion) |
| **E-commerce On-Time Delivery** | Predict late deliveries; surface cost drivers & ops levers | `Python` `scikit-learn` `PPS` `SHAP` | — | [Repository](https://github.com/hakimmurphy/ecommerce_delivery_prediction) |
| **Automotive Price Estimation** | Estimate used-car prices; pricing guidance for dealers | `Python` `scikit-learn` `XGBoost` `PPS` | — | [Repository](https://github.com/hakimmurphy/automotive_estimating_car_prices) |
| **Currency FX Forecasting** | Multi-series FX prediction; model comparison (TFT vs XGB) | `Python` `darts` `statsmodels` `XGBoost` | — | [Repository](https://github.com/hakimmurphy/forecasting_currency_exchange_rates_for_banking_operations) |
| **Restaurant Reviews — Sentiment** | Binary sentiment + insights for service improvements | `Python` `NLP` `TF-IDF` `LinearSVC` | — | [Repository](https://github.com/hakimmurphy/enhancing_restaurant_service_through_sentiment_analysis) |
| **Flower Classification (Oxford-102)** | Transfer learning demo + MLOps notes | `TensorFlow` `Keras` `ResNet` | — | [Repository](https://github.com/hakimmurphy/automating_flower_classification_for_start_up_using_deep_learning) |
| **TravelTide Segmentation** | PCA + K-means for marketing segments & strategy | `Python` `pandas` `scikit-learn` `Tableau` | — | [Repository](https://github.com/hakimmurphy/TravelTide) |
| **NYC Schools Analysis** | SAT, directory, incident, and demographic analysis with a focus on data prep and insightful visuals. | `Python` `GoogleSheets` `pandas` `numpy` `matplotlib` `SQLAlchemy` `psycopg2` `jupyter` | - | [Repository](https://github.com/hakimmurphy/nyc-schools-analysis) |

---

## 🛠️ Tech & Tools

**Data:** `Python` · `pandas` · `NumPy` · `scikit-learn` · `XGBoost` · `statsmodels` · `darts`  
**Viz / Apps:** `Tableau` · `Matplotlib` · `Seaborn` · `Plotly` · `Streamlit`  
**SQL:** `PostgreSQL` · `MySQL`  
**Ops:** `Git` · `GitHub` · `venv` · `Docker` (learning)  
**Cloud (learning):** `GCP` / `AWS` basics

---

## 📂 Repo layout

```
DA_Portfolio/
├─ projects/
│ ├─ corporacion_favorita_forecaster/
│ ├─ ecommerce_delivery_prediction/
│ ├─ automotive_price_estimation/
│ ├─ currency_fx_forecasting/
│ ├─ restaurant_sentiment/
│ └─ traveltide_segmentation/
├─ dashboards/ # Tableau workbooks or links
├─ docs/ # executive summaries, slides
├─ env/ # requirements.txt, environment.yml
└─ README.md # (this file)
```

---

## 🧪 Reproducibility

1. **Python environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   pip install -r env/requirements.txt
   ```

2. **Data access**
  - Public datasets: include a download script or link in each project’s DATA.md.
  - Private data: provide synthetic samples or schema + instructions.

3. **Run notebooks**
  - Open the main notebook in each project (e.g., notebooks/01_exploration.ipynb → 02_modeling.ipynb → 03_evaluation.ipynb).
  - Or run a small entry script: python src/train.py --config configs/base.yaml.

---

## 🧾 Executive summaries (for non-technical readers)
Each project includes:
- **Context & problem** (business framing)
- **Approach** (features, model, evaluation)
- **Key findings** (insights + figures)
- **Impact** (how a team would use it)
- **Limitations** & next steps

---

## 🔗 More work (selected)
- **Web toys & front-end**: GitHub User Search, Mars Rover Photos, CSS playgrounds
- **Mini apps**: To-Do, Notes, Weather, Newsletter Signup
- **Daily UI**: 001–005 (Sign-Up, Checkout, Tattoo mock, Calculator, Logo)

See: [hakimmurphy repositories](https://github.com/hakimmurphy?tab=repositories)

---

## 🙋 About me
Ex-librarian turned data + ML practitioner with a musician’s ear for patterns. I like:
- translating ambiguous questions into small, robust wins
- building explainable models with clean narratives
- pairing and code reviews, and writing clear docs

---

## 📬 Contact
- [GitHub](https://github.com/hakimmurphy)
- [LinkedIn](https://www.linkedin.com/in/hakim-a-murphy/)
- [Email](hakim.a.murphy@gmail.com)

---

## 📄 License
MIT

---

## 🗣️ Author
Hakim Murphy
