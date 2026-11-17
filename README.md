<div align="center">

# 🐼 Pandas for Data Analysis

**Learn Pandas the practical way: 17 question-driven lessons on real datasets (Fortune 500, Instacart, IPL, Zomato), from your first DataFrame to merges, pivot tables and missing-value handling.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Runs%20on-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Intermediate-0EA5A4)

</div>

---

## 🎯 How this course works

Every lesson is built around **real business questions**, such as *“Which sector earns the most?”*, *“Who is the most frequent CEO?”*, *“What are the top products in department 13?”*, so you learn each Pandas function by actually using it to answer something.

- 📝 **Practice notebooks** give you the questions with empty code cells. Try them yourself first.
- ⭐ **Guide notebooks** (complete merge guide, `dropna`/`fillna`, CSV handling, profiling) are fully worked, explained step by step.
- 📂 **Datasets are included** next to the notebooks, so everything runs as soon as you clone the repo.

---

## 📚 Module 1: Pandas fundamentals

| # | Lesson | What you'll learn |
|---|---|---|
| 1 | [Pandas introduction](1.%20Pandas%20fundamentals/1.%20Pandas%20introduction.ipynb) | Series vs DataFrame, importing data, head / tail / sample, key attributes |
| 2 | [Fetching rows & columns](1.%20Pandas%20fundamentals/2.%20%28Filtering%29Fetching%20rows%20and%20columns%20using%20iloc.ipynb) | Selecting single/multiple columns and rows with `iloc` |
| 3 | [Conditional filtering](1.%20Pandas%20fundamentals/3.%20Filtering%20dataframe%20on%20a%20condition%20_%20Masking%20using%20boolean%20series.ipynb) | Boolean masks, simple and complex (multi-condition) filters |
| 4 | [`value_counts()`](1.%20Pandas%20fundamentals/4.%20THE%20VALUE%20COUNT%20FUNCTION.ipynb) | Frequencies of categorical data: sectors, CEOs, industries |
| 5 | [The `plot()` function](1.%20Pandas%20fundamentals/5.%20The%20Plot%20function.ipynb) | Line, bar, pie and histogram plots straight from Pandas |
| 6 | [Series operations](1.%20Pandas%20fundamentals/6.%20Series%20Operations.ipynb) | `value_counts`, `nunique`, `unique` and Series vs DataFrame |
| 7 | [`sort_values()`](1.%20Pandas%20fundamentals/7.The%20sort_values%28%29%20method.ipynb) | Sorting Series and DataFrames on one or many columns |
| 8 | [`duplicated()` & `drop_duplicates()`](1.%20Pandas%20fundamentals/8.The%20duplicated%28%29_drop_duplicates%28%29%20method.ipynb) | Finding and removing duplicates, and *when* to use them |
| 9 | [`groupby()`](1.%20Pandas%20fundamentals/09.%20The%20Groupby%28%29%20function%20on%20campanies%20data.ipynb) | Split–apply–combine: top/bottom companies and revenue by sector |
| 10 | [`isin()` & `tolist()`](1.%20Pandas%20fundamentals/10.The%20isin%28%29%20function%28new%20function%20discussed.....tolist%28%29%7D.ipynb) | Filtering on lists of values, plus revision problems |
| 11 | [`merge()`: practice](1.%20Pandas%20fundamentals/11.%20The%20merge%20function.ipynb) | Joining Instacart orders and products to answer business questions |
| 12 | [`merge()`: complete guide](1.%20Pandas%20fundamentals/11.%20The_detailed_merge_function.ipynb) | Merging, joining & concatenating DataFrames, step by step ⭐ |
| 13 | [Pivot tables](1.%20Pandas%20fundamentals/12.%20A%20pivot%20table.ipynb) | Aggregating airline passengers over time with `pivot_table()` |
| 14 | [`corr()`](1.%20Pandas%20fundamentals/13.%20The%20corr%20function.ipynb) | Correlation between numeric columns and how to read it |
| 15 | [`rename()`](1.%20Pandas%20fundamentals/14.%20the%20rename%20function.ipynb) | Renaming columns and index labels |
| 16 | [`set_index()` & `reset_index()`](1.%20Pandas%20fundamentals/15.%20The%20set_index%28%29%20and%20reset_index%28%29.ipynb) | Index manipulation and turning a Series back into a DataFrame |
| 17 | [`dropna()` & `fillna()`](1.%20Pandas%20fundamentals/16.%20The%20dropna%28%29%20method%20and%20The%20fillna%28%29%20method.ipynb) | Handling missing values: when to drop vs. when to fill ⭐ |

## 📂 Module 2: Working with CSV files

[Working with CSV files](2.%20CSV%20files%20handling/Working%20with%20CSV%20files.ipynb) covers every `read_csv()` option you'll actually need, including reading from a URL, `sep`, `names`, `index_col`, `header`, `usecols`, `skiprows`, `nrows`, `encoding`, `dtype`, `parse_dates`, `converters`, `na_values` and reading huge files in `chunksize` pieces.

## 📊 Module 3: Automated EDA

[Pandas Profiling](3.%20Pandas%20profiling/Pandas%20Profiling.ipynb): generate a full exploratory data analysis report in one line with **ydata-profiling**.

---

## 🚀 Getting started

```bash
git clone https://github.com/ahmadhassan-aiops/Pandas.git
cd Pandas
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
```

Open a module folder and run the notebooks from inside it. Each notebook reads its dataset from the same folder.
On **Google Colab**, upload the notebook together with its CSV file(s).

---

## 🗂️ Datasets

| Dataset | Used in | Location |
|---|---|---|
| Fortune 500 (2017) | Lessons 1–10, 13–15 | `1. Pandas fundamentals/` |
| Instacart orders & products | Lessons 11 (practice), 16 | `1. Pandas fundamentals/` |
| Seaborn `flights` | Lesson 12 | Loaded automatically with `sns.load_dataset("flights")` |
| HR analytics, IPL matches, movie titles, Zomato | CSV handling | `2. CSV files handling/` |
| Titanic (`train.csv`) | Pandas profiling | `3. Pandas profiling/` |

> **Complete merge guide (lesson 11 ⭐)** also needs `order_products.csv`, `aisles.csv` and `departments.csv`, which are too large to include. Download the **Instacart Market Basket Analysis** dataset from [Kaggle](https://www.kaggle.com/c/instacart-market-basket-analysis) and place the files in `1. Pandas fundamentals/`. The notebooks read semicolon-separated files (`sep=';'`): if your download is comma-separated, simply remove `sep=';'`.

---

## 🧭 Part of a complete Data Science path

This repository is one step in a structured learning path:
**Python basics → NumPy → Pandas → Matplotlib → Seaborn → Statistics → Machine Learning**

- 🐍 [Python for Data Science](https://github.com/ahmadhassan-aiops/python-for-data-science)
- 🔢 [NumPy](https://github.com/ahmadhassan-aiops/Numpy)
- 🐼 **Pandas** ← you are here

---

## 👨‍🏫 About the author

**Ahmad Hassan** | AI Engineer and mentor

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notebooks help you learn, please star the repo. It helps other students find it!
