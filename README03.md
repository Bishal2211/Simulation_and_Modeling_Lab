# Simulation and Modeling Lab – Assignment 03  
**Course Code:** CSE 413  

**Name:** Ismam Ahmed  
**ID:** 0432220005101116  
**Section:** 7B2  
**Batch:** 53  
**Semester:** Spring 2026  

---

## Assignment Overview
This project contains the solution for **Simulation and Modeling Lab – Assignment 03**.  
The assignment focuses on simulating customer wait times using probability distributions and analyzing the results through visualization and statistical methods using Python.

---

## Problem Description
A customer service center analyzes how long customers wait before being served.

- **Regular Days:** Wait times follow a **Uniform Distribution** between **2 and 12 minutes**
- **Busy Days:** Wait times follow a **Normal Distribution**
  - Mean = 8 minutes  
  - Standard Deviation = 2 minutes  

The objective is to simulate and compare both scenarios.

---

## Tasks

### Part 1 – Data Generation
- Generate **3000 wait times** using Uniform Distribution (2–12 minutes)
- Generate **3000 wait times** using Normal Distribution (mean = 8, std = 2)
- Replace negative values in normal distribution with **0**

**Concepts Used**
- Random number generation (`numpy.random`)
- Uniform distribution
- Normal distribution
- Data preprocessing

---

### Part 2 – Visualization
- Plot histograms for both datasets
- Include:
  - Title
  - Axis labels
  - Appropriate bins
  - Grid (optional)

**Concepts Used**
- Data visualization using Matplotlib
- Distribution comparison

---

### Part 3 – Statistical Analysis
For both datasets, calculate:
- Mean  
- Median  
- Standard deviation  
- Maximum wait time  

**Concepts Used**
- Descriptive statistics using NumPy
- Simulation analysis

---

## Libraries Used
- numpy  
- matplotlib  

(Optional)  
- seaborn  
- sympy  

Install required libraries:

```bash
pip install numpy matplotlib seaborn sympy
```

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/repository-name.git
```

2. Open the project folder

3. Run the Python file:
```bash
python assignment.py
```

---

## Output

### Data Simulation
- Generated wait time datasets for regular and busy days  
- Negative values removed from normal distribution  

### Visualization
- Histogram of Uniform Distribution (Regular Days)  
- Histogram of Normal Distribution (Busy Days)  

### Statistical Results
Displays:
- Mean  
- Median  
- Standard Deviation  
- Maximum Wait Time  

---

## Learning Outcomes
- Understanding probability distributions in simulation  
- Working with NumPy for random data generation  
- Comparing uniform and normal distributions  
- Visualizing data using Matplotlib  
- Performing statistical analysis  
- Applying simulation concepts to real-life scenarios  

---

## Author
**Ismam Ahmed**  
CSE 413 – Simulation and Modeling Lab  
Spring 2026  
