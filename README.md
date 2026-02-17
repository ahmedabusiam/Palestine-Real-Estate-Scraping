# Palestine Real Estate Web Scraping & Analysis 🏠🇵🇸

## Project Overview
This project aims to collect and analyze real estate data from Palestinian marketplaces. It involves automated data extraction (web scraping), data cleaning, and preparing the dataset for further analysis or machine learning models.

## Features
- **Automated Scraping:** Uses **Selenium** to navigate and extract property details (Price, Area, Location, Title, etc.).
- **Data Cleaning:** Extensive preprocessing using **Pandas** to handle missing values, normalize prices, and encode categorical data.
- **Dataset:** Includes 500+ real estate listings covering various cities like Jerusalem, Nablus, Ramallah, and Jenin.

## Tech Stack
- **Language:** Python
- **Libraries:** - `Selenium`: For web automation and scraping.
  - `Pandas`: For data manipulation and cleaning.
  - `NumPy`: For numerical operations.
  - `Scikit-learn`: For feature scaling and encoding.

## Files Structure
- `Palestine_real_estate_scraping.ipynb`: The main notebook containing scraping and cleaning logic.
- `Palestine_real_estate_scraping_output.csv`: The raw dataset extracted from the web.
- `Palestine_real_estate_scraping_output_cleaned.csv`: The final processed dataset ready for analysis.

## How to Run
1. Install dependencies: `pip install selenium pandas`
2. Ensure you have the appropriate WebDriver (e.g., ChromeDriver) installed.
3. Run the Jupyter Notebook to see the scraping process and data transformation.
