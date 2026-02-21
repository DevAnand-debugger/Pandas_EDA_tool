# Pandas_EDA_tool
Learning Pandas Library in EDA

Learning Exploratory Data Analysis (EDA) using the Pandas Library

---

## 👤 Student Details

**Name:** Dev Anand  
**PRN:** 25070123039  
**Batch:** A2  
**Experiment:** 9  
**Title:** Study of Pandas Library  

---

# 1️⃣ AIM

To study the Pandas library and understand its importance in data manipulation, data analysis, and Exploratory Data Analysis (EDA).

---

# 2️⃣ OBJECTIVES

- To understand the importance of Pandas in Python.
- To learn about Series and DataFrame structures.
- To perform data inspection and structural analysis.
- To access and modify rows and columns.
- To perform basic statistical operations.
- To apply filtering conditions on datasets.

---

# 3️⃣ INTRODUCTION TO PANDAS

Pandas is a powerful Python library used for data manipulation and data analysis.

It provides flexible and efficient data structures designed to handle structured data easily.

The two main data structures in Pandas are:

- **Series** (1D labeled array)
- **DataFrame** (2D labeled table)

Pandas is widely used in:

- Data Science
- Machine Learning
- Financial Analysis
- Research and Statistics
- Business Intelligence

It is built on top of the NumPy library.

---

# 4️⃣ WHY PANDAS?

Pandas is used because:

- It handles structured data efficiently.
- It supports labeled rows and columns.
- It allows easy data filtering and transformation.
- It provides built-in statistical functions.
- It simplifies data cleaning and preprocessing.

In Exploratory Data Analysis (EDA), Pandas helps in:

- Data inspection
- Handling missing values
- Data filtering
- Statistical summaries
- Data transformation

---

# 5️⃣ PANDAS SERIES

A **Series** is a one-dimensional labeled array capable of holding any data type.

Example:

```python
s = pd.Series([10, 20, 30, 40])
```

Features of Series:

- Indexed data
- Homogeneous or mixed data
- Supports vectorized operations

---

# 6️⃣ PANDAS DATAFRAME

A **DataFrame** is a two-dimensional labeled data structure with rows and columns.

It is similar to a table or spreadsheet.

Example:

```python
data = {
    "Name": ["A", "B", "C"],
    "Marks": [85, 90, 78]
}

df = pd.DataFrame(data)
```

DataFrames allow:

- Column access
- Row access
- Data modification
- Statistical analysis

---

# 7️⃣ DATA INSPECTION FUNCTIONS

Pandas provides built-in functions to understand the structure of a DataFrame:

- `df.head()` → Displays first 5 rows
- `df.tail()` → Displays last 5 rows
- `df.shape` → Returns (rows, columns)
- `df.ndim` → Returns number of dimensions
- `df.size` → Returns total number of elements
- `df.columns` → Returns column names
- `df.dtypes` → Returns data types of each column

These functions are essential for EDA.

---

# 8️⃣ ACCESSING DATA

## Access Individual Column

```python
df["Name"]
df["Marks"]
```

## Access Specific Row

```python
df.loc[1]
```

`.loc[]` is used for label-based indexing.

---

# 9️⃣ DATA MODIFICATION

## Add a New Column

```python
df["Grade"] = ["First Class", "Distinction", "Second Class"]
```

## Update Specific Value

```python
df.loc[0, "Marks"] = 88
```

## Delete a Column

```python
df.drop("Grade", axis=1, inplace=True)
```

These operations are useful in real-world data cleaning.

---

# 🔟 STATISTICAL OPERATIONS

Pandas provides built-in statistical functions:

- `mean()`
- `median()`
- `mode()`
- `min()`
- `max()`

Example:

```python
df["Marks"].mean()
df["Marks"].median()
df["Marks"].mode()
```

These functions are essential for:

- Data summaries
- Report generation
- EDA insights

---

# 1️⃣1️⃣ DATA FILTERING

Pandas allows conditional filtering.

Example:

```python
df[df["Marks"] > 80]
```

This displays students who scored more than 80.

Filtering is important in:

- Data analysis
- Business decision making
- Performance evaluation

---

# 1️⃣2️⃣ PANDAS IN EDA

In Exploratory Data Analysis, Pandas is used for:

- Cleaning data
- Handling missing values
- Feature engineering
- Statistical analysis
- Data visualization preparation

Pandas works together with:

- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 1️⃣3️⃣ ADVANTAGES OF PANDAS

- Easy data handling
- Supports labeled data
- Powerful filtering system
- Built-in statistical functions
- Efficient handling of large datasets

---

# 1️⃣4️⃣ LIMITATIONS OF PANDAS

- Uses more memory compared to NumPy arrays
- Can be slower for heavy numerical computation
- Not ideal for extremely large datasets without optimization

---

# 1️⃣5️⃣ REAL-WORLD APPLICATIONS

Pandas is widely used in:

- Data Science
- Machine Learning
- Finance
- Marketing Analytics
- Business Reporting
- Academic Research

---

# 1️⃣6️⃣ CONCLUSION

In this experiment, we studied the Pandas library and its importance in data analysis.

We learned about:

- Series and DataFrame
- Data inspection methods
- Data access and modification
- Statistical operations
- Conditional filtering

Pandas is an essential tool for Exploratory Data Analysis and forms a major part of modern data science workflows.

---

## 🧰 Development Setup

- **Language:** Python  
- **Execution Environment:** Google Colab  
- **Mode:** Online execution  

---

## ▶ Usage Instructions

1. Open the Python file or notebook from this repository  
2. Run the program in Google Colab  
3. Execute the cells step by step  
4. Observe outputs and analyze results  
5. Modify data to explore further  

---

## 📌 Author

**Dev Anand**  
B.Tech – Electronics & Telecommunication Engineering  
Symbiosis Institute of Technology, Pune  
