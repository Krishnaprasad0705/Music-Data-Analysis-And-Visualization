# 🎵 Spotify Music Data Analysis & Visualization

Exploratory Data Analysis • Statistical Analysis • Machine Learning • Power BI

An end-to-end data analysis project exploring Spotify music features, popularity patterns, statistical relationships, and machine learning techniques using Python and Power BI.

## 📌 Project Overview

Music streaming platforms generate valuable data about songs, their audio characteristics, and listener engagement. Understanding these patterns can help uncover relationships between musical attributes and track popularity.

This project explores Spotify track data using Python, statistical analysis, machine learning, and interactive visualizations. It combines data preprocessing, exploratory analysis, dimensionality reduction, predictive modelling, and dashboard development in one workflow.

**Project goal:** Investigate how audio features relate to track popularity and explore whether these features can help predict popularity.

## 🎯 Objectives

- Clean and preprocess music data for analysis.
- Perform Exploratory Data Analysis (EDA) to understand feature distributions and relationships.
- Investigate relationships between audio characteristics and popularity.
- Apply statistical hypothesis testing to explore differences between groups.
- Use Principal Component Analysis (PCA) to study dimensionality reduction.
- Build regression and classification models for predictive analysis.
- Present music insights through visualizations and a Power BI dashboard.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data analysis and model development |
| Pandas & NumPy | Data manipulation and numerical computation |
| Matplotlib & Seaborn | Data visualization |
| SciPy | Statistical analysis and hypothesis testing |
| Scikit-learn | Preprocessing, PCA, regression and classification |
| Jupyter Notebook | Interactive analysis and experimentation |
| Power BI | Dashboard creation and visual reporting |

## 📂 Repository Structure

```text
Music-Data-Analysis-And-Visualization/
│
├── README.md
├── spotify_tracks.csv
├── spotify.ipynb
└── Spo.pbix
```

- `spotify_tracks.csv` — Dataset used for the analysis.
- `spotify.ipynb` — Python notebook containing data analysis and modelling.
- `Spo.pbix` — Power BI dashboard file.
- `README.md` — Project documentation.

## 🔍 Project Workflow

### 1. Data Collection and Understanding

Load the Spotify dataset and examine its structure, columns, data types, and descriptive statistics to understand the available information.

### 2. Data Cleaning and Preprocessing

- Inspect missing values and potential duplicate records.
- Investigate invalid values and extreme outliers.
- Validate audio feature ranges.
- Prepare suitable features for statistical analysis and machine learning.

Data-cleaning decisions should be based on the dataset's meaning rather than automatically removing every unusual observation.

### 3. Exploratory Data Analysis (EDA)

Explore the distribution of popularity and audio features, examine correlations, and visualize relationships between selected variables.

The analysis aims to identify patterns worth investigating rather than assuming that correlations imply causation.

### 4. Statistical Analysis

Apply statistical techniques to investigate relationships and differences in the dataset.

Methods explored include:

- Welch's two-sample t-test.
- One-sample hypothesis testing.
- Analysis of variance (ANOVA) and chi-square testing where appropriate.

The interpretation of each test should consider its assumptions, effect size, uncertainty, and statistical significance.

### 5. Dimensionality Reduction with PCA

Apply feature standardization and Principal Component Analysis to explore the underlying structure of selected audio features.

PCA helps represent correlated features using fewer principal components while quantifying how much variance is retained.

### 6. Machine Learning

Explore regression and classification techniques to investigate whether selected audio features can help explain or classify track popularity.

Models explored in the notebook include:

- Linear Regression.
- Polynomial Regression.
- Logistic Regression.

Model performance should be compared against appropriate baselines using suitable evaluation metrics and a consistent train/test split.

### 7. Power BI Visualization

Use Power BI to present music data through visual reports and dashboards.

The dashboard is intended to make patterns easier to explore and communicate findings in an accessible format.

## 📊 Key Areas of Investigation

This project focuses on the following analytical questions:

1. How are Spotify track popularity scores distributed?
2. How do audio features vary across tracks?
3. What relationships exist between selected audio features and popularity?
4. Do songs in major and minor modes exhibit differences in average popularity?
5. How effectively can dimensionality reduction summarize the selected audio features?
6. How well do regression and classification models perform against baseline approaches?

The answers should be documented using the actual results produced by the notebook.

## 📈 Model Evaluation

Predictive performance is an important part of this project. Models should be assessed on unseen data and compared against simple baselines.

| Task | Recommended evaluation metrics |
|---|---|
| Regression | MAE, RMSE, R² |
| Classification | Accuracy, Precision, Recall, F1-score |
| Model validation | Cross-validation and test-set evaluation |
| Classification diagnostics | Confusion matrix and class distribution |

**Note:** Model performance does not establish that audio features cause popularity. Results may depend on the dataset, target definition, data quality, and features selected.

Actual metrics and model comparisons should be added here after the notebook has been rerun and its results verified.

## 💡 Expected Learning Outcomes

Through this project, I explore and practise:

- Data cleaning and preprocessing with Pandas.
- Exploratory data analysis and visualization.
- Statistical hypothesis testing.
- Feature standardization and dimensionality reduction.
- Regression and classification workflows.
- Model evaluation and interpretation.
- Communicating analytical findings through Power BI.

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or a compatible Python version.
- Jupyter Notebook or JupyterLab.
- Power BI Desktop to open the `.pbix` file.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Krishnaprasad0705/Music-Data-Analysis-And-Visualization.git
```

**2. Navigate to the project directory**

```bash
cd Music-Data-Analysis-And-Visualization
```

**3. Create a virtual environment (recommended)**

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

**4. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

**5. Launch Jupyter Notebook**

```bash
jupyter notebook spotify.ipynb
```

Ensure the CSV file is available at the path expected by the notebook. If necessary, update the dataset path in the loading cell.

### Open the Power BI Dashboard

Open `Spo.pbix` using Power BI Desktop.

## 🔮 Future Improvements

- Improve data validation and document data-cleaning decisions.
- Compare additional regression and classification algorithms.
- Add cross-validation and systematic hyperparameter tuning.
- Investigate feature importance and model explainability.
- Evaluate whether alternative feature sets improve predictive performance.
- Enhance the dashboard with clearer KPIs, filters, and analytical findings.
- Add reproducible experiment settings and dependency versions.
- Document verified results, limitations, and conclusions.

## ⚠️ Limitations

- Relationships observed in the dataset do not necessarily imply causation.
- Track popularity may depend on factors not represented by audio features.
- Results depend on data quality, dataset coverage, and the definition of popularity.
- Predictive models require appropriate baselines and evaluation on unseen data.
- Statistical conclusions depend on the assumptions of the tests used.

## 👨‍💻 Author

**Krishna Prasad M**

B.E. Computer Science and Engineering  
National Engineering College | Class of 2027

Interests: Data Science, Machine Learning, Data Analytics, and Data Engineering.

- GitHub: [Krishnaprasad0705](https://github.com/Krishnaprasad0705)

## ⭐ Support

If you find this project interesting, consider giving the repository a star ⭐ and sharing your feedback.

---

*This project is developed for learning, experimentation, and portfolio development in data analysis and machine learning.*
