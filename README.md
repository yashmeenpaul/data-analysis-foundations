# Data Analysis Foundations

A structured collection of Python notebooks covering the core skills used in data analysis: numerical computing with NumPy, data wrangling with Pandas, and data visualization with Matplotlib, Seaborn, and Plotly. This repository is actively growing and will also include statistics notes, mini-projects, and assignments as they are completed.

## Repository Structure

```
.
├── numpy.ipynb           NumPy fundamentals - arrays and numerical operations
├── pandas.ipynb          Pandas fundamentals - DataFrames, cleaning, filtering
└── visualization.ipynb   Data visualization - Matplotlib, Seaborn, Plotly
```

The notebooks build on each other in sequence:

```
numpy.ipynb -> pandas.ipynb -> visualization.ipynb
```

- `numpy.ipynb` covers the array operations that underlie everything else in the Python data stack.
- `pandas.ipynb` applies those foundations to real, tabular data: loading, cleaning, and filtering.
- `visualization.ipynb` visualizes the cleaned data produced in the Pandas stage.

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

## Datasets

`pandas.ipynb` and `visualization.ipynb` read from `mtcars2.csv` and `cars (1).csv`. These files need to be present in the same directory as the notebooks for the data-loading cells to run.

## What's Next

This repository is a work in progress. Planned additions include:
- Statistics notes and exercises
- Mini-projects applying NumPy, Pandas, and visualization together
- Assignment solutions and practice problems

## License

Open for learning purposes. Feel free to fork and build on it.
