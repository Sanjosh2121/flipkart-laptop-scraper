# 💻 Flipkart Laptop Scraper & Analyst

**A Data Science project that automates the hunt for the best value-for-money laptop.**

This tool scrapes real-time laptop data from Flipkart, cleans messy specifications using Regex, analyzes price-to-performance ratios, and identifies "hidden gem" deals that offer high specs at budget prices.

---

## 🚀 Project Overview

Buying a laptop is confusing because of thousands of messy product names. This project solves that by:
1.  **Scraping** 200+ laptops from Flipkart using `BeautifulSoup`.
2.  **Cleaning** unstructured text (e.g., "16GB DDR4 RAM", "1TB Gen4 SSD") into structured data.
3.  **Visualizing** the "Price Ladder" of different processors (i3 vs i5 vs M2).
4.  **Filtering** for the best deals (High RAM + Good CPU + Low Price).

## 📊 Key Insights (The Result)

After analyzing 240 laptops, the algorithm identified a massive market inefficiency:

> **🏆 The "Jackpot" Deal Found:**
> * **Model:** Acer Aspire 15
> * **Specs:** AMD Ryzen 5 | 16 GB RAM | 512 GB SSD
> * **Price:** ₹34,490
> * **Verdict:** This laptop is ~₹10,000 cheaper than the market average for these specifications.

## 🛠️ Tech Stack

* **Python 3.10+**
* **Web Scraping:** `BeautifulSoup4`, `Requests`
* **Data Cleaning:** `Pandas`, `Regular Expressions (Regex)`
* **Visualization:** `Matplotlib`, `Seaborn`

## ⚙️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/flipkart-laptop-scraper.git](https://github.com/YOUR_USERNAME/flipkart-laptop-scraper.git)
    cd flipkart-laptop-scraper
    ```

2.  **Install dependencies:**
    ```bash
    pip install pandas beautifulsoup4 requests matplotlib seaborn
    ```

3.  **Run the analysis:**
    Open the Jupyter Notebook (`.ipynb`) or run the script:
    ```bash
    python analysis.py
    ```

## 📈 Sample Analysis (Visualization)

*The project generates a "Price Hierarchy" chart to show the average cost of performance:*

![Average Price Chart](chart.png)

---

**Author:** [Sanjosh Khatri]
