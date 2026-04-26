# Demand Forecasting for Optimising Inventory Management in a Supermarket Chain

## Project Overview
This project develops a demand forecasting system for a supermarket chain using historical daily sales data. The system forecasts daily product level demand for 252 products across 14 categories using the Prophet time series model and translates those forecasts into actionable inventory decision metrics including safety stock, reorder point, order quantity, and ABC classification. Results are presented through an interactive two page Power BI dashboard.

---

## Repository Contents

| File | Description |
|---|---|
| `w1961997_20211459_6DATA007C.Y_FYP_Main code.ipynb` | Main Python notebook containing the full forecasting pipeline |
| `w1961997_20211459_6DATA007C.Y_FYP_Dashboard.pbix` | Interactive Power BI dashboard file |

---

## Dataset

The full dataset is not included in this repository due to file size limitations. The dataset used in this project is the Kaggle Grocery Sales Database and can be downloaded from the link below:

📁 **Google Drive Dataset Link:** [Click Here to Download Dataset](https://drive.google.com/drive/folders/160N9aRHFl056gvkfHhppmQmN2uYXNFIS?usp=sharing)

Although the dataset consists of seven related CSV files only the following three files are required to run the project:
- `sales.csv`
- `products.csv`
- `categories.csv`

After downloading save all files in the same folder as the Python notebook.

---

## Project Pipeline

The project follows the CRISP-DM methodology and covers the following stages:

1. Data cleaning and preprocessing
2. Manual product category remapping
3. Daily demand aggregation
4. Exploratory data analysis
5. Feature engineering
6. Prophet, SARIMA, and Holt-Winters model development and comparison
7. Full scale forecasting for all 252 products
8. Inventory decision calculations
9. Power BI dashboard deployment

---

## Models Used

| Model | Purpose |
|---|---|
| Prophet | Primary forecasting model — best performing |
| SARIMA | Comparison model |
| Holt-Winters | Comparison model |

---

## Required Libraries

Run the following command to install all required libraries:

```python
pip install pandas numpy matplotlib scikit-learn prophet pmdarima statsmodels 
```

---

## How to Run

1. Download the dataset from the Google Drive link above
2. Save the dataset files in the same folder as the notebook
3. Open `w1961997_20211459_6DATA007C.Y_FYP_Main code.ipynb` in Jupyter Notebook
4. Run all cells from top to bottom
5. Output files will be saved automatically in a `pipeline_outputs` folder
6. Open `w1961997_20211459_6DATA007C.Y_FYP_Dashboard.pbix` in Power BI Desktop
7. Refresh the data connection to load the latest outputs

---

## Student Information

| | |
|---|---|
| Student Name | Abdul Rahman |
| Student ID | w1961997 / 20211459 |
| Module | 6DATA007C.Y — Final Year Project |
| Institution | University of Westminster |





