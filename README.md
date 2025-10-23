# World Happiness Report 2024: Statistical Analysis

This project is a practical application of fundamental hypothesis tests (T-test, Z-test, ANOVA, and Chi-Square) to analyze the World Happiness Report (2005-2023 data). The analysis is performed in Python using Pandas, SciPy, and Statsmodels within Jupyter Notebooks.

This project uses `uv` for high-speed environment and package management.

## Project Structure

-   `/notebooks`: Contains all Jupyter Notebooks for the analysis.
-   `/data/raw`: The target directory for the raw dataset.
-   `requirements.txt`: A list of all necessary Python libraries.
-   `LICENSE`: The MIT License for this analysis code.

---

## 💾 Data Source & Setup

This repository follows best practices and **does not** include the data file. You must download it yourself.

1.  **Get the Data:** Download the data from Kaggle:
    * **Link:** [https://www.kaggle.com/datasets/jainaru/world-happiness-report-2024-yearly-updated](https.org/wikipedia/commons/thumb/b/b2/Gears_icon.svg/24px-Gears_icon.svg.png)
2.  **Place the Data:** Unzip the file and move the `World-happiness-report-updated_2024.csv` file into the `/data/raw/` directory of this project.

## 📊 Summary of Findings

*(Findings based on the 2023 data from the report)*

* **T-Test:** We rejected the null hypothesis. There is a statistically significant difference in happiness scores between selected G7 and Asian powers (p-value < 0.05).
* **Z-Test:** We rejected the null hypothesis. The global average happiness score in 2023 is significantly different from our hypothesized 6.0 (p-value < 0.05).
* **ANOVA:** We rejected the null hypothesis. There is a significant difference in mean happiness scores between at least two of the constructed regions (Europe, N. America, Asia) (p-value < 0.05).
* **Chi-Square Test:** We rejected the null hypothesis. There is a significant association between a country's economy (Rich/Poor) and its happiness (Happy/Unhappy) (p-value < 0.05).