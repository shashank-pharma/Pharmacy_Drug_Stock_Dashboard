# Pharmacy_Drug_Stock_Dashboard


A simple Python project for monitoring pharmacy drug inventory and identifying low-stock medicines using **Pandas**, **Seaborn**, and **Matplotlib**.

## Overview

This project simulates a pharmacy inventory system by analyzing stock levels for different drugs and generating visual insights. Medicines below their reorder level are automatically flagged as **LOW_STOCK**, making it easier to identify products that need replenishment.

---

## Features

* Convert raw inventory data into a Pandas DataFrame.
* Automatically classify drugs as **OK** or **LOW_STOCK**.
* Generate low-stock alerts.
* Export processed data to CSV format.
* Create a color-coded dashboard for quick visualization.
* Display average reorder level as a reference line.
* Save charts for reporting purposes.

---

## Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib

---

## Dataset

| Drug         | Stock | Reorder Level |
| ------------ | ----: | ------------: |
| Metformin    |   450 |           200 |
| Aspirin      |    80 |           150 |
| Insulin      |   320 |           300 |
| Atorvastatin |    50 |           100 |
| Amoxicillin  |   600 |           250 |
| Warfarin     |   120 |           200 |

---

## Workflow

1. Create a DataFrame from inventory data.
2. Compare stock levels with reorder thresholds.
3. Assign a status (**OK** or **LOW_STOCK**).
4. Print low-stock alerts.
5. Generate a dashboard using Seaborn and Matplotlib.
6. Export results to CSV.

---

## Sample Output

Low stock medicines identified:

* Aspirin
* Atorvastatin
* Warfarin

---

## Visualization

The dashboard provides:

* Green bars for adequately stocked drugs.
* Red bars for drugs below reorder level.
* Average reorder level reference line.
* Stock quantity labels above each bar.

---

## Learning Outcomes

Through this project, I explored:

* Data manipulation using Pandas.
* Conditional logic with DataFrames.
* Filtering and reporting techniques.
* Data visualization concepts.
* Exporting results to CSV files.
* Basic pharmacy inventory analytics.

---

## Project Status

This is a learning project created to strengthen my understanding of Python and data analysis. Parts of the visualization were developed with AI assistance, while the focus was on understanding the underlying logic and workflow.

---

## Future Improvements

* Read inventory data from Excel files.
* Add expiry-date monitoring.
* Generate automatic reorder recommendations.
* Create an interactive dashboard using Streamlit.
* Connect to an SQL database.
* Send low-stock email alerts.

---

## Author

**Shashank Dharmesh Jilva**

Aspiring Regulatory Affairs Professional | Learning Python for Pharma and Healthcare Analytics

---
