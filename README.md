# Data Analysis Foundations
 
A structured collection of Python notebooks covering the core skills used in data analysis and data science: numerical computing, data wrangling, visualization, statistics, probability, inferential statistics, and linear algebra. The repository also includes applied case studies and will continue to grow with mini-projects and assignments.
 
## Repository Structure
 
```
.
├── numpy.ipynb                        NumPy fundamentals - arrays and numerical operations
├── pandas.ipynb                       Pandas fundamentals - DataFrames, cleaning, filtering
├── visualization.ipynb                Data visualization - Matplotlib, Seaborn, Plotly
├── Statistics_and_probability.ipynb   Descriptive stats, probability, and Airbnb case study
├── inferential_stats.ipynb            Hypothesis testing, confidence intervals, statistical tests
└── Linear_Algebra.ipynb               Matrix operations, properties, and hands-on exercises
```
 
The notebooks build on each other in sequence:
 
```
numpy.ipynb -> pandas.ipynb -> visualization.ipynb -> Statistics_and_probability.ipynb -> inferential_stats.ipynb -> Linear_Algebra.ipynb
```
 
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
- Measures of central tendency: mean, median, mode
- Population vs. sample and sampling methods: random, systematic, stratified
- Measures of dispersion: range, variance, standard deviation, percentiles, quartiles
- Outlier detection and removal using the IQR method
- Correlation: positive, negative, and zero
- Data types: qualitative (nominal, ordinal) and quantitative (discrete, continuous)
- Normal distribution and skewness
- Marginal, joint, and conditional probability
- Classical probability problems: coins, dice, card draws
- **Airbnb case study**: end-to-end EDA on a New York City listings dataset (48,895 rows): data cleaning, outlier removal, price distribution analysis, neighbourhood and room type breakdowns, correlation heatmap
### inferential_stats.ipynb
- Population vs. sample, point estimates, and margin of error
- Confidence intervals: construction, interpretation, and common mistakes
- Normal distribution, Z-scores, and Z-table values (90%, 95%, 99%)
- Central Limit Theorem and why sample size matters (n > 30)
- Sampling methods: random and stratified (with real-world context)
- **Hypothesis testing framework**: null hypothesis, significance level, p-value
- One sample Z-test (population std dev known) — pharmaceutical machine example
- One sample T-test (population std dev unknown)
- Two sample T-test: normality check (Shapiro), variance check (Levene), `equal_var` decisions — salary comparison and battery supplier examples
- ANOVA: comparing more than two groups, with Kruskal test as the non-parametric fallback — customer satisfaction ratings example
- Chi-square test: testing relationships between categorical variables — advertising medium vs. purchase behavior
### Linear_Algebra.ipynb
- Matrix creation and scalar operations
- Matrix addition, subtraction, multiplication (Hadamard product and dot product)
- Matrix transpose and transpose properties: (A')' = A, (A+B)' = A'+B', (AB)' = B'A'
- Matrix rank: identifying redundant or duplicate data
- Determinant: checking if a matrix is singular
- Matrix inverse
- Applied exercises using the cars dataset (real DataFrame as a matrix context)
- Hands-on problems: odd/even element extraction, row-wise mean, loop-based max without built-ins, pattern printing, character frequency dictionary
## Datasets
 
| File | Used in |
|---|---|
| `mtcars2.csv` | `pandas.ipynb` |
| `cars (1).csv` | `pandas.ipynb`, `visualization.ipynb`, `Linear_Algebra.ipynb` |
| `Country (2) (1).csv` | `Statistics_and_probability.ipynb` |
| `Airbnb_datanew.csv` | `Statistics_and_probability.ipynb` |
 
All files need to be in the same directory as the notebooks for the data-loading cells to run.
 
## What's Next
 
This repository is a work in progress. Planned additions include:
- Mini-projects applying these skills end-to-end
- Assignment solutions and practice problems
## License
 
Open for learning purposes. Feel free to fork and build on it.
 
