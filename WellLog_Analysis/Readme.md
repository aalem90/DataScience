This project performs geological data analysis on oil and gas well logs using Python. Based on the uploaded notebook, I have created a `README.md` file that you can use for your GitHub repository.

---

# Well Log Analysis and Lithofacies Classification

This repository contains a comprehensive workflow for analyzing well log data to identify geological formations (lithofacies) and evaluate reservoir potential in petroleum engineering.

## 🚀 Project Overview

The project processes raw subsurface data to visualize well logs, calculate petrophysical properties, and analyze the distribution of different facies. It specifically focuses on identifying hydrocarbon versus brine zones using resistivity and porosity indicators.

## 📊 Key Features

* **Automated Data Loading:** Integrated with Google Colab for easy CSV data ingestion.
* **Petrophysical Unit Conversion:** Automates the conversion of log units (e.g., converting `ILD_log10` to `Rt_ohmm` and percentage porosity to decimal) for standardized analysis.
* **Statistical EDA:** Generates descriptive statistics and histograms to understand data distribution across variables like Gamma Ray (GR), Depth, and Photoelectric Effect (PE).
* **Log Visualization:** Multi-track plotting of well data including:
* **Gamma Ray:** For lithology identification.
* **Resistivity:** For fluid identification (Hydrocarbon vs. Brine).
* **Porosity (PHIND/DeltaPHI):** For reservoir quality assessment.
* **Facies Track:** Visualization of geological environment heterogeneity.



## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** * `Pandas` & `NumPy`: Data manipulation and numerical calculations.
* `Matplotlib` & `Seaborn`: Advanced plotting and data visualization.



## 📈 Key Geological Insights

Based on the analysis performed in this notebook:

1. **Lithology Identification:** Low Gamma Ray (GR) values effectively differentiate clean sand units from shaly intervals.
2. **Fluid Identification:** High resistivity spikes (e.g., at ~2,820 ft and ~3,110 ft) combined with clean sand indicators signal potential **Hydrocarbon Pay Zones**.
3. **Facies Correlation:** The project identifies a shift from cool-colored facies (Sands) to warm-colored facies (Likely tighter or shaly units) at the base of the analyzed well, indicating a highly heterogeneous environment.

## 📂 File Structure

* `FaciesAnalysis.ipynb`: The main Jupyter Notebook containing the analysis pipeline.
* `facies_data2.csv`: (Required) The input dataset containing well log measurements and facies labels.


---
