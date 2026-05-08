# 🌱 Predicting Renewable Electricity Production for Sustainable Energy Planning

Renewable electricity generation is essential for reducing greenhouse gas emissions and supporting sustainable development. However, renewable energy production differs significantly across countries due to economic, environmental, and infrastructure-related factors.

This project explores how regression machine learning models can predict renewable electricity production using country-level energy and environmental indicators. The goal is to support more informed sustainability planning and improve understanding of the factors that influence renewable energy generation.

## Research Question and Hypothesis

**How do electricity prices and country-level energy indicators influence renewable electricity production?**

Electricity prices and country-level energy indicators are expected to significantly influence renewable electricity production.
It is hypothesized that regression machine learning models will be able to predict renewable electricity generation with reasonable accuracy using economic and energy-related indicators.
Additionally, tree-based models such as Random Forest Regression are expected to outperform linear models because relationships between energy production and economic indicators may be nonlinear.

## 📊 Dataset
- **Source:**
  https://www.kaggle.com/code/khushipitroda/renewable-energy
  
This project uses a renewable electricity dataset containing country-level energy indicators associated with renewable electricity generation.

The dataset includes renewable electricity statistics collected across different countries and is used to predict renewable electricity production through regression machine learning models.

**The dataset was selected because:**
- It directly relates to environmental sustainability and clean energy
- Renewable electricity forecasting is an important real-world challenge
- The target variable is continuous, making it appropriate for regression analysis
- The dataset contains measurable country-level indicators that may influence renewable electricity generation

## 📌 Sustainability Relevance

Renewable energy is essential for reducing dependence on fossil fuels and lowering greenhouse gas emissions.

**Machine learning models that can predict renewable electricity production may help organizations:**
- Improve renewable energy planning
- Support sustainable infrastructure development
- Reduce dependence on non-renewable energy sources
- Improve long-term energy forecasting
- Support climate-conscious policy decisions

## 🎯 Features and Target Variable
The dataset contains country-level indicators related to renewable electricity production.

**Independent Variables (Features)**
Example features may include:
- Country-level electricity indicators
- Electricity prices
- Renewable energy statistics
- Energy consumption indicators
- Country or regional energy measurements

**Dependent Variable (Target)**
- Renewable electricity production

## ❗️ Ethical and Licensing Considerations

This dataset does not contain personal or sensitive human data.
However, renewable electricity predictions should be used as decision-support tools rather than replacements for expert energy planning systems.
Incorrect predictions could potentially lead to inefficient energy planning or sustainability decisions if models are used without human oversight.

**The model may also be limited by:**
- Regional economic differences
- Changing energy policies
- Missing environmental variables
- Differences in renewable energy infrastructure across countries
