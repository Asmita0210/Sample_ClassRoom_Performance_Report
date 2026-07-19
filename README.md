# Student Performance Analytics & Visualization

A Python-based data analytics tool designed to evaluate student academic metrics across multiple subjects. Utilizing `pandas`, `numpy`, and `matplotlib`, this project generates insight-driven statistical visualizations, culminating in a comprehensive, multi-panel academic performance report.

## Table of Contents
* [Features](#features)
* [Visualizations & Data Insights](#visualizations--data-insights)
* [Dataset Structure](#dataset-structure)
* [Installation & Setup](#installation-and-setup)
* [Usage](#usage)

---

## Features

* **Multi-Subject Performance Breakdown:** Computes localized class subject averages and handles distribution frequencies.
* **Comparative Student Profiling:** Tracks individual subject-to-subject trends to identify relative strengths and weaknesses.
* **Comprehensive Multi-Panel Layout:** Leverages Matplotlib's `GridSpec` to generate a production-ready dashboard aggregating line graphs, custom heatmaps, and box-and-whisker plots into a single exported report.

---

## Visualizations & Data Insights

### 1. Subject-Wise Class Average
Analyzes the overall class performance per subject against a global baseline average, color-coded based on achievement thresholds.

<img src="reports/Class Average by Subject.png" alt="Class Average by Subject" width="600"/>

### 2. Score Distribution Per Student
Individual student performance frequencies modeled across distinct metric bins to observe variance in individual marks.

<img src="reports/Score Distribution per Student.png" alt="Score Distribution Per Student" width="600"/>

### 3. Student Performance Comparison
A comparative multi-line analysis displaying student scores side-by-side with localized inline annotations marking final-subject placements.

<img src="reports/Student Performance Across Subjects.png" alt="Student Performance Across Subjects" width="600"/>

### 4. Consolidated Student Performance Report Dashboard
The complete dashboard compiling an analytical heatmap of precise score values, an overall subject profile chart, and a subject-wise score distribution box plot.

<img src="reports/Student Performance Report 2024.png" alt="Student Performance Report 2024" width="600"/>

---

## Dataset Structure

The project processes a student academic tracking framework evaluating individual marks (out of 100) across five essential technical and core disciplines:

* **Students Tracked:** Alice, Bob, Carol, Dave, Eve
* **Core Subject Areas:** Math, Science, English, History, Coding

---

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/student-performance-analytics.git](https://github.com/yourusername/student-performance-analytics.git)
   cd student-performance-analytics
