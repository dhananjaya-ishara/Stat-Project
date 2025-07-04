
---

# 🧠📊 Advanced Statistics Final Project – Data Analysis & Forecasting

> A comprehensive statistical analysis project applying **hypothesis testing**, **regression modeling**, and **time series forecasting** on synthetic datasets designed to simulate real-world scenarios.

### 👨‍🎓 Performed by:

* W\.A.C Fernando (26545)
* M.A Pasindu Malinda (26033)
* R.T Dulmina (27999)
* H.K.I Dhananjaya (27595)
* W\.G.M.M.A Mansoor (26775)

---

## 📁 Project Structure

| 📂 Section                | 🔍 Focus                    | 📊 Dataset                                       |
| ------------------------- | --------------------------- | ------------------------------------------------ |
| 🧪 Hypothesis Testing     | T-Test, Mann-Whitney U Test | `health_data.xlsx`, `employee_performance.xlsx`  |
| 📉 Linear Regression      | Multiple Regression, ANOVA  | `house_prices.xlsx`, `employee_salaries.xlsx`    |
| ⏰ Time Series Forecasting | ARIMA, SARIMA Modeling      | `monthly_retail_sales.xlsx`, `weather_data.xlsx` |

---

## 🔧 Tools & Libraries

* `pandas`, `numpy` – Data manipulation
* `matplotlib`, `seaborn`, `plotly` – Visualization
* `scipy.stats`, `statsmodels`, `sklearn` – Statistical testing and regression
* `pmdarima`, `statsmodels.tsa` – Time series modeling

📎 **Code Notebooks:**

* `StatProject.ipynb`
* `forecasting.ipynb`

---

## 📊 Key Techniques Used

### 🧪 Hypothesis Testing

* Parametric **T-Test** on diabetic vs. non-diabetic blood pressure
* **Mann-Whitney U Test** on employee performance based on work hours

### 📉 Linear Regression

* **House Prices**: Modeled using features like square footage, bathrooms, garage, location
* **Employee Salaries**: Based on experience, education level, certifications, and industry type
* **Model Evaluation**: Included ANOVA, VIF (for multicollinearity), residual plots, and heteroscedasticity checks

### ⏰ Time Series Forecasting

* **ARIMA & SARIMA Models**: Applied to monthly sales and daily weather datasets
* Performed **Stationarity Testing** with ADF
* Used **Differencing**, **ACF/PACF** plots for parameter tuning
* Evaluated using **AIC**, **BIC**, **RMSE**, **MAE**, and residual diagnostics

---

## 📌 Summary of Results

### ✅ Hypothesis Testing

* No significant difference in blood pressure between diabetics and non-diabetics
* Significant impact of work hours on employee performance

### ✅ Regression Modeling

* Key predictors for **house prices**: square footage, bathrooms, garage, proximity to city
* Key predictors for **salary**: experience, education, certifications, and industry sector
* High **R² values** indicate strong model fit in both scenarios

### ✅ Time Series Forecasting

* **Retail Sales**: SARIMA outperformed ARIMA slightly in forecasting accuracy
* **Weather Data**: ARIMA provided better forecast accuracy, while SARIMA had lower AIC/BIC
* Both models showed strong predictive ability with normally distributed residuals

---

## ⚠️ Challenges Faced

* Adjusting regression models to be compatible with ANOVA functions (`anova_lm`)
* Designing synthetic datasets with realistic statistical properties
* Addressing **heteroscedasticity** and residual non-normality in regression models

---

## 📷 Sample Visuals (Optional for GitHub)

* 📊 Regression residual & fitted plots
* 🌿 Linear regression output tables (coefficients, R², p-values)
* ⏳ Time series decomposition & stationarity tests
* 📉 ACF/PACF plots and ARIMA/SARIMA forecast graphs

---

## 📄 License

This project is developed for **educational purposes** only as part of an **Advanced Statistics** university coursework. It is **not licensed** for commercial or production use.

---

## 🙌 Acknowledgements

Special thanks to our course instructor, academic mentors, and teammates who contributed to the project and offered continuous guidance throughout the analytical process.

---

### 🚀 Ready to Publish?

Let me know if you'd like:

* This saved as a downloadable `README.md`
* A suggested GitHub folder structure for uploading the datasets and notebooks
* Help adding images/plots for `Sample Visuals` section
* A version formatted for LinkedIn or portfolio presentation

---
