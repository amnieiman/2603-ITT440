# 2603-ITT440
# NUR AMNIE IMAN BINTI ZAHA (2024272968)
# M3CS2554B
# 📊 Parallel Text Processing Performance Analyzer

---

## 📌 PROJECT TITLE
Parallel Text Processing Performance Analyzer

---

## 📖 INTRODUCTION
This project is developed to compare the performance of different programming approaches in processing large-scale data using Python. It focuses on sequential processing, multithreading and multiprocessing techniques.

A large dataset of 4,000,000 text lines is generated and processed to measure execution time for each method. The results are then displayed in a table and visualized using a graph.

The main goal of this project is to show how parallel programming can improve performance compared to traditional sequential execution when handling big data.

---

## ❗ PROBLEM STATEMENT
Modern systems process large volumes of data and choosing the right execution method is critical for performance. Sequential processing can be slow when handling large datasets, while concurrent and parallel techniques may improve execution time.

This project aims to analyze and compare the performance of three approaches: sequential processing, multithreading and multiprocessing in Python. The system processes a large dataset (millions of text lines) and measures execution time to determine the most efficient method.


**The problem addressed is:**  
👉 Which processing method provides the best performance when handling large-scale text data?

---

## 💻 SYSTEM REQUIREMENTS
- Operating System: Windows / macOS / Linux  
- Python Version: Python 3.8 or higher  
- Recommended IDE: Visual Studio Code  
- Libraries: matplotlib (for data visualization)  
- RAM: Minimum 8GB (recommended for large dataset processing)  
- CPU: Multi-core processor (recommended for multiprocessing)

---

## ⚙️ INSTALLATION STEPS

### 1. Install Python
- Download Python from official website  
- Ensure Python is added to PATH  

### 2. Install required library
Run in terminal:
```bash
python -m pip install matplotlib
```

### 3. (Optional) Install Visual Studio Code
- Download and install Visual Studio Code
- Install Python extension

---

## ▶️ HOW TO RUN THE PROGRAM

### Step 1: Open Project
Open the project folder in Visual Studio Code


### Step 2: Open Terminal
Press:
```bash
Ctrl+
```

### Step 3: Install Required Library (First Time Only)
```bash
pip install matplotlib
```

### Step 4: Run the Program
```bash
python ptext_analyzer.py
```

---

## ⏳ PROGRAM EXECUTION FLOW

### 1. Data Generation
The program generates a large dataset:
```bash
Generating HEAVY DATA (4,000,000 lines)... Please wait.
```

### 2. Execution Methods
The system runs three processing methods:
```bash
Running Multiprocessing...
Running Threading...
Running Sequential...
```


### 3. Performance Results

The terminal will display a comparison table:

```bash
- Method               | Time (Seconds)
--------------------------------------
- Multiprocessing      | fastest
- Threading            | medium
- Sequential           | slowest
```


### 4. Graph Output

- A performance graph will appear in a pop-up window  
- The graph will also be saved automatically as:
```bash
  performance_graph.png
```

  ---

  ## 📥 SAMPLE INPUT (INSERT REAL INPUT LATER)

The system automatically generates a large dataset consisting of 4,000,000 lines of repeated text:
(insert input here)
- Wujudmu di sini di tanah anak merdeka. Bagai obor ilmu memayungi putera puterinya.
(repeated 4,000,000 times)

---

## 📤 SAMPLE OUTPUT (INSERT REAL OUTPUT)

### Terminal Output Example:
```bash
Generating HEAVY DATA (4,000,000 lines)... Please wait.
Running Multiprocessing...
Running Threading...
Running Sequential...
```

```bash
Method | Time (Seconds)
Multiprocessing | 1.23s (Fastest)
Threading | 2.45s (Middle)
Sequential | 4.89s (Slowest)
```
```bash
SUCCESS: Graph saved as 'performance_graph.png'
Displaying Graph... (Close window to finish)
```

---

## 💻 SOURCE CODE

The full source code for this project is provided in:
(INSERT FULL CODE)

It includes:
- Data generation
- Sequential processing
- Threading implementation
- Multiprocessing implementation
- Performance comparison
- Graph visualization

---

## 📌 CONCLUSION

This project successfully demonstrates the performance differences between sequential, threading, and multiprocessing approaches when handling large-scale data.

Based on the results, multiprocessing is the fastest method because it utilizes multiple CPU cores for true parallel execution. Threading provides moderate performance but is limited by Python’s Global Interpreter Lock (GIL). Sequential processing is the slowest as it executes tasks one at a time.

Overall, the project proves that parallel programming significantly improves efficiency for CPU-intensive tasks involving large datasets.

---

## 🎥 VIDEO DEMONSTRATION

👉 Insert your YouTube video link here:

