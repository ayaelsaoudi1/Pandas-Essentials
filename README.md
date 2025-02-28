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

### **6️⃣ Merging DataFrames in Pandas**  
🔗 Learn how to **combine multiple DataFrames** efficiently using Pandas:  
- **Concatenation** → `pd.concat([df1, df2])` for stacking DataFrames.  
- **Merging** → `pd.merge(df1, df2, on='key')` for relational joins.  
- **Types of Joins** → `inner`, `outer`, `left`, `right`.  
- **Handling duplicate columns** in merges using `suffixes=('_left', '_right')`.  
- **Joining on multiple keys** for complex merges.  

📄 **Notebook:** [`merging_dataframes.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/5-%20Merging%20DataFrames.ipynb)

---

### **7️⃣ Pandas Visualization**  
📊 Explore different ways to visualize data using Pandas' built-in plotting functionalities:  
- **Line plots** → `df.plot(kind='line')` for time-series visualization.  
- **Bar charts** → Vertical & horizontal bar plots, stacked bars.  
- **Scatter plots** → Relationship analysis using `df.plot.scatter()`.  
- **Histograms** → Distribution visualization with `df.plot.hist(bins=20)`.  
- **Boxplots** → Identifying outliers with `df.boxplot()`.  
- **Area charts** → Filled plots using `df.plot.area()`.  
- **Pie charts** → Category distribution using `df.plot.pie(y='column')`.  
- **Customizing plots** → Setting titles, labels, and Matplotlib styles.  

📄 **Notebook:** [`pandas_visualizations.ipynb`](https://github.com/ayaelsaoudi1/Pandas-Essentials/blob/main/6-%20Pandas%20Visualizations.ipynb)

---

## 📚 **Resources & Documentation**  
🔗 Official Pandas Documentation: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)  
