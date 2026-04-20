# Web-scraping-101
Project Title:
Web Scraping 101: Extracting Book Data from BooksToScrape.com
Project Description:
This project is my Web Scraping 101 foundation project. The goal was to learn how to extract structured data from a website using Python, starting from basic inspection to building a clean dataset.
What I Did:

Inspected website structure using browser Developer Tools (Elements tab)
Used requests to fetch the webpage and BeautifulSoup to parse the HTML
Extracted key information for each book: Title, Price, Rating, and Availability
Cleaned messy data (removed currency symbols and encoding issues like Â£)
Converted data into a pandas DataFrame
Saved the final dataset into an Excel file (books_data.xlsx)

Key Learnings & Logic:

How to find the right HTML elements using class names (find() and find_all())
The importance of proper data cleaning when scraping real websites
Understanding the difference between raw HTML source and structured parsing with BeautifulSoup
Converting text data (like prices) into numeric format for analysis
Building a reusable scraping workflow from inspection → extraction → cleaning → saving

This project helped me build a strong foundation in web scraping — one of the essential skills for a Data Analyst who works with Python, especially when public APIs are not available.
Tools Used:

Python, Requests, BeautifulSoup4, Pandas
