# Bilinear-Complexity-of-Matrix-Multiplication-
# 🔢 Research on the Bilinear Complexity of 3×3 Matrix Multiplication over GF(2)

This repository contains the code and computational experiments for my bachelor's thesis:  
**“Research on the Bilinear Complexity of Multiplying 3×3 Matrices over the Field of Two Elements.”**

---

## 🎯 Project Overview

Matrix multiplication is one of the most fundamental operations in mathematics and computer science.  
This project explores the **bilinear complexity** of multiplying 3×3 matrices over the binary field **GF(2)** —  
a case that, to the best of my knowledge, has not been systematically studied before.

The main goal was to analyze how **cyclic symmetry assumptions** can reduce the number of required scalar multiplications in **Brent’s bilinear system** and simplify the search for valid algorithms.

---

## 🧩 Methodology

The project combines theoretical analysis and computational experiments.  
- Equations describing 3×3 matrix multiplication were generated and reduced using **cyclic symmetry**.  
- A search algorithm was implemented in **Python (SageMath)** to find valid coefficient sets.  
- Experiments were performed using symbolic computation and algebraic constraints.

The workflow is organized into Jupyter notebooks:

| Notebook | Description |
|-----------|-------------|
| `notebooks/pipeline_2.ipynb` | Main search pipeline for generating and solving Brent systems |
| `notebooks/4th_element.ipynb` | Experiments with alternative coefficient structures and partial solutions |

---

## ⚙️ Requirements

To reproduce the results, install:
```bash
pip install numpy sympy
