# Statistical Inference & Parametric Hypothesis Testing Audit

## 📌 Project Overview
This data analytics project focuses on statistical computing and parametric inference using localized sample datasets. The objective is to perform a rigorous One-Sample T-Test to evaluate whether the empirical sample mean deviates significantly from a standardized population benchmark. 

Even with a lean data distribution, this framework establishes baseline validation principles required for corporate auditing, quality assurance control, and performance profiling.

---

## 🛠️ Core Tech Stack
* **Language:** Python 3.x
* **Statistical Computing:** SciPy (Stats Module), NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 🧪 Statistical Methodology & Hypothesis Design
The project applies a formal Independent One-Sample T-Test to statistically evaluate the data behavior against a hypothesized population mean baseline ($\mu = 160$).

### 🔍 Hypothesis Testing Setup:
* **Null Hypothesis ($H_0$):** The true sample mean is statistically equal to the hypothesized baseline value ($\mu = 160$).
* **Alternative Hypothesis ($H_1$):** The true sample mean significantly differs from the hypothesized baseline value ($\mu \neq \mu 160$).
* **Significance Level ($\alpha$):** Evaluated at $\alpha = 0.05$ (95% Confidence Interval) to determine mathematical variance.

---

## 📊 Exploratory Data Analysis & Visualizations
To evaluate the normality and probability density of the sample values, the pipeline generates a customized Distribution Chart:
* **Sample Density & Comparison Profiling:** Built using Seaborn's `sns.histplot` paired with a continuous Kernel Density Estimate (KDE) curve. 
* It features a fixed vertical variance axis (`plt.axvline`) representing the population benchmark, allowing instant visual auditing of how data quantiles cluster around the baseline target.# Statistical-Inference-and-Hypothesis-Testing-Audit

