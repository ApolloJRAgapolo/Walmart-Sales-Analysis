# Walmart Weekly Sales Analysis

This is an independent data analytics project where I explored historical Walmart weekly sales data using Python.

The main goal was to understand how sales changed over time, compare the performance of different stores, and check whether holiday weeks and economic factors had any relationship with sales.

## About the Dataset

The dataset contains weekly sales records from 45 stores, covering February 5, 2010 to October 26, 2012.

- **Rows:** 6,435
- **Columns:** 8
- **Stores:** 45
- **Weeks:** 143

**Dataset Source:** [Walmart Sales Dataset – Kaggle](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)

**Creator:** Mikhail (@mikhail1681)

## What I Did

- Checked the dataset for missing values and duplicates.
- Converted the date column into the correct format.
- Checked the records for each store and date.
- Investigated unusual sales values using the IQR method.
- Compared sales across the 45 stores.
- Checked weekly sales trends.
- Compared holiday and non-holiday sales.
- Looked at the relationship between sales and economic factors.
- Created charts to help understand the results.

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

Power BI was also used to create a separate four-page interactive sales dashboard.

## Some Findings

Here are some of the results from the analysis:

- Total sales reached around **$6.74 billion**.
- Average sales per store-week were around **$1.05 million**.
- Store 20 had the highest total sales, followed by Store 4.
- Average sales during holiday weeks were around **7.84% higher** than non-holiday weeks.
- Temperature, Fuel Price, CPI, and Unemployment had weak relationships with weekly sales.

## Project Files

| File | Description |
|---|---|
| `Walmart_Sales_Analysis_Cleaned_Final.ipynb` | Python notebook containing the data checks, analysis, and charts. |
| `README.md` | Project information and overview. |

## How to Run the Notebook

1. Download the notebook from this repository.
2. Open it using [Google Colab](https://colab.research.google.com/).
3. Download the dataset from the Kaggle link above.
4. Upload the CSV file to your Colab environment.
5. Make sure the file path in the notebook matches the uploaded CSV.
6. Run the notebook cells from top to bottom.

## Limitations

The dataset only contains historical weekly sales for each store. It does not include product details, customer information, profit, or inventory records.

The analysis also does not prove that holidays or economic factors caused sales to change. The results only describe the data available from 2010 to 2012.

## Disclaimer

This is an independent learning project using a public historical dataset. It was not made for Walmart and is not affiliated with or endorsed by Walmart.

The dataset is not included in this repository. Please check the original Kaggle page for its licence and reuse terms before sharing or redistributing the data.
