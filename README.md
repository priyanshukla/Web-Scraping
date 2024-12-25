Web Scraper Project

Overview

This is a web scraping project built using Python and Scrapy. The goal of this project is to extract data from websites and store it in a structured format for further analysis. The scraper is designed to scrape data such as book titles, authors, and prices from an e-commerce website and store it in a MongoDB database.

Features

- Scrape book data such as title, author, price, and availability from a specified website.
- Store the scraped data in a MongoDB database for easy retrieval and analysis.
- Modular, well-commented, and clean code.
- Error handling and logging for smooth execution and debugging.

Technologies Used

- Python: Programming language used for the web scraper.
- Scrapy: A web crawling and web scraping framework for Python.
- MongoDB: NoSQL database used for storing the scraped data.
- BeautifulSoup: (Optional) If used in the project for parsing HTML.
- Requests: (Optional) Used for making HTTP requests.

 Installation and Setup

Follow these steps to set up the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/Web_Scraping.git
   cd Web_Scraping
2. Set up MongoDB:

Install and configure MongoDB on your system (if not already installed).
Ensure that MongoDB is running and accessible on your machine.

3. Run the Scraper:

Navigate to the spiders folder where the Scrapy spiders are located.
Run the spider using the following command:
Scrapy Crawl Books
