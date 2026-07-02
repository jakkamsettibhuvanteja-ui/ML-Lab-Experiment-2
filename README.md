# ML Lab Experiment 2 - Descriptive Statistics using Python

## Overview

This project demonstrates the implementation of descriptive statistical analysis on two real-world datasets using Python. The experiment focuses on understanding data distribution, measuring central tendency and dispersion, detecting outliers, and visualizing numerical data through statistical plots.

The analysis was performed using the **Titanic** and **Iris** datasets with the help of Python's data analysis libraries.

---

## Objectives

- Load and analyze real-world datasets.
- Perform descriptive statistical analysis.
- Calculate measures of central tendency.
- Calculate measures of dispersion.
- Compute quartiles and Interquartile Range (IQR).
- Detect outliers using the IQR method.
- Visualize data distributions using Histograms and Boxplots.
- Generate cleaned datasets after outlier removal.

---

## Datasets Used

### 1. Titanic Dataset
Used for analyzing passenger age distribution and statistical characteristics.

### 2. Iris Dataset
Used for analyzing petal length measurements and comparing statistical properties with the Titanic dataset.

---

## Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook
- Visual Studio Code

---

## Statistical Measures Implemented

The following descriptive statistics were calculated for both datasets:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- First Quartile (Q1)
- Second Quartile (Median / Q2)
- Third Quartile (Q3)
- Interquartile Range (IQR)

---

## Outlier Detection

Outliers were identified using the Interquartile Range (IQR) method.

Lower Bound:

```
Q1 - (1.5 × IQR)
```

Upper Bound:

```
Q3 + (1.5 × IQR)
```

Data points outside these limits were considered outliers and removed to create cleaned datasets.

---

## Data Visualization

The following visualizations were generated:

- Histogram
- Boxplot

These plots help in understanding:

- Data distribution
- Spread of values
- Median
- Quartiles
- Presence of outliers

---

## Project Structure

```
ML-Lab-Experiment-2
│
├── Datasets
│   ├── titanic.csv
│   └── iris.csv
│
├── Notebook
│   └── Experiment2.ipynb
│
├── Output
│   ├── titanic_statistics.csv
│   ├── iris_statistics.csv
│   └── titanic_cleaned.csv
│
├── .gitignore
└── README.md
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/jakkamsettibhuvanteja-ui/ML-Lab-Experiment-2.git
```

### Navigate to the Project Directory

```bash
cd ML-Lab-Experiment-2
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib scipy jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Notebook/Experiment2.ipynb
```

Run all cells sequentially.

---

## Results

The experiment successfully:

- Loaded and explored two datasets.
- Computed descriptive statistics.
- Detected and removed outliers using the IQR method.
- Generated histograms and boxplots.
- Compared statistical properties between the Titanic and Iris datasets.
- Exported cleaned datasets and statistical summaries.

---

## Learning Outcomes

Through this experiment, the following concepts were learned and implemented:

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Measures of central tendency
- Measures of dispersion
- Quartile and IQR calculations
- Outlier detection techniques
- Data visualization using Matplotlib
- Working with real-world datasets using Pandas

---

## Future Improvements

Possible enhancements include:

- Interactive visualizations using Plotly or Seaborn.
- Automated statistical report generation.
- Comparative dashboards for multiple datasets.
- Additional preprocessing techniques for missing values and feature scaling.

---

## Author

**Bhuvan Teja Jakkamsetti**

Bachelor of Technology (Artificial Intelligence & Machine Learning)

GitHub: https://github.com/jakkamsettibhuvanteja-ui
