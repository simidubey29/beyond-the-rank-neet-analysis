# Beyond The Rank: NEET Result Analysis & Competition Insights

## Overview

NEET (National Eligibility cum Entrance Test) is one of the most competitive entrance examinations in India, with lakhs of students competing every year for limited medical seats.

This project performs an in-depth Exploratory Data Analysis (EDA) on NEET result data to uncover performance trends, regional disparities, participation patterns, and examination center insights across India using Python and data visualization techniques.

The analysis helps understand how student performance varies across states, cities, and examination centers while highlighting competition intensity and score distribution patterns.

---

## Problem Statement

NEET is one of the largest medical entrance examinations in India. With increasing competition, regional performance differences, and concerns regarding unusual score patterns, understanding the distribution and trends of examination results has become increasingly important.

This project aims to analyze NEET result data to answer key questions such as:

- How are marks distributed among students?
- Which states and cities perform better on average?
- Which examination centers show the highest average scores?
- How does student participation vary across regions?
- Are there noticeable score concentration patterns across specific centers?

The objective is to generate meaningful insights about competition trends and student performance using data-driven analysis.

---

## Dataset Information

### Dataset Used
**NEET_result.csv**

### Features

| Column Name | Description |
|------------|-------------|
| marks | Student NEET score |
| state | Student state |
| city | Examination city |
| center_name | Examination center name |
| center_number | Center identification number |
| dummy_srlno | Student serial number |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Exploratory Data Analysis Performed

### 1. Dataset Exploration
- Dataset shape
- Data types
- Statistical summary
- Missing value analysis
- Duplicate value detection

### 2. Marks Distribution Analysis
- Score distribution
- Competition intensity
- Performance concentration

### 3. State-wise Performance Analysis
- Average marks by state
- Top performing states
- Lowest performing states

### 4. City-wise Performance Analysis
- Top performing cities
- Regional performance comparison

### 5. Student Participation Analysis
- States with highest participation
- Distribution of candidates across regions

### 6. Center-wise Performance Analysis
- Top performing examination centers
- Average marks by center

### 7. Center Participation Analysis
- Centers with highest student count
- Examination center distribution

### 8. Outlier Detection
- Boxplot analysis
- Score spread visualization

### 9. Correlation Analysis
- Heatmap visualization
- Relationship between numeric variables

---

## Visualizations Included

The project generates the following charts:

- Marks Distribution Histogram
- Top Performing States
- Lowest Performing States
- City-wise Performance Analysis
- Student Participation Analysis
- Top Performing Centers
- Center Participation Distribution
- Marks Boxplot
- State-wise Marks Distribution
- Correlation Heatmap

---

## Key Insights

- NEET scores show strong competition with a large concentration of students in mid-score ranges.
- Certain states consistently demonstrate higher average performance.
- Significant regional differences exist in average student scores.
- Student participation varies considerably across states.
- Some examination centers show notably higher average scores than others.
- Score distribution contains outliers representing exceptionally high-performing students.
- Numeric identifier fields have little direct relationship with student marks.

---

## Project Structure

```text
beyond-the-rank-neet-analysis/
│
├── notebooks/
│   └── beyond_the_rank_neet_eda.ipynb
│
├── visuals/
│   ├── marks_distribution.png
│   ├── state_analysis.png
│   ├── lowest_state_analysis.png
│   ├── city_analysis.png
│   ├── student_participation.png
│   ├── center_analysis.png
│   ├── top_centers.png
│   ├── boxplot.png
│   ├── statewise_boxplot.png
│   └── heatmap.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/simidubey29/beyond-the-rank-neet-analysis.git
```

Navigate to the project directory:

```bash
cd beyond-the-rank-neet-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## Future Enhancements

- Interactive Streamlit Dashboard
- State-wise Geographic Visualization
- Advanced Statistical Analysis
- Performance Trend Forecasting
- Machine Learning Based Score Prediction
- Automated Insight Generation

---
## Dataset

The original dataset is not included in this repository due to GitHub file size limitations.

Place the following file inside the `data/` folder before running the notebook:

- NEET_result.csv
- 
## Author

**Simi Dubey**

Aspiring Data Scientist passionate about transforming raw data into meaningful insights through analytics, visualization, and machine learning.

---

## License

This project is licensed under the MIT License.
