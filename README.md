# eBay Motors Car Image Scraper

## Introduction

This project implements a web scraper to extract car model details and download images from eBay Motors using Python. The scraping process is structured into three main steps:

1. **Scraping car model URLs** – Extracts car model names, listing URLs, and cover image URLs.
2. **Scraping all image URLs** – Extracts multiple image URLs from individual car listing pages.
3. **Downloading images** – Saves car images locally from extracted URLs.

The implementation uses **BeautifulSoup** for web scraping, and **Selenium WebDriver** is explored for handling dynamic JavaScript content.

---

## Features

- **Automated Scraping**: Extracts car listings and images efficiently.
- **CSV Data Storage**: Saves extracted data in structured CSV files.
- **Image Downloading**: Automates downloading of all available car images.
- **Expandable**: Can be modified to scrape additional car attributes.

---

## Installation

### Prerequisites

Ensure that you have Python installed along with the required libraries. Install dependencies using:

```bash
pip install requests beautifulsoup4 selenium pandas
