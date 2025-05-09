# 🦠 COVID-19 Global Data Tracker

## 📊 Project Overview

This project analyzes global COVID-19 data using Python and its data science ecosystem. It tracks time-series trends in total cases, deaths, and vaccinations across selected countries (Kenya, United States, India). The analysis includes data cleaning, visualization, and summarizing key insights to help understand pandemic dynamics.

---

## 🧾 Features

- Import and clean real-world COVID-19 data
- Time-series analysis of cases, deaths, and vaccination rollout
- Comparison of metrics across countries
- Visualization using `matplotlib`, `seaborn`, and `plotly`
- Interactive choropleth map of global case distribution
- Markdown summary of key findings

---

## 🛠️ Tools & Libraries

- **Python**
- **pandas** – Data manipulation
- **matplotlib & seaborn** – Static visualizations
- **plotly.express** – Interactive maps and charts
- **Jupyter Notebook** – Interactive report combining code and narrative

---

## 📁 Dataset

The analysis uses the **Our World in Data** COVID-19 dataset (`owid-covid-data.csv`), which includes:

- `date`, `location`
- `total_cases`, `total_deaths`, `new_cases`, `new_deaths`
- `total_vaccinations`, `iso_code`, and more

---

## 📌 Project Workflow

1. **Data Collection**  
   Load the provided `owid-covid-data.csv` dataset.

2. **Data Exploration**  
   Inspect data structure, columns, and missing values.

3. **Data Cleaning**  
   - Filter for Kenya, USA, India  
   - Convert `date` to datetime format  
   - Forward-fill missing numeric values

4. **Exploratory Data Analysis**  
   - Line charts for total cases, deaths, new cases  
   - Death rate calculations  
   - Bar charts for country comparisons

5. **Vaccination Analysis**  
   - Cumulative vaccination trends  
   - (Optional) Pie charts for vaccinated vs unvaccinated

6. **Choropleth Mapping** *(Optional)*  
   - Plot interactive world map of case counts using `plotly`

7. **Insights & Summary**  
   - Markdown cell with documented observations and findings

---

## 📷 Sample Outputs

- 📈 Total COVID-19 Cases Over Time
- 🧮 Death Rate Trends
- 💉 Vaccination Progress Line Charts
- 🌍 Interactive Choropleth Map (saved as HTML)

---

## 🚀 How to Run

1. Open the project in **VS Code**
2. Install extensions:
   - Jupyter
   - Python
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn plotly nbformat 

4. Open `covid_analysis.ipynb`
5. Run all cells sequentially
6. View interactive map in `covid_choropleth_map.html` (if using .py script)

---

## 📌 Notes

* Some features (e.g., interactive plots) only work in Jupyter environments.
* The choropleth map is saved as an HTML file to avoid MIME-type errors in non-notebook environments.

---

## 📚 Credits

* **Dataset Source**: [Our World in Data – COVID-19 Dataset](https://www.kaggle.com/datasets/sandhyakrishnan02/latest-covid-19-dataset-worldwide)

---

## 📝 License

This project is for educational purposes. Dataset is used under terms specified by Our World in Data.
