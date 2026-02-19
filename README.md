# Data Cleaning & Outlier Visualization  
## King County Housing Sales Dataset

### Overview
This project demonstrates fundamental data cleaning, exploratory data analysis, and outlier detection techniques using the King County housing sales dataset. The analysis was completed in a Jupyter Notebook as part of a data cleaning and visualization assignment.

### Dataset
- **Name:** House Sales in King County, USA  
- **Source:** Kaggle  
- **Description:** The dataset contains information about residential home sales, including price, size, location, and construction details.

If the dataset is not included in this repository, it can be downloaded from Kaggle and placed in the same directory as the notebook.

---

### Tools & Libraries
- Python 3
- pandas
- numpy
- matplotlib

---

### Project Structure
housing-data-cleaning/
│
├── housing_data_cleaning.ipynb
├── kc_house_data.csv
└── README.md

---

### Analysis Steps
1. **Data Loading & Inspection**
   - Loaded the dataset from CSV
   - Inspected structure, size, and data types

2. **Exploratory Data Analysis**
   - Examined summary statistics
   - Checked for missing values and duplicate records

3. **Data Cleaning**
   - Removed rows with missing values
   - Converted the date column to datetime format
   - Removed duplicate records

4. **Outlier Detection & Visualization**
   - Used a box plot to visualize housing price outliers
   - Applied the IQR method to identify extreme price values
   - Retained high-priced outliers as valid luxury properties

---

### Key Findings
- The dataset contained no missing values or duplicate records.
- Housing prices are heavily right-skewed.
- Using the IQR method, 1,146 high-priced homes were identified as outliers.
- Outliers were retained to preserve realistic market behavior.

---

### How to Run
1. Clone or download this repository
2. Ensure `kc_house_data.csv` is in the same directory as the notebook
3. Open the notebook in Jupyter Lab or Jupyter Notebook
4. Run all cells from top to bottom

---

### Author
Jordan Tellekson
