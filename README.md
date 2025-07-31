# Medical Data Visualizer

This project is part of the **freeCodeCamp Data Analysis with Python** course.  
The goal is to analyze and visualize medical examination data using **Pandas**, **Seaborn**, and **Matplotlib**.

##  Files Included
- `medical_data_visualizer.py` – main Python script with analysis and plotting functions
- `medical_examination.csv` – dataset used in the analysis
- `catplot.png` – categorical plot output
- `heatmap.png` – correlation heatmap output

##  What the Script Does
- Cleans the medical dataset
- Adds 'overweight' column based on BMI
- Normalizes 'cholesterol' and 'gluc' values
- Creates a **categorical plot** (`catplot.png`)
- Generates a **correlation heatmap** (`heatmap.png`)

##  How to Run
Make sure you have Python and the following libraries installed:
```bash
pip install pandas matplotlib seaborn
