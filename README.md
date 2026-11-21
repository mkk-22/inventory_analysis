# KAVAK UAE Inventory Analysis

Analysis of publicly advertised used-car listings to compare KAVAK with other UAE dealerships, with a focus on inventory composition and pricing.

## Data

- Source: YallaMotor UAE, collected using an Apify scraper.
- Snapshot date: 18 November 2026.
- Dealerships: KAVAK, Cars24, AlbaCars, AutoCentral, and CarSwitch.
- Additional KAVAK website listings are used to compare inventory composition across platforms.

## Repository Contents

- **Datasets (in data dir):** Raw and processed listing data.
- **Jupyter notebooks (in code dir):** Data collection, cleaning, exploratory analysis, competitive pricing, inventory overlap, and Random Forest regression.
- **HTML dashboard (inventory_analysis_dashboard.html):** Interactive results and visualizations. Open the HTML file in a web browser.

## Limitations

The analysis uses public listing snapshots, not complete dealer inventories or confirmed sales. Prices are advertised asking prices, not transaction prices. Results may change as listings are updated.