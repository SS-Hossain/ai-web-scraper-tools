# AI-Powered Web Scraping & Summarization Suite

## Overview
This project is a suite of AI-powered web scraping tools that extract and summarize data from Google Search and YouTube using **SerpAPI**. The tools automate information retrieval, enhance accessibility, and generate key insights from large datasets.

## Features
- **Google Search Scraper**: Extracts top search results, including titles, links, and snippets.
- **YouTube Video Scraper**: Fetches video details such as title, channel name, views, and descriptions.
- **AI-Powered Summarization**: Uses **SerpAPI** to generate concise summaries of scraped content.

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed. You also need an API key for **SerpAPI**.

### Clone Repository
```bash
git clone https://github.com/SS-Hossain/ai-web-scraper-tools.git
cd ai-web-scraper-tools
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
### 1️⃣ Google Search Scraper
Open **google_search_scraper.ipynb** in Jupyter Notebook or Google Colab and run the cells.
- Enter your **search query** when prompted.
- Results will be saved as **google_search_results.csv**.

### 2️⃣ YouTube Video Scraper
Open **youtube_scraper.ipynb** in Jupyter Notebook or Google Colab and run the cells.
- Enter your **search query**.
- Results will be saved as **youtube_video_results.csv**.

### 3️⃣ AI-Powered Summarization
Open **ai_data_summarizer.ipynb** in Jupyter Notebook or Google Colab and run the cells.
- Enter the **CSV file path** (e.g., youtube_video_results.csv or google_search_results.csv).
- Provide your **SerpAPI key**.
- Summarized results will be saved as **summarized_data.csv**.

## API Key Setup
1. **Get a SerpAPI Key**: Sign up at [SerpAPI](https://serpapi.com/).
2. **Use your key** when prompted in the summarization notebook.

## Demo
🚀 A demo Jupyter Notebook is included (`demo.ipynb`) for testing the tools.

## Contributions
Feel free to fork and contribute! Open an issue for feature requests or bug reports.

## License
This project is licensed under the **MIT License**.
