# Web Scraping and Sentiment Analysis of Testimonials

## Project Overview

This project is based on web scraping and sentiment analysis using Python. It extracts testimonials from a public webpage called **Tech for All with Priya** using the Requests and BeautifulSoup libraries.

After extracting the testimonials, sentiment analysis is performed to classify them into three categories: Positive, Negative, and Neutral. The extracted data is then processed and visualized to understand the overall sentiment distribution.

## Objectives

- Extract testimonials from a public webpage using web scraping.
- Collect and organize testimonial data.
- Perform sentiment analysis on the extracted text.
- Classify testimonials into Positive, Negative, and Neutral categories.
- Visualize the sentiment results using graphs.

## Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Requests | Fetch webpage content |
| BeautifulSoup | Extract data from HTML |
| Pandas | Data cleaning and manipulation |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |

## Project Workflow

1. **Webpage Access:** Send HTTP requests to the target webpage using Requests.
2. **HTML Parsing:** Use BeautifulSoup to parse the webpage's HTML content.
3. **Data Extraction:** Extract testimonials from the webpage.
4. **Data Processing:** Organize the extracted testimonials using Pandas.
5. **Sentiment Analysis:** Analyze the testimonial text and classify it into Positive, Negative, or Neutral.
6. **Visualization:** Display the sentiment distribution using Matplotlib and Seaborn.

## Sentiment Categories

- **Positive:** Testimonials expressing satisfaction, appreciation, or positive opinions.
- **Negative:** Testimonials expressing dissatisfaction or negative opinions.
- **Neutral:** Testimonials expressing neither clearly positive nor negative opinions.

## Tools Used

- Google Colab
- Python
  

## Project Files

- `web_scraping_using_python.ipynb` – Contains the complete Python implementation.
- `README.md` – Project documentation.
- `platform_testimonials.csv` – Extracted testimonial dataset (if available).

## Conclusion

This project provides practical experience in web scraping, data extraction, data processing, sentiment analysis, and visualization using Python. It demonstrates how publicly available textual data can be collected and analyzed to identify opinions and understand sentiment patterns.

## Author

Created as a Python Data Science project.
