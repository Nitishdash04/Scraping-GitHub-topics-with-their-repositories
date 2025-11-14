# Scraping-GitHub-topics-with-their-repositories
GitHub Topics & Repositories Scraper

This project automates the extraction of GitHub topics, their top repositories, and each repository’s README content using web scraping techniques. It provides structured, ready-to-use data for analysis, research, or dataset creation.

🚀 Features

Scrapes all GitHub topics from the Topics page.

Fetches each topic’s top repositories (stars, owners, URLs).

Extracts each repository’s README file in clean text format.

Stores outputs in CSV/JSON for easy reuse.

Uses requests, BeautifulSoup, and pandas for efficient scraping.


🛠️ Tech Stack

Python

BeautifulSoup4

Requests

Pandas


📊 Output

topics.csv → List of GitHub topics

repositories.csv → Repositories with metadata

README text files → Clean extracted README of each repo
