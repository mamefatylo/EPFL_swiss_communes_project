# Swiss Communes — Exploratory Data Analysis

## Overview
Exploratory data analysis of 2,202 Swiss communes using demographic, geographic, and land use data, completed as part of the EPFL Extension School Applied Data Science: Machine Learning course.

The analysis establishes structural and data integrity checks before conducting numerical and visual exploration. Key findings include: Zürich as the most populated commune with a population more than double that of second-ranked Genève; Basel-Stadt as the densest canton driven by its exceptionally small land area; and Graubünden as the least dense despite a larger population than Basel-Stadt, owing to its vast territory. Settlement allocation does not follow population ranking; Lugano, despite ranking 9th in population, records the lowest Settlement proportion among the top 10 communes, with land dominated by Wooded and Unproductive areas.

Demographic analysis across language regions reveals that `fr` communes tend younger, with the highest median 0–19 proportion (~23%) and the lowest 65+ proportion, while `rm` and `it` communes tend older, with the lowest youth proportions and highest elderly proportions. The `20–64` working-age group dominates consistently across all regions (58–63%), meaning regional demographic differences are primarily expressed through the 0–19 vs 65+ split. Elevation emerges as a strong geographic differentiator: half of all communes above 2000m belong to Valais, consistent with it recording the largest elevation range of all cantons. High-altitude communes are characterised by low agricultural, low settlement, low wooded, and high unproductive land, consistent with rocky alpine terrain. Geographic scatter maps of commune coordinates successfully reproduce Switzerland's three main regions, the Jura, the Central Plateau, and the Swiss Alps, through elevation as a colour variable. The language map reveals a sharp boundary between `de` and `fr` regions, the complete geographic isolation of `it` behind the Alpine barrier, and `rm` as a small enclave between `de` and `it` in the Alps.

## Notebook Contents
- **A. Data Overview:** loading, column classification, missing values, and logical constraints
- **B. Exploration:** summary statistics, population rankings, cantonal density, elevation ranges
- **C. Visualisations:** bar charts, histograms, box/boxen plots, pairplots, and geographic scatter maps
- **D. Probabilities:** conditional probability of canton membership given elevation threshold
- **E. Matrices:** binary encoding of canton membership as a preprocessing step for Machine Learning

## Dataset
`p1_communes.csv` — 2,202 Swiss communes × 17 variables, including population, age groups, language region, canton, elevation, coordinates, and land use proportions.

## Requirements
- Python 3
- Pandas
- Matplotlib
- Seaborn
- NumPy

## Usage
1. Clone the repository
2. Install dependencies: `pip install pandas matplotlib seaborn numpy`
3. Open `communes_solution.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells sequentially
