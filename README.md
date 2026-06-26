# Data Analysis Foundations

A structured collection of Python notebooks covering the core skills used in data analysis and data science: numerical computing with NumPy, data wrangling with Pandas, data visualization, and statistics and probability. The repository also includes applied case studies and will continue to grow with mini-projects and assignments.

## Repository Structure

```
.
├── numpy.ipynb                        NumPy fundamentals - arrays and numerical operations
├── pandas.ipynb                       Pandas fundamentals - DataFrames, cleaning, filtering
├── visualization.ipynb                Data visualization - Matplotlib, Seaborn, Plotly
└── Statistics_and_probability.ipynb   Statistics, probability, and an applied Airbnb case study
```

The notebooks build on each other in sequence:

```
numpy.ipynb -> pandas.ipynb -> visualization.ipynb -> Statistics_and_probability.ipynb
```

- `numpy.ipynb` covers the array operations that underlie everything else in the Python data stack.
- `pandas.ipynb` applies those foundations to real, tabular data: loading, cleaning, and filtering.
- `visualization.ipynb` visualizes the cleaned data produced in the Pandas stage.
- `Statistics_and_probability.ipynb` builds the statistical reasoning behind the analysis, then applies it directly to a real dataset in the Airbnb case study.

## Contents

### numpy.ipynb
- Arrays vs. lists, array creation, and dtype rules
- Element-wise arithmetic and aggregations (sum, mean, median, sort)
- Array dimensions, shape, and reshaping
- Identity, zero, and random array generation

### pandas.ipynb
- Series and DataFrame fundamentals
- Indexing and slicing with `loc` and `iloc`
- Loading datasets with `read_csv`
- Handling missing values and duplicates
- Filtering rows on single and multiple conditions

### visualization.ipynb
- Line, bar, pie, and scatter plots
- Histograms, box plots, and violin plots
- Subplots and correlation heatmaps
- Interactive 3D visualization with Plotly

### Statistics_and_probability.ipynb

**Descriptive statistics**
- Measures of central tendency: mean, median, mode (including multimode)
- Population vs. sample, and sampling methods: random, systematic, stratified
- Measures of dispersion: range, variance, standard deviation, percentile, quartiles
- Outlier detection (box plots) and removal using the IQR method
- Correlation: positive, negative, and zero correlation
- Data types: qualitative (nominal, ordinal) and quantitative (discrete, continuous)
- Normal distribution and skewness

**Probability**
- Core concepts: experiment, event, outcome
- Simple and compound events
- Classical probability problems: coins, dice, and card draws
- Marginal, joint, and conditional probability
- Hands-on practice using a country-level dataset

**Airbnb case study**

An applied exploratory data analysis project on a New York City Airbnb listings dataset (48,895 listings, 16 columns), combining the statistics and visualization skills above into a single end-to-end analysis:
- Data cleaning: renaming columns, dropping irrelevant fields, filling missing values
- Outlier detection and removal across numeric columns
- Distribution analysis of listing prices (histogram, skewness)
- Identifying the busiest neighbourhood groups
- Room type distribution (count plot)
- Correlation matrix and heatmap across listing attributes
- Identifying neighbourhoods with the highest review counts (bar plot)

## Datasets

The following CSV files are read directly by the notebooks and need to be present in the same directory for the data-loading cells to run:

| File | Used in |
|---|---|
| `mtcars2.csv` | `pandas.ipynb` |
| `cars (1).csv` | `pandas.ipynb`, `visualization.ipynb` |
| `Country (2) (1).csv` | `Statistics_and_probability.ipynb` |
| `Airbnb_datanew.csv` | `Statistics_and_probability.ipynb` |

## What's Next

This repository is a work in progress. Planned additions include:
- Mini-projects applying statistics, probability, and visualization together
- Assignment solutions and practice problems

## License

Open for learning purposes. Feel free to fork and build on it.
