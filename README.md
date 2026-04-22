# 📊 Matplotlib & Seaborn Chart Guide

A complete, single-page visual reference guide for Python data visualization using **Matplotlib** and **Seaborn**.

🌐 **Live Demo:** [View Guide](https://YOUR_USERNAME.github.io/matplotlib-seaborn-guide/)

---

## 📌 What's Inside

### 1. Library Overview
- What is Matplotlib vs Seaborn
- Key strengths of each library
- Standard import setup & installation

### 2. Chart Types (12 Charts)
Every chart includes a visual preview, description, when-to-use info, and copy-paste code for both libraries.

| Chart | Library | Use Case |
|---|---|---|
| Bar Chart | MPL + SNS | Compare categories |
| Line Chart | MPL + SNS | Trends over time |
| Scatter Plot | MPL + SNS | Correlation between two numbers |
| Histogram | MPL + SNS | Distribution of one variable |
| Box Plot | MPL + SNS | Spread & outliers across groups |
| Violin Plot | MPL + SNS | Distribution shape per group |
| Heatmap | SNS | Correlation matrix / 2D grid |
| Pie / Donut | MPL | Part-to-whole proportions |
| Pair Plot | SNS | All numeric columns at once |
| KDE Plot | SNS | Smooth distribution estimate |
| Regression Plot | SNS | Linear relationship with CI |
| Stacked Bar | MPL + SNS | Composition per category |

---

### 3. Data Type Combination Matrix
Choose the right chart based on your X and Y axis data types:

| X Axis | Y Axis | Best Charts |
|---|---|---|
| Categorical | Numerical | Bar, Box Plot, Violin |
| Categorical | Categorical | Stacked Bar, Grouped Bar, Pie |
| Numerical | Numerical | Scatter, Regression, 2D KDE |
| Time | Numerical | Line Chart, Area Chart |
| — | Single Numerical | Histogram, KDE, Box Plot |
| — | Many Numerical | Pair Plot, Correlation Heatmap |

---

### 4. Matplotlib vs Seaborn Comparison
Side-by-side feature comparison across 13 dimensions including:
- Code verbosity
- DataFrame support
- Statistical built-ins
- 3D & animation support
- Customization level

### 5. Decision Guide
When to use Matplotlib, when to use Seaborn, and how to combine both.

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install matplotlib seaborn pandas numpy
```

### Standard Imports
```python
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd
import numpy as np

sns.set_theme(style="darkgrid")
```

---

## 📁 Project Structure

```
matplotlib-seaborn-guide/
│
├── matplotlib_seaborn_guide.html   # Main guide (open in browser)
└── README.md                       # This file
```

---

## 🛠️ How to Use

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/matplotlib-seaborn-guide.git
```

2. Open the file in your browser:
```bash
cd matplotlib-seaborn-guide
open matplotlib_seaborn_guide.html
```

---

## 💡 Key Insight

> Seaborn and Matplotlib are not competitors — they work best **together**.
> Build your chart in Seaborn, polish it with Matplotlib.

```python
sns.heatmap(df.corr(), annot=True)        # Seaborn for the chart
plt.title("Correlation Matrix", size=16)  # Matplotlib to customize
plt.tight_layout()
plt.savefig("chart.png", dpi=300)         # Matplotlib to export
```

---

## 📚 Topics Covered

`Python` `Matplotlib` `Seaborn` `Data Visualization` `EDA` `Data Science` `Data Analytics` `Bar Chart` `Scatter Plot` `Heatmap` `Histogram` `Box Plot`

---

## 👤 Author

**Vasanth**
B.E. Electronics & Communication Engineering
Transitioning into Data Science & Data Analytics

---

## ⭐ Support

If this guide helped you, please give it a **star ⭐** on GitHub!
It helps others find this resource.
