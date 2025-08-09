Here’s a `README.md` based on your `main.py` script:

---

# Startup Funding Analysis

This project analyzes a startup funding dataset to uncover trends, top sectors, cities, startups, and the distribution of investment types. The analysis includes both data processing and visualization.

## 📂 Dataset

The script expects a CSV file named `startup_funding.csv` located in `/content/`.

**Key columns used:**

* `Date dd/mm/yyyy` — Funding date
* `Amount in USD` — Funding amount
* `Industry Vertical` — Startup's sector
* `City  Location` — City of the startup
* `Startup Name` — Name of the startup
* `InvestmentnType` — Type of investment

## ⚙️ Features

1. **Data Cleaning**

   * Converts `Date dd/mm/yyyy` to datetime format.
   * Removes commas from `Amount in USD` and converts it to numeric.

2. **Analysis**

   * Monthly funding trend.
   * Top 5 industry verticals.
   * Top 5 cities.
   * Top 5 startups.
   * Investment type distribution.

3. **Visualizations**

   * **Line plot** for monthly funding trends.
   * **Bar plots** for:

     * Top sectors
     * Top cities
     * Top startups
     * Investment type distribution

## 📊 Libraries Used

* **pandas** — Data manipulation
* **matplotlib** — Plotting
* **seaborn** — Statistical data visualization

## ▶️ How to Run

1. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn
   ```
2. Place your `startup_funding.csv` in the `/content/` directory.
3. Run the script:

   ```bash
   python main.py
   ```

## 📈 Sample Output

* Funding trends over time
* Distribution of startups across sectors and cities
* Investment type patterns

---


