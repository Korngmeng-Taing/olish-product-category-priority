# 📦 Olist Product Mix Optimization

### Operations Research Project (Group 1)

**Topic:** Linear Programming for E-Commerce Logistics  
**Live Website:** [View Project Report](https://korngmeng-taing.github.io/olish-product-category-priority/)

---

## 📖 Overview

**Olist** is a Brazilian e-commerce marketplace facing logistic constraints. The warehouse has a maximum handling capacity (weight/volume), but demand varies across product categories.

This project uses **Linear Programming (Simplex Method)** to determine the optimal product mix that maximizes **Total Revenue** without exceeding the **Total Capacity Limit**.

### The Core Problem

- **Input:** Historical sales data (100k+ orders).
- **Constraint:** Limited warehouse weight capacity ($K$).
- **Objective:** Maximize Revenue ($Z$).

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **Optimization:** `PuLP` (Linear Programming Solver)
- **Data Processing:** `Pandas`, `NumPy`
- **Visualization:** `Matplotlib`, `Seaborn`
- **Reporting:** `Quarto` (Static Site Generator)

---

## 🚀 How to Run Locally

If you want to run this analysis on your own machine, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/Korngmeng-Taing/olish-product-category-priority.git
cd olish-product-category-priority
```

### 2. Set Up a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On linux,mac
use `venv\Scripts\activate` # On Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Analysis

````bash
 cd olist_quarto
    quarto render

    ```
````
