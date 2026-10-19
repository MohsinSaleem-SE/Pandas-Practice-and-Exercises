# Pandas Practice and Exercises 🐼

## 📌 About This Repository

This repository contains my hands-on practice and exercises using **Pandas**, a powerful Python library for data manipulation and analysis.

I have organized my learning into Jupyter Notebooks, starting with the fundamentals of Series and DataFrames and progressing toward data filtering, missing-value handling, grouping, aggregation, pivot tables, and combining datasets.

The purpose of this repository is to strengthen my practical understanding of Pandas and develop the data manipulation skills required for **Data Analysis, Data Science, and Machine Learning**.

## 📚 Repository Contents

| Notebook | Topics Covered |
|---|---|
| `Pandas Series.ipynb` | Creating Series from lists and dictionaries, custom indexes |
| `DataFrames.ipynb` | Creating and working with DataFrames |
| `operations.ipynb` | Common DataFrame operations, indexing, selection, and filtering |
| `MissingData.ipynb` | Detecting, filling, and dropping missing values |
| `GroupbyAggregation.ipynb` | Grouping data and calculating aggregate statistics |
| `Pivottable.ipynb` | Creating summary tables with `pivot_table` and totals |
| `MergingJoiningConcatination.ipynb` | Combining DataFrames using `merge`, `join`, and `concat` |

## 🧠 Topics and Skills Practiced

### 1. Pandas Series and DataFrames
- Creating Series from lists and dictionaries
- Working with custom indexes
- Creating and exploring DataFrames
- Inspecting data using `.head()` and `.shape`

### 2. Data Selection and Filtering
- Selecting columns and rows
- Using `.loc` and `.iloc` for indexing
- Filtering rows using conditional expressions
- Selecting records based on city, marks, and other conditions

### 3. Missing Data Handling
- Detecting missing values using `.isna()` and `.isnull()`
- Counting missing values
- Filling missing data using `.fillna()`
- Removing missing values using `.dropna()`
- Using NumPy's `np.nan` to represent missing numerical data

### 4. GroupBy and Aggregation
- Grouping records using `.groupby()`
- Calculating average values using `.mean()`
- Calculating totals using `.sum()`
- Counting records using `.count()`
- Aggregating data by categories such as city

### 5. Pivot Tables
- Creating summary tables using `.pivot_table()`
- Organizing data by rows and columns
- Calculating aggregated values
- Using `margins=True` to include totals

### 6. Applying Custom Functions
- Using `.apply()` to perform operations on data
- Applying lambda functions
- Creating a new column based on the length of each student's name

### 7. Combining DataFrames
- Understanding the purpose of `merge()`, `join()`, and `concat()`
- Merging two DataFrames using a common column
- Practicing data combination with related datasets, such as students and teachers

## 📝 Practice Questions

The practice exercises use a student dataset containing names, cities, subjects, and marks.

The questions include:

1. Create a Series with subjects as the index and average marks as values.
2. Display the first three rows of a DataFrame and inspect its shape.
3. Filter students who belong to Lahore.
4. Find students whose marks are greater than 80.
5. Count missing values in the marks column.
6. Fill missing marks with the mean of the column.
7. Calculate average marks for each city.
8. Create a pivot table using city as rows, subject as columns, and mean marks as values, including totals.
9. Add a column containing the length of each student's name using `apply()` and a lambda function.
10. Create a teachers DataFrame and merge it with the student DataFrame using the subject column.

## 💻 Sample Dataset

The following example demonstrates the type of student data used in the exercises:

```python
import pandas as pd
import numpy as np

data = {
    'name': ['Ali', 'Sara', 'Ahmed', 'Hina', 'Bilal', 'Ayesha'],
    'city': [
        'Lahore', 'Karachi', 'Lahore',
        'Islamabad', 'Karachi', 'Lahore'
    ],
    'subject': [
        'Math', 'Math', 'English',
        'English', 'Math', 'Math'
    ],
    'marks': [85, 92, np.nan, 78, 66, 90]
}

df = pd.DataFrame(data)

print(df.head())
print(df.shape)
print(df.isna().sum())
```

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computing and missing-value representation
- **Jupyter Notebook** — Interactive coding and practice
- **VS Code** — Development environment

## ⚙️ Requirements

- Python 3.8 or newer
- Pandas
- NumPy
- Jupyter Notebook

Install the required libraries with:

```bash
pip install pandas numpy jupyter
```

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Open the repository folder:

   ```bash
   cd <repository-folder>
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open any `.ipynb` notebook and execute the cells in order.

You can also open the notebooks directly in VS Code if you have the Python and Jupyter extensions installed.

## 🎯 Learning Objectives

Through this practice, I am working to:

- Build a strong foundation in Pandas Series and DataFrames.
- Improve my ability to select, filter, and transform data.
- Handle missing values correctly.
- Analyze grouped data using aggregation functions.
- Generate meaningful summaries using pivot tables.
- Apply custom functions to DataFrame columns.
- Understand how datasets can be combined using merging, joining, and concatenation.

## 📈 My Data Science Learning Journey

I am a Software Engineering student building practical skills in Python and data analysis as part of my journey toward becoming a **Data Scientist**.

After practicing Python and NumPy, I am developing my Pandas skills to work more confidently with structured datasets, perform exploratory data analysis, and prepare data for future machine learning projects.

This repository documents my learning progress and will continue to grow as I solve more exercises and explore advanced data analysis techniques.

---

**Note:** This is a learning and practice repository. The notebooks document the concepts I have worked on so far, and I am continuously improving my skills through hands-on coding.

