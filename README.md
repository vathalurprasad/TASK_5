# TASK_5
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## Files Included
- `TASK5.ipynb` - Jupyter Notebook with all analysis, cleaning, and visualization.
- `TASK 5 DA.pdf` - PDF containing task description and interview questions.
- `test.csv` - Titanic dataset used (add this to the repo if required).
- `README.md` - This file (project explanation).

---

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Steps Performed

1. **Data Loading**
   - Loaded `test.csv` using Pandas

2. **Data Inspection**
   - Used `.info()`, `.describe()`, `.isnull().sum()` to understand structure and missing values

3. **Data Cleaning**
   - Dropped the `Cabin` column due to many missing values
   - Filled missing `Age` and `Fare` values with median

4. **Exploratory Data Analysis**
   - Visualized correlations using `heatmap`
   - Plotted feature distributions using `histogram`, `boxplot`, etc. (if extended)
   - Observed patterns, trends, and anomalies

5. **Summary of Insights**
   - Correlation analysis
   - Trends based on passenger class, age, fare, and gender
   - Prepared data for potential modeling

---

## Key Visualizations
- Heatmap for correlation
- Bar plots / histograms for feature distributions
- (Add pairplot, boxplot if added in notebook)

---

## Outcome
- Understood how to clean and explore real-world data
- Identified useful trends and patterns in Titanic dataset
- Gained hands-on experience with Python data analysis libraries
