# 🌱 Forecasting Renewable Electricity Production for Sustainable Energy Planning

This project builds regression machine learning models to predict renewable electricity production using country-level energy and environmental indicators. The goal is to support sustainability planning, improve understanding of renewable energy trends, and explore how energy-related variables influence renewable electricity generation.

---

# Problem and Hypothesis

This project predicts renewable electricity production using features such as electricity generation, non-hydro renewable energy indicators, renewable energy statistics, and country-level energy measurements.

My hypothesis is that electricity generation and renewable energy indicators significantly influence renewable electricity production. I also expect Random Forest Regression to outperform Linear Regression because relationships between energy production variables may be nonlinear and more complex than simple linear patterns.

---

# Dataset

## Source
Kaggle Renewable Energy Dataset  
https://www.kaggle.com/code/khushipitroda/renewable-energy

## What it contains
The dataset contains country-level renewable electricity and energy-related indicators collected across multiple countries.

### Target Variable
- Renewable electricity production

### Example Features
- Electricity generation indicators
- Non-hydro renewable energy statistics
- Renewable energy percentages
- Country-level energy measurements
- Electricity-related indicators

---

# ⚙️ Installation

```bash
pip install -r requirements.txt

```


# 👨‍💻 Usage

Run the notebook:

```bash
notebooks/regression_capstone.ipynb
```

(or use `jupyter notebook` if preferred).

The notebook will:

- Load and preprocess the renewable energy dataset
- Perform exploratory data analysis
- Generate visualizations and feature importance plots
- Train Linear Regression and Random Forest Regression models
- Evaluate model performance using regression metrics
- Save trained models and reports into the outputs folder

# 📂 Folder Structure

- `data/raw/` – Original renewable_energy.csv
- `data/processed/` – Cleaned version
- `notebooks/` – Main regression notebook
- `outputs/models/` – Saved trained models showing model performance
- `outputs/reports/` – Evaluation summaries
- `requirements.txt` – Project dependencies
- `README.md` – Project documentation

# 📝 Ethical and Sustainability Notes

Predictions are intended to support sustainability planning and renewable energy analysis.

The project does not use personal or sensitive human data. However, model predictions should be treated as decision-support tools rather than replacements for expert analysis or government energy planning systems.

Potential limitations include:

- Regional economic differences
- Missing environmental variables
- Policy changes affecting renewable energy production
- Limited dataset size

# 🖇️ Dependencies

Listed in `requirements.txt`
