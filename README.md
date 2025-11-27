# Parallel Data Processing and Modeling for U.S. Trip Analysis

This project analyzes U.S. mobility patterns using the **Trips by Distance** dataset.  
It includes **data preprocessing**, **exploratory analysis**, **travel distance insights**,  
**threshold-based comparisons**, and **parallel processing performance benchmarking**.  
Several predictive models are also implemented to study trends in travel behavior.

---

## 📊 Project Overview

This repository contains a complete workflow for analyzing national-level mobility data:

###  1. Data Loading & Inspection  
- Automatic file path resolution  
- Null value inspection  
- Column structure verification  
- Date conversion and cleanup  

###  2. National-Level Trip Analysis  
- Stay-at-home vs. not-at-home population statistics  
- Distance-based travel metrics (0–500+ miles)  
- Weighted distance calculations  
- Daily trend visualizations  

###  3. Threshold-Based Comparison  
The project identifies dates where:
- **> 10,000,000** people made **10–25 mile trips**, and  
- **> 10,000,000** people made **50–100 mile trips**  
and compares the overlap between the two sets of dates.

###  4. Parallel Processing Performance Benchmark  
Aggregation over dates is computed using:
- Sequential processing  
- Parallel processing with **10 workers**  
- Parallel processing with **20 workers**

Performance metrics include:
- Total runtime  
- Speedup  
- Efficiency  

###  5. Modeling  
Predictive models include:
- Linear Regression  
- Random Forest Regression  
with performance metrics such as:
- R²  
- RMSE  
- MAE  

###  6. Export Key Tables  
All major results are saved as CSV:
- `processing_performance.csv`  
- `model_performance.csv`  
- `home_stats.csv`  
- `distance_stats.csv`  

---

