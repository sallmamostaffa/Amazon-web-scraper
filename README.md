# Price Analysis Web Scraper

This repository contains a Python-based web scraper that extracts product names and their prices from e-commerce websites. The scraped data is used for price analysis and tracking competitive prices for informed business decisions.

## Features
- **Web scraping**: Extract product names and prices from specified websites.
- **Data storage**: Save scraped data in CSV format for easy analysis.
- **Price analysis**: Analyze price trends and compare with competitor prices using Jupyter Notebooks.
- **Track price changes**: Automate tracking to see how prices evolve over time.

## Technologies Used
- **Python**: The main language used for writing the scraper.
- **BeautifulSoup**: For parsing HTML content from websites.
- **Requests**: To fetch web pages.
- **Pandas**: For data analysis and manipulation.
- **Matplotlib/Seaborn**: For visualizing price trends.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/price-analysis-scraper.git
    cd price-analysis-scraper
    ```

2. **Install dependencies**:
    Make sure you have Python 3.x installed, then install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## How to Use

1. **Scraping the Data**:
    - The `scraper.py` script is located in the `src/` directory. You can modify the URLs and the tags/classes to match the structure of the website you want to scrape.
    - Run the script to scrape the data:
      ```bash
      python src/scraper.py
      ```

2. **Analyzing the Data**:
    - The scraped data is stored in the `data/scraped_data.csv` file.
    - Use the Jupyter notebook in the `notebooks/` folder for price analysis:
      ```bash
      jupyter notebook notebooks/price_analysis.ipynb
      ```
    - In the notebook, you can load the data, clean it, and visualize price trends.
