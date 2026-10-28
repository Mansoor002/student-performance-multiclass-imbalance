##  Student Performance Multi-Class Imbalance Analysis

A data analysis and machine learning exploratory project focusing on student academic scores and demographic distributions to analyze multi-class imbalances.

##  Project Overview
This repository contains exploratory data analysis (EDA) and dataset inspection for student academic performance (`math_score`, `reading_score`, `writing_score`) alongside various demographic features like gender, parental level of education, and race/ethnicity. 

The primary objective of this project is to explore data distributions, correlation between test scores, and handle multi-class categorical imbalances.

##  Dataset Details
- **File Name:** `study_performance.csv`
- **Features Included:** 
  - `gender`
  - `race_ethnicity` (Target/Multiclass analysis category)
  - `parental_level_of_education`
  - `lunch`
  - `test_preparation_course`
  - `math_score`
  - `reading_score`
  - `writing_score`

##  Tech Stack & Libraries
- **Python**
- **Pandas** (Data Manipulation)
- **NumPy** (Numerical Computations)
- **Matplotlib & Seaborn** (Data Visualization & Heatmaps)
- **Scikit-Learn** (Model Preparation & Classification algorithms setup)

##  Exploratory Data Analysis (EDA) Highlights
1. **Statistical Summary:** Inspected shapes, data types, and descriptive statistics.
2. **Visualizations:**
   - Histograms showing individual score distributions (`math_score`, `writing_score`).
   - Scatter plots visualizing relationships between writing, reading, and math scores.
   - Correlation heatmaps highlighting score relationships.
3. **Multi-Class Categorical Analysis:** Analyzed categorical distribution across `race_ethnicity` groups to check for imbalance patterns.

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.0com/Mansoor002/student-performance-multiclass-imbalance.git
    
