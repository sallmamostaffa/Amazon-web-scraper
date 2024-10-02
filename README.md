# Price Analysis Web Scraper

This repository contains a Python-based web scraper that extracts product names and their prices from e-commerce websites. The scraped data is used for price analysis and tracking competitive prices for informed business decisions.

This project was developed as part of my **Data Science Internship as part of the Commercial Development team** at **Nestlé Waters Egypt**, where it was utilized to monitor competitor product pricing, helping to inform and refine our pricing strategy.

## Features
- **Web scraping**: Extract product names and prices from specified e-commerce websites.
- **Data storage**: Save scraped data in CSV format for easy analysis.
- **Price analysis**: Analyze price trends and compare with competitor prices using Jupyter Notebooks.
- **Track price changes**: Automate tracking to monitor price evolution over time.

## Project Context

As part of my internship at **Nestlé Waters Egypt**, this project was used to:
- Track the pricing of competitors' products in the water and beverages category on various e-commerce platforms.
- Automate the collection of price data to improve market insights and competitive analysis.
- Provide the marketing and commercial development teams with up-to-date pricing information to optimize pricing strategies.

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

### Scraping the Data:
- The `scraper.py` script is located in the `src/` directory. You can modify the URLs and the tags/classes to match the structure of the website you want to scrape.
- Run the script to scrape the data:
    ```bash
    python src/scraper.py
    ```

### Analyzing the Data:
- The scraped data is stored in the `data/scraped_data.csv` file.
- Use the Jupyter notebook in the `notebooks/` folder for price analysis:
    ```bash
    jupyter notebook notebooks/price_analysis.ipynb
    ```
- In the notebook, you can load the data, clean it, and visualize price trends. The cleaned data is then integrated into an interactive dashboard to facilitate easy exploration of pricing insights.

## Use Case for Nestlé Waters Egypt

This project was integral to supporting **Nestlé Waters Egypt** in staying competitive in the market. By providing real-time insights into competitor pricing, the team could:
- Identify pricing trends over time.
- Adjust their pricing to remain competitive.
- Detect changes in competitor strategies and act accordingly.

## Future Enhancements

1. **Extend to More Platforms**: Add support for scraping prices from additional e-commerce platforms beyond Amazon.
2. **Automate Data Collection**: Implement scheduling to automatically collect and analyze data at regular intervals.
3. **Advanced Analytics**: Include more advanced statistical analyses and machine learning models to forecast pricing trends and predict competitor movements.
4. **Real-Time Dashboard**: Integrate the results into a live dashboard for real-time price tracking and visualization.
