# Matplotlib

# 📊 Matplotlib Practice for Data Visualization

Welcome to my practice repository for learning and mastering **Matplotlib**, Python’s most widely used data visualization library. This repository contains structured, topic-wise examples to help reinforce core visualization concepts.

---

## 🚀 Objective

As a software engineer working towards full-stack and ML development, I’m using this space to:

- Develop a strong understanding of Matplotlib for data visualization.
- Create reusable code snippets and templates for future projects.
- Build a portfolio of visualizations that demonstrate real-world data interpretation.
- Improve plotting skills for both technical presentations and dashboards.

---

## 📂 What's Inside

### 🟢 Basics
- `line_plot.py`: Simple line chart with markers and colors.
- `bar_chart.py`: Vertical and horizontal bar charts.
- `scatter_plot.py`: Relationship visualization between two variables.

### 🟡 Customization
- `plot_styles.py`: Different line and marker styles.
- `labels_legends.py`: Adding titles, labels, and legends.
- `subplots.py`: Multiple plots in a single figure.

### 🔵 Advanced
- `histogram.py`: Frequency distribution visualization.
- `pie_chart.py`: Category-wise distribution.
- `3d_plot.py`: Basic 3D plotting with `Axes3D`.

### 🖼️ Assets
- Saved images of plots for documentation and presentations.

---

## 🧪 Example Plot

```python
import matplotlib.pyplot as plt
import numpy as np

ypoints = np.array([3, 8, 1, 10])
plt.plot(ypoints, 'o:r')  # red dotted line with circle markers
plt.title("Sample Line Plot")
plt.xlabel("X Axis")
plt.ylabel("Y Axis")
plt.grid(True)
plt.show()
