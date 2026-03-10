# Seaborn Data Visualization 🎨

A collection of Python data visualization scripts utilizing the **Seaborn** library. Built on top of Matplotlib, Seaborn provides a high-level interface for drawing highly attractive and informative statistical graphics. 

This repository serves as a quick reference for generating diverse plotting styles with minimal code.

## 🚀 Plot Types Included

Each script in this repository stands alone to demonstrate a specific type of Seaborn chart using built-in datasets like `flights`, `tips`, and `iris`:

- **Distribution Plots:**
  - `histogram.py` (Visualizing univariate distributions)
  - `violin.py` (Combining box plots and kernel density estimations)
  - `box.py` (Visualizing summary statistics and outliers)
- **Categorical & Point Plots:**
  - `Scatter.py` (Plotting relationships between variables)
  - `strip.py` (Drawing scatterplots where one variable is categorical)
  - `Swarm.py` (Non-overlapping strip plots for better representation of point density)
  - `bar.py` (Plotting categorical data as rectangular bars)
- **Relational & Matrix Plots:**
  - `Line.py` (Standard line charts over continuous values)
  - `pair.py` (Visualizing pairwise relationships across entire DataFrames simultaneously)
  - `heatmap.py` (Plotting rectangular data as a color-encoded matrix)

## 🛠 Prerequisites

To run these visual scripts, you need Python installed along with the `seaborn` and `matplotlib` libraries.

```bash
pip install seaborn matplotlib
```

## 📝 Running the Scripts

Execute any `.py` file from your terminal to render the Seaborn plot in a new visual window:

```bash
python heatmap.py
```
*(Note: Seaborn will automatically download the necessary built-in datasets like `flights` or `iris` the first time you execute scripts requiring them).*