# web-scraping-challenge

**File: part_1_mars_news**
- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
- The titles and preview text of the news articles were scraped and extracted.
- The scraped information was stored in a python data structure - "news_article_dict", which is a list of dictionaries.

**File: part_2_mars_weather**
- The HTML table was extracted into a Pandas DataFrame. Used Beautiful Soup to scrape the data.
- Ensured the columns have the correct headings and data types per the requirements.
- The data was analyzed to answer the following questions:
    - How many months exist on Mars?
    - How many Martian days' worth of data are there?
- The data was also analyzed to answer the following questions, and a data visualization was created to support each answer:
    - Which month, on average, has the lowest temperature? (Month - 3) The highest? (Month - 8)
    - Which month, on average, has the lowest atmospheric pressure? (Month - 6) The highest? (Month - 9)
    - How many terrestrial days exist in a Martian year? A visual estimate of min_temp was also plotted against the Terrestial days.
    - The DataFrame was exported into a CSV file: **File: "Mars_weather_output.csv"**
