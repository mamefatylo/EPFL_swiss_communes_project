# Swiss Communes — Exploratory Data Analysis

## Overview
Exploratory data analysis of Swiss communes using demographic, geographic, and land use data. The notebook covers data exploration, visualization, probability, and matrix encoding as part of the EPFL Extension School Applied Data Science: Machine Learning program.

## Dataset
`p1_communes.csv` — 2,202 Swiss communes × 17 variables, including population, age groups, language region, canton, elevation, coordinates, and land use proportions.

## Structure
- **A. Data Overview** — loading, column classification, missing values, and logical constraints
- **B. Exploration** — summary statistics, population rankings, cantonal density, elevation ranges
- **C. Visualizations** — bar charts, histograms, box/boxen plots, pairplots, and geographic scatter maps
- **D. Probabilities** — conditional probability of canton membership given elevation threshold
- **E. Matrices** — one-hot encoding of canton membership as a binary matrix

## Technologies
- Python 3
- Pandas
- Matplotlib
- Seaborn
- NumPy

## How to Run
1. Clone the repository
2. Install dependencies: `pip install pandas matplotlib seaborn numpy`
3. Open `communes_solution.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells sequentially
