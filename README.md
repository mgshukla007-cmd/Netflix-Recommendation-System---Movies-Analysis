# Netflix Content Strategy Analysis

### Data-Driven Insights for Global Streaming Optimization

## 📌 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on Netflix's content library. By leveraging Python, I analyzed trends in content production, geographical distribution, and rating patterns to identify strategic opportunities for content acquisition and production.

## 🛠️ Technical Toolkit

* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization)
* **Environment:** Jupyter Notebook / VS Code

## 🚀 Project Roadmap

| Stage | Status |
| --- | --- |
| **Data Cleaning & Preprocessing** | 🟢 Complete |
| **Exploratory Data Analysis** | 🟢 Complete |
| **Statistical Distribution Analysis** | 🟢 Complete |
| **Key Insights Generation** | 🟢 Complete |
| **Advanced Visualization** | 🟢 Complete |

---

## 🔍 Key Analysis & Methodology

### 1. Data Cleaning

* Handled missing values in critical columns like `Director`, `Cast`, and `Country`.
* Converted date strings into datetime objects for chronological analysis.
* Handled outliers in `Popularity` and `Vote_Count` using statistical filtering.

### 2. Core Insights

* **Content Trends:** Analysis of the shift from Movies to TV Shows over the last decade.
* **Geographical Dominance:** Identified top-performing regions and emerging markets for Netflix.
* **Rating Distribution:** Evaluated how content is categorized (e.g., TV-MA vs. TV-14) and its impact on audience reach.
* **Feature Correlation:** Investigated the relationship between `Popularity`, `Vote_Average`, and `Vote_Count`.

### 3. Visualizations

The project utilizes advanced Seaborn plots to visualize:

* Year-over-year content growth.
* Distributions of popularity (highlighting the **Right-Skewed** nature of the data).
* Correlation heatmaps between numerical features.

---

## 📈 Key Findings

* **Skewed Success:** As identified in the `describe()` analysis, a small percentage of "blockbuster" content drives the majority of `Popularity` and `Vote_Count`, creating a significant right-skew.
* **Growth:** There is a marked increase in international content production, specifically in regions outside of North America.

## 📁 Repository Structure

```text
├── data/                    # Raw and cleaned datasets
├── notebooks/               # Jupyter Notebooks with step-by-step EDA
├── README.md                # Project documentation
└── .gitignore               # Files excluded from version control

```

## 📬 Contact

**Maharshi Shukla** *AI Engineer & Data Scientist* [[LinkedIn Profile Link]](https://www.linkedin.com/in/er-maharshi-shukla-714750343/) | iamshuklamaharshi@gmail.com
