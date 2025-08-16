# 🌍 External Debt Analysis: A Case Study with World Bank Data

This project analyzes **external debt statistics** using a Jupyter Notebook 🐍 and data from the **World Bank's International Debt Statistics (IDS)**.
It explores **debt trends** and **key financial ratios** through a combination of **Python-based analysis** and **SQL queries**.

---

## 📊 Dataset

* **Source:** [World Bank International Debt Statistics (IDS)](https://databank.worldbank.org/source/international-debt-statistics)
* **Focus:** Selected indicators related to **external debt** and their **evolution over time**.
* **Processing:** Raw IDS data is cleaned and structured for analysis.

---

## 📈 Analysis & Findings

### 🔹 Python Analysis

* Tools: `pandas`, `matplotlib`, `seaborn`
* Key Finding: **Total External Debt Stocks** showed a **steady increase from 2013 to 2023**.
* Visualization highlights the **49.68% growth** in debt during this period.

### 🔹 SQL Analysis

* Data stored in an **in-memory SQLite database** for querying.
* Key results:

  * **Total Debt (2023):** `$646,787.1 million`
  * **Percentage Change (2013 → 2023):** `+49.68%`
  * **Debt Ratios (2023):**

    * External debt stocks to **exports (%)** → `79.7%`
    * External debt stocks to **GNI (%)** → `18.4%`
  * **Highest Debt Service Ratio:** `2014 → 18.6%`

---

## 🛠️ How to Use

1. **Clone the repository**

```bash
git clone https://github.com/deep-khimani/Indian-External-Debt-Analysis-2013-2023-.git
```

2. **Install dependencies**

```bash
pip install pandas numpy matplotlib seaborn
```

3. **Download dataset**

   * Obtain the data from the **World Bank IDS** website.

4. **Run the Jupyter notebook**

```bash
jupyter notebook debt_analysis.ipynb
```

⚠️ Replace the placeholder `UPLOAD YOUR DATASET` with your local dataset file path.

---

## 📂 Project Structure

```
├── debt_analysis.ipynb   # Main analysis notebook  
├── dataset/                 # Folder for dataset (not included in repo)  
├── README.md             # Project documentation  
```

---

## 📚 Sources

* 🌐 [World Bank International Debt Statistics (IDS)](https://databank.worldbank.org/source/international-debt-statistics)

---

Would you like me to also **add example plots (matplotlib/seaborn outputs)** into the README (with `![plot](assets/plot.png)` style) so that it looks more professional?
