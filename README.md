
# Vladyslav Hordiienko — Software Development & Data Portfolio

---

## Java & Algorithms

### [Inventory & Order Management System](https://github.com/vladyslav-hordienko/Inventory-Order-Management-System)

A Java system for managing products, inventory, and customer orders through object-oriented classes and collections. Products can be searched, sorted, removed, and saved to files, while orders use immutable objects and defensive copying to protect stored information. The application also includes `Comparable`, `equals()`, and `hashCode()` for sorting and comparing objects.

**Technologies:** Java, OOP, Java Collections, File I/O

### [Recipe Finder API](https://github.com/vladyslav-hordienko/Recipe-Finder-API)

Recipe information is retrieved from TheMealDB API through HTTP requests and processed from JSON responses. The application separates API communication from its main logic and supports local file storage and saved settings between sessions. Error handling covers unsuccessful requests, missing recipes, and unexpected responses.

**Technologies:** Java, REST API, HTTP, JSON, File I/O

### [Sorting Algorithms Benchmark](https://github.com/vladyslav-hordienko/Sorting-Algorithms-Benchmark)

Selection Sort, Quick Sort, and Merge Sort are tested on arrays of different sizes to compare their execution times. The benchmark covers datasets of up to 100,000 elements, showing how performance changes as the number of elements increases. Quick Sort and Merge Sort use recursive algorithms, while Selection Sort provides a comparison with a simpler sorting method.

**Technologies:** Java, Sorting Algorithms, Recursion, Performance Benchmarking

---

## Python & Backend Development

### [SQL Helper](https://github.com/vladyslav-hordienko/SQL_Helper)

A Python web application for practising and checking SQL queries using a sample SQLite sales database. SQLGlot handles query parsing and validation, with only read-only `SELECT` and `WITH` statements permitted to protect the database. The interface includes query previews, validation messages, practice exercises, and support for optional OpenAI API integration.

**Technologies:** Python, SQLite, SQLGlot, HTML, CSS, JavaScript

---

## Python & Data Analytics

### [Sales & Traffic Analysis](https://colab.research.google.com/drive/1hOoHGm3nnuUyAwyKzxi3VSY3nRgIL4F8?usp=sharing)

The analysis covers 61,087 website sessions and approximately $5.77M in revenue, using data collected from multiple Google BigQuery tables. Python, Pandas, and NumPy were used to clean and combine the data, calculate business metrics, and compare performance across products, countries, devices, and traffic channels. Statistical analysis and visualisations were included, with the results presented in an interactive Tableau dashboard.

**Technologies:** Python, SQL, Google BigQuery, Pandas, NumPy, Matplotlib, Seaborn, Tableau

### [International Sales & Business Performance Analysis](https://colab.research.google.com/drive/1JEo_wYX0JLjrXxHQMzrl09BoALasjPvT?usp=sharing)

Three related datasets were combined and analysed in Python, covering 1,330 orders across 45 countries. The data includes approximately $1.70B in revenue, $501.4M in profit, and 6.57M units sold. Pandas and NumPy were used to examine product profitability, regional performance, sales channels, shipping times, and changes in sales over time.

**Technologies:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

---

## SQL & Database Analysis

### [Email & Account Activity Analysis](https://github.com/jhgjvvjk/Email-Account-Activity-Analysis/blob/main/main)

Customer accounts and email activity are analysed together to track engagement across countries and dates. The SQL query combines several CTEs with JOINs, `UNION ALL`, aggregations, and window functions to calculate account and email metrics. Country-level results are ranked using `DENSE_RANK` to identify the top 10 countries by account volume and email activity.

**Technologies:** SQL, Google BigQuery, CTEs, Window Functions, DENSE_RANK
