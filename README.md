# 🧠 Market-Basket Analysis – Algorithms for Massive Data

This project implements a scalable market-basket analysis solution using the **Amazon Books Reviews** dataset. It was developed as part of the course **Algorithms for Massive Data** in the **Master in Data Science for Economics** at Università degli Studi di Milano.

---

## 📌 Project Overview

- **Goal:** Identify frequently co-reviewed books and generate recommendation rules using association rule mining.
- **Approach:** The classic A-Priori algorithm was used via the [`efficient-apriori`](https://pypi.org/project/efficient-apriori/) package for memory efficiency.
- **Dataset:** Amazon Book Reviews published on Kaggle under the public domain (CC0 license).

---

## 📁 Dataset

**Source:**  
[Kaggle – Amazon Books Reviews](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews)

**Access Method:**  
The dataset is downloaded automatically using the [`kagglehub`](https://pypi.org/project/kagglehub/) package. You do not need to manually download or upload any files.

**Usage in notebook:**
```python
import kagglehub
path = kagglehub.dataset_download("mohamedbakhet/amazon-books-reviews")

