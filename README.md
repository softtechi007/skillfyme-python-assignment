# 📓 Python Practical Assignments - Complete Notebook

## 📌 Overview

This notebook contains **10 real-world Python assignments** covering fundamental to intermediate programming concepts including:

- **Conditional logic & loops** (Grading System, Parking Management)
- **Data structures** (Library Management, Conference Room Booking)
- **NumPy** (Climate analytics & temperature pattern analysis)
- **Pandas** (Data cleaning, filtering, aggregation, and analysis)

All assignments focus on **practical workflows** and **collaboration-ready code** with proper documentation and output formatting.

---

## 📚 Assignments Summary

### Assignment #1: Real-World Logic Systems

| Problem | Description | Key Concepts |
|---------|-------------|---------------|
| **Problem 1** | Student Grading System – Takes marks for 3 subjects, calculates average, and assigns grades (A, B, C, D) based on predefined ranges | Input validation, conditional statements (if-elif-else), formatted output (f-strings) |
| **Problem 2** | Parking Management System – Dynamic rate calculator with hourly rates (₹20/₹15/₹10), 6 AM–12 AM operation hours, 50% discount every 5th vehicle | While loops, time validation, discount logic, continuous data entry, exit condition |

### Assignment #2: Smart Systems in Python (Library & Booking)

| Problem | Description | Key Concepts |
|---------|-------------|---------------|
| **Problem 1** | Library Management System – Manage book collection with search (by title), add new books, display all books, filter books published after a given year using list comprehension | Lists, dictionaries, list comprehension, loops, user interaction |
| **Problem 2** | Conference Room Booking System – Store bookings in dictionary (room → list of tuples), check for overlapping time slots before adding, display full schedule | Dictionaries, tuples, nested data structures, conflict detection (time overlap logic) |

### Assignment #3: Climate Analytics with NumPy

| Problem | Description | Key Concepts |
|---------|-------------|---------------|
| **Problem 1** | Weekly Temperature Analysis – Generate 7-day temperature data (3×7 array), calculate per-city averages, weekly max, element-wise difference between city 1 & 2, reshape to day-wise view | NumPy random generation, axis-based aggregation, element-wise operations, reshape() |
| **Problem 2** | Yearlong Climate Trends – Generate 3×365 temperature array (-5°C to 45°C), detect heatwave days (>40°C), find hottest day (value + city + day), identify most stable city (lowest std dev), convert to Fahrenheit, display top 5 hottest days | 2D NumPy arrays, boolean indexing, argmax, standard deviation, broadcasting, sorting/slicing |

### Assignment #4: Data Cleaning & Analysis with Pandas

| Problem | Description | Key Concepts |
|---------|-------------|---------------|
| **Problem 1** | Customer Orders Analysis – Load CSV, display .info() & .describe(), drop missing OrderAmount rows, filter by region (e.g., 'North'), sort by OrderAmount descending, calculate average order value per region using groupby | Pandas I/O, data inspection, dropna(), boolean filtering, sort_values(), groupby().mean() |
| **Problem 2** | Flight Delay Analysis – Drop missing DelayInMinutes, filter delays >30 minutes, group by Airline (count + mean delay), identify destination with highest cumulative delay per airline, create Severity column (Low/Medium/High) based on delay minutes | Pandas data cleaning, groupby aggregation, idxmax(), .apply() with custom function, feature engineering |

---

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| **Python 3.x** | Core programming language |
| **NumPy** | Numerical operations, array manipulation, random data generation |
| **Pandas** | Data loading, cleaning, filtering, grouping, and aggregation |
| **Matplotlib** | (Optional/Implied) For visualization tasks |
| **Scikit-learn** | (Reference) For regression tasks mentioned in curriculum |

---

## 📂 Dataset Files Used (Generated)

| File Name | Assignment | Description |
|-----------|------------|-------------|
| `customer_orders.csv` | Assignment #4 (P1) | Customer order data (CustomerID, OrderAmount, OrderDate, Region) |
| `flight_delays.csv` | Assignment #4 (P2) | Flight delay data (FlightID, Airline, Destination, DepartureTime, DelayInMinutes) |
| `temperatures.npy` (simulated) | Assignment #3 | NumPy arrays for climate simulations |

> 💡 **Note:** All datasets are either generated within the notebook using NumPy/Pandas or created from hardcoded data strings to ensure reproducibility.

---


---

## 🎯 Learning Outcomes

After completing this notebook, you will be able to:

- ✅ Write conditional logic and loops for real-world business rules
- ✅ Work with Python data structures (lists, tuples, dictionaries) for storage & retrieval
- ✅ Detect overlapping time slots and manage bookings
- ✅ Generate and manipulate multi-dimensional NumPy arrays
- ✅ Perform element-wise operations, aggregations, and broadcasting
- ✅ Clean, filter, group, and transform data using Pandas
- ✅ Apply custom functions to create new features (e.g., Severity column)
- ✅ Generate summary statistics and identify key insights (hottest day, stable climate, top destinations)

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)

1. Go to [Google Colab](https://colab.research.google.com/)
2. Click **File → Upload Notebook**
3. Upload the `.ipynb` file
4. Run cells in order ( **Runtime → Run all** )
