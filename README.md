#  DA5401 Assignment 5  
### *Visualizing Data Veracity Challenges in Multi-Label Classification*

---

## Course Information
**Course Code:** DA5401  
**Assignment No.:** 5  
**Title:** Visualizing Data Veracity Challenges in Multi-Label Classification  
**Name:** Ranjith.V.R 
**Roll no:** EE24S034  
**Date:** 05/Oct/2025 
---

## Objective

This assignment aims to:

- Understand **data veracity issues** (noisy labels, outliers, and hard-to-learn samples) in real-world datasets.  
- Apply **non-linear dimensionality reduction** techniques — **t-SNE** and **Isomap** — to explore hidden structure and complexity in the **Yeast multi-label classification dataset**.  
- Visually interpret the results to explain challenges in biological data modeling.

---

## Dataset

- **Name:** Yeast Dataset  
- **Source:** [MULAN Repository](http://mulan.sourceforge.net/datasets-mlc.html)  
- **File Used:** `yeast.arff`  
- **Description:**  
  Each instance represents a gene experiment with **103 gene expression features** and **14 binary functional labels** representing biological functions.  
  A gene may belong to multiple functions, making this a **multi-label classification problem**.

---

## How to Run the Notebook

## How to run
1. Place `yeast.arff` in the same folder as the notebook.
2. Open `DA5401 Assignment #5.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells in order. Plots and evaluation results will be displayed inline.

---

## Assignment Tasks Overview

### Part A – Preprocessing and Setup
1. Load `yeast.arff` dataset.  
2. Separate features (X) and labels (Y).  
3. Identify the two most frequent single-label classes and one multi-label combination for visualization.  
4. Standardize features to ensure fair distance computation.

### Part B – t-SNE Visualization and Veracity Analysis
1. Apply **t-SNE** with different perplexities (5, 30, 50).  
2. Visualize clusters with class coloring.  
3. Identify:
   - **Noisy/Ambiguous Labels:** Misclassified or overlapping points.  
   - **Outliers:** Isolated data points.  
   - **Hard-to-Learn Samples:** Mixed regions indicating functional overlaps.

### Part C – Isomap and Manifold Comparison
1. Apply **Isomap** for 2D projection.  
2. Compare **global vs local** structure preservation between t-SNE and Isomap.  
3. Discuss manifold curvature and its relationship to classification difficulty.




