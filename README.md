🔬 PandemicLens — COVID-19 Exploratory Data Analysis

*Turning COVID-19 data into meaningful insights.

PandemicLens is a data analytics project that explores global and Indian COVID-19 trends using Python. It applies Exploratory Data Analysis (EDA) techniques to identify patterns in reported cases, deaths, and changes over time through statistical summaries and visualizations.
 *Project Objectives
- Analyze COVID-19 trends across different countries.
- Explore India's daily reported cases and seven-day rolling averages.
- Visualize relationships between reported cases and deaths.
- Identify patterns using statistical analysis and data visualization.
- Understand missing values, data quality, and dataset limitations.

 🛠️ Technologies Used
- **Python** — Core programming language
- **Pandas** — Data cleaning and manipulation
- **NumPy** — Numerical calculations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical charts and heatmaps
- **Jupyter Notebook / Google Colab** — Interactive analysis

 📊 Key Features
- Dataset inspection and missing-value analysis
- Statistical summaries of COVID-19 data
- Time-series visualization of reported cases in India
- Country-level comparison of reported cases
- Correlation analysis and heatmaps
- Seven-day rolling-average analysis

 📂 Project Structure
```text
pandemic-lens-eda/
├── data/
│   └── README.md
├── notebooks/
│   └── covid19_global_india_eda.ipynb
├── reports/
│   └── figures/
├── README.md
├── requirements.txt
└── .gitignore
```

 🌐 Dataset
**Source:** Our World in Data (OWID)

Dataset: https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv

Documentation: https://docs.owid.io/projects/etl/api/covid/

The notebook loads the dataset directly from its online source.

 📌 Project Outcome
PandemicLens demonstrates how Python-based EDA can be used to explore public-health data, uncover trends, and communicate findings through clear visualizations.
