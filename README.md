
# NDTA631 Group Assignment
## South Africa: GDP Growth vs Employment by Economic Sector

Data Analysis and Visualisation project using two South African datasets from World Bank Open Data (Data360): annual GDP growth and employment by economic sector (1961–2017).

## Group Members
- Jodeane Kyle Bee – 202408335
- Kamogelo Angela Macena – 202424481
- Kabelo Solomon Maphalla – 202451685
- Kabelo George Sethunya – 202424816
- Raymond Thabang Mothoa – 202409842

## Repository Structure
NDTA631-Group-Assignment/
├── data/
│ ├── raw/ # Original World Bank CSV files
│ └── final_clean/ # Cleaned, merged dataset used by all notebooks
├── deliverables/
│ ├── 01_data_preparation/ # Data loading, cleaning, validation
│ ├── 02_numpy_analysis/ # NumPy statistical analysis
│ ├── 03_visualisation/ # Matplotlib charts (bar, line, pie, scatter, histogram, box plot)
│ ├── 04_database_integration/# SQLite database build and queries
│ └── 05_excel_python_analysis/ # Conditional formatting and further analysis
├── GROUP_ASSIGNMENT_combined.ipynb # All five deliverables combined into one notebook
└── README.md


## Environment Configuration

This project requires:
- Python 3.10 or later
- Jupyter Notebook

Required Python libraries:
pandas
numpy
matplotlib

(`sqlite3` and `csv` are used in Section 4 and are part of Python's standard library — no separate installation needed.)

### Installing dependencies
```bash
pip install pandas numpy matplotlib jupyter
```

## Execution Instructions

1. Clone this repository:
```bash
   git clone https://github.com/MaphallaKabelo1/NDTA631-Group-Assignment.git
   cd NDTA631-Group-Assignment
```

2. Launch Jupyter Notebook **from the repository root folder**:
```bash
   jupyter notebook
```

3. To see the full project in one place, open `GROUP_ASSIGNMENT_combined.ipynb` at the root and use "Restart Kernel and Run All Cells".

4. To view an individual deliverable, run the notebooks in this order, using "Restart Kernel and Run All Cells" in each:
   1. `deliverables/01_data_preparation/data_preparation.ipynb`
   2. `deliverables/02_numpy_analysis/numpy_analysis.ipynb`
   3. `deliverables/03_visualisation/visualisation.ipynb`
   4. `deliverables/04_database_integration/database_integration.ipynb`
   5. `deliverables/05_excel_python_analysis/Python_Excel_Analysis.ipynb`

5. Chart images are saved to `deliverables/03_visualisation/images/`, and database screenshots are in `deliverables/04_database_integration/images/`.

## Error Handling

Each notebook includes error handling (`try`/`except`) around its data-loading step.

## Report

The full written report (7–9 pages, DOCX and PDF) is submitted alongside this repository
