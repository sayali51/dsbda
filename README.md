# 📊 DSBDA — Data Science & Big Data Analytics

A collection of **10 hands-on practicals** covering core Data Science and Big Data Analytics concepts using Python (Jupyter Notebooks), along with Hadoop and Apache configurations.

---

## 🗂️ Repository Structure

```
dsbda/
├── prac1.ipynb       # Data Wrangling I
├── prac2.ipynb       # Data Wrangling II
├── prac3.ipynb       # Descriptive Statistics
├── prac4.ipynb       # Data Analytics I — Linear Regression
├── prac5.ipynb       # Data Analytics II — Logistic Regression
├── prac6.ipynb       # Data Analytics III — Naïve Bayes
├── prac7.ipynb       # Text Analytics
├── prac8.ipynb       # Data Visualization I
├── prac9.ipynb       # Data Visualization II
├── prac10.ipynb      # Data Visualization III
├── apache/           # Apache configuration files
├── apache 2/         # Apache configuration files (extended)
├── hadoop/           # Hadoop setup and configuration
└── weather/          # Weather dataset used in practicals
```

---

## 📓 Practicals Overview

| # | Title | Key Concepts |
|---|-------|-------------|
| 1 | Data Wrangling I | Loading datasets, handling missing values, data cleaning with Pandas |
| 2 | Data Wrangling II | Merging, grouping, filtering, and transforming data |
| 3 | Descriptive Statistics | Mean, median, mode, standard deviation, variance, correlation |
| 4 | Data Analytics I | Linear Regression using Scikit-learn, model evaluation (MSE, R²) |
| 5 | Data Analytics II | Logistic Regression, classification report, confusion matrix |
| 6 | Data Analytics III | Naïve Bayes classifier, prior/posterior probabilities |
| 7 | Text Analytics | Tokenization, TF-IDF, word frequency, sentiment analysis |
| 8 | Data Visualization I | Histograms, box plots, scatter plots using Matplotlib/Seaborn |
| 9 | Data Visualization II | Pair plots, heatmaps, correlation matrix visualization |
| 10 | Data Visualization III | Advanced charts — bar, pie, area plots; dashboard-style layouts |

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing
- **Scikit-learn** — Machine learning models
- **Matplotlib / Seaborn** — Data visualization
- **NLTK** — Natural language processing (Text Analytics)
- **Apache Hadoop** — Big Data processing (configuration included)

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/sayali51/dsbda.git
cd dsbda
```

### Clone a specific notebook in Google Colab

```python
!curl -L -o prac.ipynb "raw_file_link_here"
```

> Replace `raw_file_link_here` with the raw GitHub URL of any notebook (e.g., from the **Raw** button on GitHub).

### Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📁 Datasets

- **Weather dataset** — Used across multiple practicals for regression, classification, and visualization exercises.

---

## 📌 Notes

- All notebooks are self-contained and can be run independently.
- Ensure required datasets are in the same directory as the notebook, or update the file path inside the notebook.
- For Hadoop practicals, refer to the `hadoop/` folder for setup instructions.

---

## 👩‍💻 Author

**Sayali** — (https://github.com/sayali51)

---

## 📄 License

This repository is intended for **educational purposes** as part of the DSBDA coursework.
