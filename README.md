# Task_04_Descriptive_Stats

This repository contains a modular system (Python function) for generating descriptive statistics from tabular datasets using:

-  Pure Python (no third-party libraries)
-  Pandas
-  Polars

The system supports optional grouping by one or two categorical columns, and outputs both console summaries and grouped `.csv` files for Pandas.
Use the Data Wrangler extension if using VS Code for easier and smoother CSV reading.
---

## File Structure

Task_04_Descriptive_Stats/
│
├── pure_python_stats.py 
├── pandas_stats.py 
├── polars_stats.py 
├── .gitignore 
└── README.md 

I have worked below the previous code for better understanding and streamlining the flow. But I did comment out the previous code (Hard Script).

---

##  Dataset Used

**IPEDS – American University Data**  
This dataset includes information about U.S. postsecondary institutions such as:

- Applicant/enrollment numbers
- Full-time/part-time breakdowns
- Degree levels awarded
- State/county-level info

 Dataset Source:  
[Kaggle - IPEDS American University Data](https://www.kaggle.com/datasets/sumithbhongale/american-university-data-ipeds-dataset)

 **Note**: Per project guidelines, the dataset is not included in this repository. But it can be downloaded manually from the above URL.

---

## How to Use the Modular System

Each script can be run standalone and accepts the following inputs:

- `file_path` – Path to your `.csv` dataset
- `numeric_columns` – List of columns to summarize
- `group_by` (optional) – Column or list of columns to group by
- `output_prefix` (optional) – Used to name output `.csv` files

---

## Examples

### Pure Python - pure_python_stats.py
## Pandas - pandas_stats.py
##Polars - polars_stats.py
