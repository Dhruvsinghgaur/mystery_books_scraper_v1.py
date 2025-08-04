This script scrapes book data from the 'Mystery' category on the website
https://books.toscrape.com. It collects the following information for each book:

- Title
- Price
- Star rating (e.g., One, Two, Three...)

The script navigates through all available pages in the 'Mystery' section by
following pagination links, and stores the extracted information in a
Pandas DataFrame for further analysis or export.

Libraries Used:
- requests: to send HTTP requests and fetch web content
- BeautifulSoup (bs4): to parse and extract data from HTML
- pandas: to store and manipulate the scraped data

Usage:
Simply run the script. It will output the first few entries as a preview.
You can also modify it to save the data to a CSV file.
