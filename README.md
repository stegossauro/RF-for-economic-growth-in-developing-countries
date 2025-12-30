# Economic Growth & Machine Learning Analysis

### Project Overview

This thesis,"Economic Growth Through the Lens of Data Science", is the synergy of my studies in **Economic History**, **Macroeconomics**, and **Data Science**. It bridges the gap between the evolution of economic thought—from Smith to Endogenous growth—and modern **Machine Learning**. Using **Python**, I developed **Random Forest** algorithms to forecast global GDP trends, transforming theoretical insights into predictive models. Full code will be on **GitHub** for open-access research.

---

### Key Features

* **Multidisciplinary Approach:** Integration of historical economic theories (Classical, Neoclassical, Endogenous) with modern computational tools.
* **Global Data Analysis:** Processing of macroeconomic indicators for ~150 countries (1980–2023) using `pandas`.
* **Data Visualization:** Comparative analysis of GDP evolution across Africa, Asia, Europe, and South America using `matplotlib`.
* **Advanced Forecasting:** Implementation of a **Random Forest Regressor** enhanced with:
* Temporal features (Years since start, time indexing).
* Lagged variables (Previous year's GDP).
* Statistical indicators (Moving averages and linear trend slopes).
* Hybrid trend adjustment for realistic 2025–2027 forecasts.



---

### Technologies Used

* **Language:** Python 3.x
* **Libraries:** * `pandas` & `numpy`: Data manipulation and cleaning.
* `scikit-learn`: Random Forest Regressor and Linear Regression for trend analysis.
* `matplotlib`: Data visualization and subplotting.


---

### Methodology Notes

The model utilizes a **Random Forest** approach because of its ability to capture non-linear relationships in macroeconomic data—something traditional linear models often miss. To ensure realistic forecasts, the predictions (2025-2027) incorporate a weight-based trend adjustment that combines the ML output with historical linear momentum.

---

### Academic References

* **Author:** Stefano Caronti
* **Degree:** Economics and Management – Università degli Studi di Milano
* **Supervisor:** Prof. Luca Rossini
* **Academic Year:** 2024/2025

---

### How to use

1. Clone the repository.
2. Ensure you have the required libraries installed: `pip install pandas matplotlib scikit-learn numpy`.
3. Update the file path in the script to point to your local version of `world_gdp_data.csv`.
4. Run the script to generate the continent-specific visualizations and future GDP predictions.

---
