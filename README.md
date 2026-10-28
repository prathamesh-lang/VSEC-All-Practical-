# 📊 Vocational Skill Enhancement Course (VSEC) — Data Science Practicals

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<p align="center">
  <b>A comprehensive, production-grade repository of laboratory assignments for the Vocational Skill Enhancement Course (VSEC).</b><br>
  Covering core Python programming, high-performance numerical computation with NumPy, data wrangling with Pandas, statistical visualization with Matplotlib & Seaborn, and end-to-end Exploratory Data Analysis (EDA).
</p>

[Explore Assignments](#-assignment-index) • [Tech Stack](#-technologies--libraries) • [Quickstart Guide](#-quickstart--execution-guide) • [Assignment Walkthrough](#-detailed-assignment-walkthrough)

</div>

---

## 📌 Overview

This repository houses all laboratory practicals and assignments developed under the **Vocational Skill Enhancement Course (VSEC)** curriculum. The coursework follows a progressive learning path designed to build strong foundations in **Scientific Computing and Applied Data Science**:

1. **Phase 1: Python Core Foundations** — Built-in data structures, numeric computation, math utilities.
2. **Phase 2: Numerical Computing with NumPy** — Multidimensional arrays, slicing, vectorization, universal functions, broadcasting, and probability distributions.
3. **Phase 3: Data Manipulation with Pandas** — Series, DataFrames, dataset inspection, cleaning, missing-value imputation, filtering, and aggregation.
4. **Phase 4: Data Visualization** — Univariate, bivariate, and categorical plots using **Matplotlib** and **Seaborn** with customized multi-plot subplots.
5. **Phase 5: Capstone Exploratory Data Analysis (EDA)** — Full analytical pipeline applied to the famous **Titanic dataset**.

---

## 📂 Repository Structure & Assignment Index

```text
VSEC-All-Practical/
├── Assignment1.py          # Python Core: Data Types, Arithmetic & Built-in Structures
├── Assignment2.py          # NumPy: Array Creation, Indexing, Slicing & Matrix Operations
├── Assignment3.py          # NumPy: Vectorized Math, Universal Functions (UFuncs) & Broadcasting
├── Assignment4.py          # NumPy: Random Sampling, Distributions & Statistical Simulations
├── Assignment5.py          # Pandas: Series, DataFrames, Summaries & CSV File I/O
├── Assingment6.py          # Pandas: Data Preprocessing, Missing Value Imputation & Filtering
├── Assignment7.ipynb       # Matplotlib: Line, Bar, Scatter & Histogram Visualizations
├── Assignment8.ipynb       # Matplotlib: Multi-plot Layouts, Subplots, Custom Legends & Grids
├── Assignment9.ipynb       # Seaborn: Statistical Line, Bar, KDE Histograms, Box & Scatter Plots
├── Assignment10.ipynb      # Capstone EDA: Comprehensive Titanic Dataset Analysis & Heatmaps
└── README.md               # Repository Documentation
```

### 📋 Assignment Summary Table

| Assignment | Topic / Domain | File | Primary Tool | Key Topics & Highlights |
| :---: | :--- | :--- | :---: | :--- |
| **01** | **Python Core Foundations** | [`Assignment1.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment1.py) | Python 3, `math` | Numeric types (`int`, `float`, `complex`), strings, lists, tuples, dictionaries, sets, and booleans. |
| **02** | **NumPy Arrays & Matrices** | [`Assignment2.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment2.py) | `numpy` | 1D & 2D array creation (`arange`, `linspace`), slicing, multi-axis indexing, matrix reshaping. |
| **03** | **Vectorization & Broadcasting** | [`Assignment3.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment3.py) | `numpy` | Vectorized operations (`np.add`, `np.sqrt`, `np.exp`), scalar broadcasting, multi-dimensional array math. |
| **04** | **Random Sampling & Statistics** | [`Assignment4.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment4.py) | `numpy` | Uniform, standard normal, and custom Gaussian distributions, descriptive statistics (`mean`, `std`, `min`, `max`). |
| **05** | **Pandas Data Structures & I/O** | [`Assignment5.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment5.py) | `pandas` | `Series` & `DataFrame` creation, structural introspection (`head`, `tail`, `describe`, `info`), CSV export/import. |
| **06** | **Data Cleaning & Wrangling** | [`Assingment6.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assingment6.py) | `pandas` | Missing value audit (`isnull`), mean imputation (`fillna`), `dropna`, categorical replacements, boolean masks, sorting. |
| **07** | **Fundamental Plotting (Matplotlib)** | [`Assignment7.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment7.ipynb) | `matplotlib` | Line plots, categorical bar charts, scatter plots for correlation, frequency distribution histograms. |
| **08** | **Advanced Subplots & Styling** | [`Assignment8.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment8.ipynb) | `matplotlib` | Multi-figure subplots (`plt.subplots`), custom line styles, marker tuning, color palettes, legends, and grid layouts. |
| **09** | **Statistical Graphics (Seaborn)** | [`Assignment9.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment9.ipynb) | `seaborn` | Statistical line plots, bar plots, KDE histograms (`histplot`), box plots for outlier detection, and scatter plots. |
| **10** | **End-to-End Titanic EDA** | [`Assignment10.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment10.ipynb) | `pandas`, `seaborn` | Full analytical pipeline: data ingestion, null audits, summary statistics, correlation heatmaps, passenger survival analysis. |

---

## 🛠️ Technologies & Libraries

The practicals are implemented using Python's premier scientific and data stack:

- **Language:** [Python 3.9+](https://www.python.org/)
- **Numerical Computing:** [NumPy](https://numpy.org/) (`numpy`)
- **Data Wrangling:** [Pandas](https://pandas.pydata.org/) (`pandas`)
- **Data Visualization:** [Matplotlib](https://matplotlib.org/) (`matplotlib.pyplot`) & [Seaborn](https://seaborn.pydata.org/) (`seaborn`)
- **Interactive Environment:** [Jupyter Notebook](https://jupyter.org/) / IPython

---

## 🚀 Quickstart & Execution Guide

### 1. Clone the Repository

```bash
git clone https://github.com/prathamesh-lang/VSEC-All-Practical-.git
cd VSEC-All-Practical-
```

### 2. Set Up a Virtual Environment (Recommended)

```bash
# On Windows (PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1

# On Linux / macOS
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Install all requisite packages with a single command:

```bash
pip install numpy pandas matplotlib seaborn jupyter ipykernel
```

### 4. Running Python Scripts (Assignments 1–6)

Run any Python script directly in your terminal:

```bash
# Run Assignment 1 (Python Core)
python Assignment1.py

# Run Assignment 2 (NumPy Arrays)
python Assignment2.py

# Run Assignment 6 (Pandas Data Cleaning)
python Assingment6.py
```

### 5. Running Jupyter Notebooks (Assignments 7–10)

Launch the Jupyter environment to interactively run the visualization and EDA notebooks:

```bash
jupyter notebook
```
*Alternatively, open the repository in **VS Code** or **Antigravity IDE** and run cells interactively with the Python extension.*

---

## 📖 Detailed Assignment Walkthrough

<details>
<summary><b>🔹 Assignment 1: Python Core Data Types & Operations</b></summary>

- **File:** [`Assignment1.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment1.py)
- **Objective:** Master native Python numeric types, strings, and built-in collection structures.
- **Topics Covered:**
  - `int`, `float`, `complex` numbers with real/imag parts and magnitude calculations.
  - `math` module utilities (`math.ceil`, `math.floor`, `round`, `abs`).
  - String manipulation, formatting, transformations (`upper`, `lower`), and slicing.
  - CRUD operations and methods on `list`, `tuple`, `set`, and `dict`.
</details>

<details>
<summary><b>🔹 Assignment 2: NumPy Array Creation, Indexing & Slicing</b></summary>

- **File:** [`Assignment2.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment2.py)
- **Objective:** Understand high-performance homogeneous n-dimensional arrays (`ndarray`).
- **Topics Covered:**
  - Array initialization via lists, `np.arange()`, and `np.linspace()`.
  - 1D slicing, negative indexing, and step reversals (`arr[::-1]`).
  - 2D matrices, dimensional inspection (`shape`, `ndim`, `size`, `dtype`).
  - Row/column filtering, submatrix extraction, and array reshaping/flattening.
</details>

<details>
<summary><b>🔹 Assignment 3: Vectorized Operations, UFuncs & Broadcasting</b></summary>

- **File:** [`Assignment3.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment3.py)
- **Objective:** Perform element-wise operations without explicit Python loops.
- **Topics Covered:**
  - Vectorized addition, subtraction, division, and multiplication.
  - Universal mathematical functions: `np.sqrt()`, `np.exp()`, trigonometric functions.
  - Broadcasting rules across scalars, 1D vectors, and 2D matrices.
</details>

<details>
<summary><b>🔹 Assignment 4: Random Sampling & Statistical Simulations</b></summary>

- **File:** [`Assignment4.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment4.py)
- **Objective:** Generate pseudo-random distributions and perform descriptive statistical analysis.
- **Topics Covered:**
  - Random number generators (`np.random.rand`, `np.random.randn`, `np.random.randint`, `np.random.normal`).
  - Empirical distribution metrics: `mean`, `median`, `std`, `var`, `min`, `max`.
  - Simulating large-sample datasets ($N = 1000$) to evaluate law-of-large-numbers behavior.
</details>

<details>
<summary><b>🔹 Assignment 5: Pandas Data Structures & Data I/O</b></summary>

- **File:** [`Assignment5.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment5.py)
- **Objective:** Work with tabular data structures using Pandas Series and DataFrames.
- **Topics Covered:**
  - Creating 1D `pd.Series` and 2D `pd.DataFrame` from Python mappings.
  - Inspecting structures with `df.head()`, `df.tail()`, `df.describe()`, `df.shape`.
  - Column schema inspection (`df.columns`, `df.dtypes`).
  - Data persistence: exporting to CSV (`to_csv()`) and reading data from disk (`read_csv()`).
</details>

<details>
<summary><b>🔹 Assignment 6: Data Cleaning, Missing Value Imputation & Filtering</b></summary>

- **File:** [`Assingment6.py`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assingment6.py)
- **Objective:** Clean and preprocess raw, noisy tabular data for downstream analytics.
- **Topics Covered:**
  - Detecting missing data with `isnull()` and column-wise aggregations (`isnull().sum()`).
  - Imputing missing numeric features using mean imputation (`fillna()`).
  - Dropping incomplete observations with `dropna()`.
  - Categorical data normalization (`replace()`).
  - Boolean conditional filtering and multi-column sorting (`sort_values()`).
</details>

<details>
<summary><b>🔹 Assignment 7: Fundamental Visualization with Matplotlib</b></summary>

- **File:** [`Assignment7.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment7.ipynb)
- **Objective:** Build standard 2D statistical plots using `matplotlib.pyplot`.
- **Topics Covered:**
  - **Line Plot:** Trend tracking with markers and axis labels.
  - **Bar Chart:** Categorical comparisons.
  - **Scatter Plot:** Variable correlation and bivariate distributions.
  - **Histogram:** Frequency distributions and binning analysis.
</details>

<details>
<summary><b>🔹 Assignment 8: Subplots, Advanced Styling & Layouts</b></summary>

- **File:** [`Assignment8.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment8.ipynb)
- **Objective:** Compose professional multi-panel figures and fine-tune chart aesthetics.
- **Topics Covered:**
  - Multi-plot figures using `plt.subplots(nrows, ncols)`.
  - Line styles (`solid`, `dashed`, `dotted`), custom colors, and data point markers.
  - Custom legends, grid configuration (`plt.grid(True)`), and tight layouts.
</details>

<details>
<summary><b>🔹 Assignment 9: Statistical Graphics with Seaborn</b></summary>

- **File:** [`Assignment9.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment9.ipynb)
- **Objective:** Leverage high-level statistical plotting with Seaborn.
- **Topics Covered:**
  - `sns.lineplot()` & `sns.barplot()` with automated error estimation.
  - `sns.histplot()` with Kernel Density Estimation (KDE) overlays.
  - `sns.boxplot()` for quartile analysis and outlier identification.
  - `sns.scatterplot()` for multi-dimensional data relations.
</details>

<details>
<summary><b>🔹 Assignment 10: Capstone Exploratory Data Analysis (Titanic EDA)</b></summary>

- **File:** [`Assignment10.ipynb`](file:///c:/Users/USER/Desktop/VSEC%20%20CODES/VSEC-All-Practical-main/VSEC-All-Practical-/Assignment10.ipynb)
- **Objective:** Perform a complete real-world Exploratory Data Analysis pipeline on the Titanic dataset.
- **Key Pipeline Steps:**
  1. **Data Ingestion:** Load Titanic passenger records directly via Seaborn.
  2. **Data Profiling:** Inspect shape, column data types, and five-number summaries.
  3. **Null Value Auditing:** Detect and visualize missing patterns across `age`, `embarked`, `deck`.
  4. **Correlation Analysis:** Compute numeric correlation matrices (`df.corr()`) and render visual heatmaps (`sns.heatmap`).
  5. **Demographic Survival Analysis:** Uncover actionable insights on survival probability segmented by Passenger Class, Gender, and Fare paid.
</details>

---

## 🎯 Key Learning Outcomes

By working through these practicals, students gain practical mastery over:

- [x] Writing idiomatic, modular Python code for data processing.
- [x] Vectorized mathematical operations avoiding slow nested iterations.
- [x] Data cleaning workflows: missing value imputation, row filtering, and feature encoding.
- [x] Crafting publication-quality visualizations for business and scientific reporting.
- [x] Performing structured end-to-end Exploratory Data Analysis (EDA) on real-world datasets.

---

## 👨‍💻 Author & Contribution

Developed with ❤️ by **[Prathamesh](https://github.com/prathamesh-lang)** as part of the **VSEC Practical Coursework**.

Contributions, suggestions, and enhancements are always welcome! If this repository helped you in your academics or practical prep:
- ⭐ **Star this repository** on GitHub!
- 🍴 **Fork the project** to add your own experiments.
- 🐛 **Open an issue** if you encounter any errors or have recommendations.

---

## 📄 License

This repository is distributed under the **MIT License**. Feel free to use, modify, and share this code for academic and learning purposes.