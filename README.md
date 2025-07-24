📚 Book Scraper – Python Web Scraping Project
This project is a simple web scraper that extracts book information from the website Books to Scrape. It gathers data such as title, price, star rating, availability, and the product link for each book listed on the homepage.

🔍 What It Does
Scrapes book information from the homepage of books.toscrape.com

Extracts:

🏷️ Book Title

💲 Price

⭐ Star Rating

🔗 Product Link

📦 Availability status

Saves the collected data into a books.csv file using pandas

🖥️ Requirements
Python 3.x

Libraries:

requests

beautifulsoup4

pandas

You can install the required libraries using:

pip install requests beautifulsoup4 pandas
Check the output:

The script displays the scraped data in a table

It also saves the data to a books.csv file in the same directory

📁 Output Sample (books.csv)
Title	Price	Star_Rating	Link	Availability
A Light in the Attic	51.77	Three	https://books.toscrape.com/catalogue/a-light-in-the-attic_1000/index.html	In stock
Tipping the Velvet	53.74	One	...	In stock
...	...	...	...	...

💡 Notes
The current script only scrapes the first page (index.html) of the site.

You can extend it to loop through all pages using pagination logic.
