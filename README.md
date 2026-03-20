# 📊 Unemployment in India — Exploratory Data Analysis

> **Internship Project | CodeAlpha Data Science Internship**  
> Analyzing unemployment trends across India with a focus on COVID-19 impact, regional disparities, and rural vs. urban workforce differences.

---

## 📌 Project Overview

This project performs an end-to-end exploratory data analysis (EDA) on unemployment data across Indian states and regions. The analysis uncovers how unemployment evolved over time, which regions were hit hardest, and how the COVID-19 pandemic impacted both rural and urban labour markets.

---

## 🗂️ Table of Contents

- [Project Overview](#-project-overview)
- [Dataset](#-dataset)
- [Project Structure](#-project-structure)
- [Key Analysis](#-key-analysis)
- [Visualizations](#-visualizations)
- [How to Run](#-how-to-run)
- [Key Findings](#-key-findings)
- [Internship Context](#-internship-context)

---

## 📁 Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | [Kaggle — Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india) |
| **File** | `Unemployment in India.csv` |
| **Coverage** | Indian states and union territories |
| **Period** | Jan 2020 – Oct 2020 (peak COVID-19 period) |
| **Key Columns** | `Date`, `Region`, `Area` (Rural/Urban), `Unemployment Rate (%)`, `Estimated Employed`, `Labour Participation Rate (%)` |

---

## 📂 Project Structure

```
unemployment-analysis/
│
├── unemployment_analysis.ipynb   # Main analysis notebook
├── Unemployment in India.csv     # Dataset
└── README.md                     # Project documentation
```

---

## 🔍 Key Analysis

The notebook is structured into the following sections:

1. **Data Loading & Preview** — Import and inspect the raw dataset
2. **Data Cleaning**
   - Strip whitespace from column names
   - Parse dates into proper datetime format
   - Rename columns for readability
   - Handle and verify missing values
3. **Exploratory Data Analysis**
   - National unemployment trend over time
   - Top 5 most-affected regions
   - Rural vs. Urban unemployment comparison
   - COVID-19 lockdown impact (March–June 2020)

---

## 📈 Visualizations

| Chart | Description |
|-------|-------------|
| **National Trend** | Average unemployment rate over time with COVID-19 start marker |
| **Top 5 Regions** | Line chart comparing the hardest-hit states |
| **Rural vs. Urban** | Side-by-side trend comparison across area types |
| **COVID-19 Zoom** | Focused view of the lockdown shock (Mar–Jun 2020) |

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/tashkidd1/unemployment-analysis.git
cd unemployment-analysis
```

### 2. Install Dependencies

```bash
pip install pandas matplotlib seaborn jupyter
```

### 3. Launch the Notebook

```bash
jupyter notebook unemployment_analysis.ipynb
```

> Make sure `Unemployment in India.csv` is in the same directory as the notebook before running.

---

## 💡 Key Findings

- 📈 **Unemployment spiked sharply in April 2020**, coinciding with India's national lockdown, reaching rates several times higher than pre-pandemic levels.
- 🏙️ **Urban areas experienced steeper unemployment spikes** compared to rural areas during the peak lockdown months, likely due to the concentration of formal sector employment.
- 🌾 **Rural unemployment, while lower in peak values**, showed higher baseline volatility throughout the analysis period.
- 🗺️ **Regional disparities are significant** — the top 5 worst-affected states showed unemployment rates dramatically higher than the national average.
- 📉 **Recovery began from June 2020**, though unemployment remained elevated compared to pre-pandemic levels for several months.

---

## 🎓 Internship Context

This project was completed as part of the **CodeAlpha Data Science Internship**. The objective was to apply real-world data analysis skills including data wrangling, cleaning, and visualization using Python's core data science stack.

**Skills demonstrated:**
- Data cleaning and preprocessing with Pandas
- Time-series analysis and date handling
- Multi-variable visualization with Matplotlib & Seaborn
- Communicating insights from data through structured EDA

---

## 📬 Contact

 
GitHub: [@tashkidd1](https://github.com/tashkidd1)

---
