# **Pandas Essentials** 🐼  

This repository contains Jupyter Notebooks covering essential **Pandas** functionalities, from fundamental concepts to advanced data manipulation techniques.  

---

## 📌 **Notebooks Overview**  

### **1️⃣ Pandas Fundamentals**  
🔹 Introduction to Pandas core objects:  
- **Series** → One-dimensional labeled array.  
- **DataFrame** → Two-dimensional labeled table.  
- **Methods & Attributes** → Used for performing data operations.  
- **Indexing** → `.iloc[]` (integer-based) vs `.loc[]` (label-based).  

📄 **Notebook:** [`pandas_fundamentals.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/pandas%20fundamentals.ipynb)

---

### **2️⃣ Reading Files in Pandas**  
📂 Learn how to load data into Pandas using different file formats:  
- **CSV** → `pd.read_csv()`  
- **TXT** → `pd.read_csv()` with separators  
- **JSON** → `pd.read_json()`  
- **Excel** → `pd.read_excel()`  

📄 **Notebook:** [`reading_files.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/1-%20Reading%20Files%20in%20Pandas.ipynb)

---

### **3️⃣ Filtering & Ordering Data**  
🔍 How to **filter and sort** data using Pandas:  
- **Basic filtering** → Conditions on DataFrame columns.  
- **String filtering** → `.str.contains()` method.  
- **Sorting** → Single & multiple column sorting (`ascending`, `descending`).  

📄 **Notebook:** [`filtering_ordering.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/2-%20Filtering%20and%20Ordering%20in%20Pandas.ipynb)

---

### **4️⃣ Indexing in Pandas**  
📑 Learn how to efficiently manage **DataFrame indexing**:  
- Setting & resetting the **index** (`.set_index()`, `.reset_index()`).  
- Multi-indexing with **multiple levels** (`['Continent', 'Country']`).  
- Using `.loc[]` and `.iloc[]` for **row selection**.  
- Sorting index with `.sort_index()`.  

📄 **Notebook:** [`indexing_pandas.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/3-%20Indexing%20in%20Pandas.ipynb)

---

### **5️⃣ Grouping & Aggregation**  
📊 How to summarize data using `groupby()` and aggregation functions:  
- **Grouping data** → `df.groupby('column')`  
- **Aggregation functions** → `mean()`, `sum()`, `count()`, `min()`, `max()`  
- **Custom aggregations** → Using `.agg({column: [func1, func2]})`.  
- **Multi-column grouping** → Grouping by **two or more columns**.  
- **Descriptive statistics** → `.describe()` for grouped data.  

📄 **Notebook:** [`groupby_aggregating.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/4-%20Group%20by%20and%20Aggregating.ipynb)

---

## 📚 **Resources & Documentation**  
🔗 Official Pandas Documentation: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)  



