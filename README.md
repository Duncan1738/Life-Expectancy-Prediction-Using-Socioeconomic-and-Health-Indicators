 📘 Life Expectancy Prediction Using Socioeconomic and Health Indicators

This project explores and predicts **life expectancy** using a range of socioeconomic and health-related indicators from the **World Health Organization (WHO)** dataset. It applies data analysis, feature selection, machine learning, and explainability techniques to identify key factors influencing life expectancy across countries.

---

## 📌 Project Objectives

- Perform data cleaning and preprocessing on the WHO Life Expectancy dataset
- Explore patterns using visualizations and correlations
- Train multiple machine learning models to predict life expectancy
- Compare model performance (Linear Regression, Random Forest, XGBoost)
- Use **SHAP** to interpret model predictions and identify key features

---

## 📊 Dataset

- **Source**: [WHO via Kaggle](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)
- **Features** include:
  - GDP
  - Schooling
  - Alcohol use
  - Immunization coverage
  - HIV/AIDS prevalence
  - Health expenditure
  - Status (Developed/Developing)
  - Mortality indicators

---

## 🧪 Methods

| Task                     | Tools/Techniques                          |
|--------------------------|-------------------------------------------|
| Data Exploration         | Pandas, Seaborn, Matplotlib               |
| Data Preprocessing       | Null handling, feature encoding           |
| Modeling                 | Linear Regression, Random Forest, XGBoost|
| Evaluation               | RMSE, R²                                  |
| Explainability           | SHAP (TreeExplainer, summary plots)       |

---

## 🔬 Key Insights

- Countries with higher schooling, health expenditure, and immunization coverage tend to have higher life expectancy.
- HIV/AIDS prevalence, adult mortality, and thinness are negatively correlated.
- SHAP plots show **schooling**, **income level**, and **BMI** as top positive predictors.

---

## 📁 Folder Structure
life-expectancy-prediction/ ├── Life Expectancy Data.csv ├── life_expectancy_model.ipynb ├── README.md ├── requirements.txt (optional) └── life_expectancy_xgb_model.pkl (optional, saved model)


---

## 🧠 Future Work

- Incorporate geospatial analysis and choropleth maps
- Add interactive dashboards (Plotly Dash or Streamlit)
- Integrate temporal trends by region or continent

---

## 👤 Author

**Duncan Kibet**  
PhD Student, Big Data & Industrial Engineering  
Chosun University

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---



