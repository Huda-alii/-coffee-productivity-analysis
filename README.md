Coffee Productivity Analysis

Overview

This project explores the relationship between caffeine intake, focus level, and sleep quality using Python and data analysis techniques.

The main goal is to understand whether higher caffeine intake is associated with changes in focus and sleep quality.

Dataset

The dataset contains 500 records and 13 columns.

Key variables include:

* Caffeine intake
* Focus level
* Sleep quality
* Sleep impact
* Beverage type
* Time of day
* Age
* Gender

The values for several variables are normalized between 0 and 1.

Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

Analysis

The project examines:

1. The relationship between caffeine intake and focus level.
2. The relationship between caffeine intake and sleep quality.
3. Average focus level across Low, Medium, and High caffeine intake groups.

Key Findings

* Caffeine intake and focus level showed a moderate positive correlation (r = 0.55).
* Caffeine intake and sleep quality showed a moderate negative correlation (r = -0.37).
* Average focus level increased across caffeine intake groups:
    * Low: 0.705
    * Medium: 0.841
    * High: 0.931

These results suggest that higher caffeine intake is associated with higher focus levels but lower sleep quality in this dataset.

Limitations

The analysis is based on correlations and group comparisons, so it does not establish that caffeine directly causes changes in focus or sleep quality.

The dataset also contains normalized values, and other factors may influence focus and sleep quality that were not examined in this project.

Project Files

* Coffee Productivity Analysis.ipynb — Jupyter Notebook containing the analysis and visualizations.
* caffeine_intake_tracker.csv — Dataset used for the analysis.
