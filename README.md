# Data Analysis with Python

This notebook was originally created as a final project for an introductory data analysis course. It is presented here as an example of descriptive statistics, data visualization, regression, model evaluation, and clustering in Python.

The project began as two separate notebooks, which have been combined into one notebook with marked boundaries between the two originals. The original was also in Croatian, while the notebook here is an AI translation.

## Contents

The first part of the notebook mostly contains basic statistical analysis of a dataset and performs a linear regression at the end. The second part is somewhat more interesting, as along with polynomial regression, it also implements a k-means clustering algorithm. A more detailed list:

- Descriptive analysis of one airline's annual cost data from 1970–1984. Covers means, standard deviations, medians, quartiles, covariance, correlation and regression plots.
- Comparison of linear and quadratic regression models for monthly international airline passenger data. Includes training and test splits, RMSE and R^2 evaluation, cross-validation and visual comparison of the fitted models.
- Exploration of flower measurements using 3D plots and k-means clustering. Uses another descriptive approach, an inertia graph, to decide on the number of clusters, then visualizes cluster centers and compares cluster assignments with the known flower types.

## Files and folders

| File | Description |
| --- | --- |
| [data_analysis_en.ipynb](data_analysis_en.ipynb) | Notebook with English explanations and chart labels. |
| [data_analysis.ipynb](data_analysis.ipynb) | Notebook with the original Croatian text. |

## Tools

Python, Jupyter Notebook, pandas, NumPy, Matplotlib, seaborn, scikit-learn and pydataset.

The notebooks include saved outputs and can be viewed directly on GitHub or opened in Jupyter.

## Running locally

Use Python 3.10 or higher and install the required packages:

```bash
python -m pip install numpy pandas matplotlib seaborn pydataset notebook "scikit-learn==1.5.2"
```

From the repository folder, open the English notebook:

```bash
jupyter notebook data_analysis_en.ipynb
```