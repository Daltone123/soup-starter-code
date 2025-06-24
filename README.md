# 🕷️ Beginner Web Scraping Starter Code

This project contains the simplest possible Python example for beginners to understand how to scrape data from a website using **Requests** and **BeautifulSoup**.

---

## 🚀 What This Code Does

- Sends an HTTP request to a website
- Downloads the webpage content (HTML)
- Parses the HTML using BeautifulSoup
- Extracts and prints the page title

---

## 📦 Requirements

Make sure you have Python installed. Then install the required libraries:

```bash
pip install requests
pip install beautifulsoup4

## 📝 Explanation

| Line | What It Does |
|------|--------------|
| `import requests` | Loads the library to send HTTP requests |
| `from bs4 import BeautifulSoup` | Loads the library to parse HTML |
| `url = 'https://books.toscrape.com'` | Defines the target website |
| `response = requests.get(url)` | Sends a GET request to the website |
| `soup = BeautifulSoup(response.text, 'html.parser')` | Parses the HTML content |
| `print(soup.title.text)` | Prints the page title |



