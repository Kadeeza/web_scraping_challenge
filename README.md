# 🔴 Mars Data Collection — Web Scraping & Analysis

![Python](https://img.shields.io/badge/Tool-Python-blue) ![BeautifulSoup](https://img.shields.io/badge/Tool-BeautifulSoup-orange) ![Splinter](https://img.shields.io/badge/Tool-Splinter-orange) ![Pandas](https://img.shields.io/badge/Tool-Pandas-blue) ![Data Collection](https://img.shields.io/badge/Skill-Web%20Scraping-red)

## 📌 Project Summary

This project demonstrates automated data collection from the web using Python scraping tools, applied to two different sources of Mars exploration data.

The two-part project covers scraping news articles and structured scientific data, then analyzing that data to extract meaningful insights — showcasing the full data pipeline from raw web content to clean, exportable analysis.

---

## 🎯 Business Objective

Many real-world datasets don't come pre-packaged in CSV files — they exist on websites and need to be collected programmatically. This project demonstrates the ability to automate data extraction, structure it, and analyze it, skills directly applicable to market research, competitive intelligence, and data journalism.

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Scripting and data processing |
| Splinter | Browser automation for web scraping |
| BeautifulSoup | HTML parsing and element extraction |
| Pandas | Structuring and analyzing scraped data |
| Matplotlib | Data visualization |
| Jupyter Notebook | Step-by-step workflow |

---

## 📊 Project Workflow

### Part 1 — Mars News Scraping (`part_1_mars_news.ipynb`)
- Used Splinter to automate browser navigation to a Mars news site
- Used BeautifulSoup to parse the HTML and extract article titles and preview text
- Stored results in a structured list of dictionaries

### Part 2 — Mars Weather Data Scraping & Analysis (`part_2_mars_weather.ipynb`)
- Scraped a table of Mars atmospheric data from a web page
- Parsed the HTML table into a Pandas DataFrame
- Converted columns to appropriate data types
- Analyzed the data to answer questions such as:
  - How many months exist on Mars?
  - How many Martian days of data are in the dataset?
  - Which months have the coldest and warmest average temperatures?
  - Which months have the lowest and highest atmospheric pressure?
  - How many Earth days are in a Martian year?
- Exported the cleaned dataset to `output_file.csv`

---

## 💼 Business Value Delivered

This project demonstrates the ability to:

✅ Automate data collection from websites using Python scraping tools  
✅ Parse and extract structured information from raw HTML  
✅ Clean, type-convert, and analyze scraped data with Pandas  
✅ Export processed data to reusable CSV files  
✅ Answer analytical questions from data gathered end-to-end  

---

## 📁 Repository Structure

```
web_scraping_challenge/
│── part_1_mars_news.ipynb       # News article scraping
│── part_2_mars_weather.ipynb    # Weather data scraping and analysis
│── output_file.csv              # Exported Mars weather dataset
│── README.md
```
