# 🐍 Python Practice Repository

This repository is a curated collection of Python notebooks and scripts designed to help learners master Python from the ground up — starting with the basics, moving through data analysis and data science concepts, and including function-based exercises and assignments for hands-on practice.

---

## 📘 Contents

### 1️⃣ Basic Python
Foundational concepts and syntax for beginners:
- Variables and Data Types
- Operators (Arithmetic, Logical, Comparison)
- Conditional Statements (`if`, `else`, `elif`)
- Loops (`for`, `while`)
- Input/Output
- String Manipulation
- Lists, Tuples, Sets, Dictionaries

📂 Folder: `basic_python/`

---

### 2️⃣ Python Functions & Assignments
Strengthen your understanding of modular programming and logic building:
- User-defined Functions
- Arguments and Return Values
- Default & Keyword Arguments
- Recursion
- Practice Assignments for:
  - Numbers & Math
  - Strings
  - Lists & Dictionaries
  - Control Flow

📂 Folders: `functions/`, `assignments/`

---

### 3️⃣ Python for Data Analysis
Learn how to use Python libraries for analyzing and visualizing data:
- Working with Pandas (Series, DataFrames)
- Data Cleaning and Manipulation
- GroupBy and Aggregation
- Handling Missing Data
- Merging and Joining Datasets
- Exploratory Data Analysis (EDA)

📦 Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

📂 Folder: `data_analysis/`

---

### 4️⃣ Python for Data Science
Applied data science concepts with hands-on Python coding:
- Importing and Preprocessing Data
- Feature Engineering
- Data Visualization Techniques
- Introduction to Machine Learning using `Scikit-learn`
  - Train-Test Split
  - Building Models
  - Evaluating Accuracy


## 🧠 Sample Code Snippets

```python
# Basic: Check if a number is even
def is_even(n):
    return n % 2 == 0

# Data Analysis: Load and describe data
import pandas as pd
df = pd.read_csv("data.csv")
print(df.describe())

# Data Science: Train a model
from sklearn.linear_model import LogisticRegression
model = LogisticRegression()
model.fit(X_train, y_train)
