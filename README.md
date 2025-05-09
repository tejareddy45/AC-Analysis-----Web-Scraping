# ❄️ Web Scraping and EDA: Analyzing Air Conditioners on Flipkart

## 📌 Project Overview
This project focuses on scraping air conditioner product data from Flipkart using tools like Selenium and BeautifulSoup, followed by data cleaning and exploratory data analysis (EDA). The goal is to identify the best ACs based on brand, energy efficiency, pricing, user ratings, and reviews.

## 🎯 Objective
- To build a web scraping pipeline to collect structured AC product data from Flipkart and analyze it to:

- Identify top-performing brands

- Understand how features like star rating, cooling capacity, and price affect customer satisfaction

Help consumers make informed purchasing decisions

## 🧩 Problem Statement
Customers often struggle to choose the best AC among the numerous options on Flipkart. Manually comparing brands, features, and customer feedback is inefficient. This project solves that by automating data extraction and providing analytical insights.

## 🕸️ Web Scraping Technology
To collect TV listings from Flipkart, I used:

**Python Libraries :**

***BeautifulSoup*** – Extracted structured HTML content from Flipkart product pages.

***Selenium*** – Automated page navigation and data extraction for dynamic content.

***Requests*** – Retrieved HTML content efficiently.
  

## 🛠️ Process & Methodology
📥 Data Collection <a htef = "https://github.com/tejareddy45/AC-Analysis-----Web-Scraping/blob/main/AC_DATA.ipynb">(AC_DATA.ipynb)</a>
- Used `Selenium` and `BeautifulSoup` to scrape product details from Flipkart.

- Extracted data includes: brand, cooling capacity, star rating, annual power usage, room size, warranty, price, customer ratings, and reviews.

🧹 Data Cleaning <a href = "https://github.com/tejareddy45/AC-Analysis-----Web-Scraping/blob/main/AC_EDA_CLEANING.ipynb">(AC_EDA_CLEANING.ipynb)</a>
- Converted object fields to appropriate numeric formats.

- Removed missing values, duplicates, and special characters.

- Standardized fields like price, no_of_rating, and reviews.

📊 Data Analysis <a href = "https://github.com/tejareddy45/AC-Analysis-----Web-Scraping/blob/main/AC_Analysis.ipynb">(AC_Analysis.ipynb)</a>
- Conducted descriptive and visual analysis to understand:

- Brand distribution

- Pricing trends

- Rating vs Review correlations

- Influence of features like star rating and cooling capacity on customer satisfaction

## 📂 Data Storage:
Extracted data was stored in CSV format for further processing.
**Dataset Description**
This dataset contains structured information about air conditioners listed on Flipkart, one of India's leading e-commerce platforms. The data was collected through web scraping and is used for analysis and insights on product performance, customer feedback, and pricing.
- <a href = "https://github.com/tejareddy45/AC-Analysis-----Web-Scraping/blob/main/AC_data.csv">Dataset</a>
- ***Brand Name:*** Name of the air conditioner manufacturer (e.g., LG, Samsung)
- ***Cooling_Capacity:***	The cooling capacity of the AC, usually in tons (e.g., "1.5 Ton")
- ***Star_Rating:***	Energy efficiency rating (e.g., "5 Star", "3 Star")
- ***Annual_power_usage:***	Power consumption in a year (typically in kWh/year)
- ***Room_Size:***	Recommended room size for the AC (e.g., "Up to 150 sq ft")
- ***Warranty:***	Warranty period in years
- ***Price:***	Selling price of the AC (may need conversion to numeric)
- ***Ratings:***	Average customer rating (e.g., 4.2 out of 5)
- ***no_of_rating:***	Number of customer ratings (e.g., "2,134 Ratings")
- ***Reviews:***	Number of customer reviews (e.g., "356 Reviews")

- ## 🧠 Key Insights
- 5-star rated ACs tend to receive higher average customer ratings.

- Some mid-priced brands receive better reviews than high-end ones.

- Warranty and power consumption also play a role in influencing customer decisions.

## ✅ Final Conclusion
By scraping and analyzing real Flipkart data, this project demonstrates how online reviews and product specifications can be used to evaluate air conditioners effectively. The insights help both customers and sellers in understanding product performance and consumer preferences.

## 🔮 Future Improvements
Scrape additional attributes like inverter technology, noise level, and delivery time.

Integrate review sentiment analysis using NLP.

Build an interactive Streamlit dashboard for consumer-facing product comparisons.

Store data in a structured database for scheduled updates.

