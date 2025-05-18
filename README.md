# bank-marketing-cleaning
Python project to subset, clean, and reformat the bank_marketing.csv dataset into three separate CSV files: client.csv, campaign.csv, and economics.csv.
# Bank Marketing Dataset Cleaning and Subsetting

This project processes the `bank_marketing.csv` dataset by cleaning and splitting it into three structured and tidy subsets based on column categories: **client**, **campaign**, and **economics**.

##  Objective

To clean, reformat, and store specific subsets of the dataset as individual CSV files (`client.csv`, `campaign.csv`, and `economics.csv`) according to predefined schema and data types.

## 🗂Output Files

- `client.csv` – Contains personal and demographic information of clients.
- `campaign.csv` – Contains campaign interaction and communication history.
- `economics.csv` – Contains economic indicators and financial context.

Each file is:
- Saved **without an index** column.
- Cleaned of null or irrelevant entries (as required).
- Converted to appropriate data types (e.g., int, float, category, datetime).

## 🧪 Requirements

Install the following Python libraries:

```bash
pip install pandas numpy
