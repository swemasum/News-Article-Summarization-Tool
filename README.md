Introduction

This project involves the development of a News Article Summarization Tool using Python. The tool is designed to automatically scrape news articles from various websites, process the text data, and then generate concise summaries. This is particularly useful for quickly understanding the key points of news articles without reading the entire content.

Technologies Used

 1. Python: Primary programming language.

Libraries:

 1. NumPy and pandas: For data manipulation.
 2. requests: For making HTTP requests for web scraping.
 3. newspaper: For news extraction and curation.
 4. NLTK: For natural language processing tasks.
 5. pdfcrowd: For converting HTML to PDF.
 6. markdown2: For Markdown processing.

Features

 1. Web Scraping: Automated scraping of news articles based on specified search terms.
 2. Natural Language Processing: Utilizes NLTK for tokenization, stopwords handling, and other NLP tasks.
 3. Summarization Algorithm: Custom FrequencySummarizer class that computes word frequencies and generates text summaries.
 4. Search Customization: Allows users to define search terms and periods for article retrieval.
 5. Output Format Options: Summaries can be displayed in Markdown or converted to PDF format.

Implementation

 1. Setup and Configuration: Importing necessary libraries and setting up the scraping and NLP environment. (Install all from requirements.txt)
 2. FrequencySummarizer Class: Definition of a Python class for summarizing text based on word frequency analysis.
 3. News Scraping Functionality: A decorator function URL_Decorator and search_strings function for fetching news articles.
 4. Summarization Process: Application of the FrequencySummarizer to the scraped news articles to extract key insights.

Usage
 1. The tool can be used to fetch and summarize news articles from specified sources.
 2. Users can customize the search terms and the number of articles to be summarized.


Output report is given below:

![screencapture-file-C-Users-masum-NEWS-PAPER-SUMMARY-File-html-2024-01-18-23_14_37](https://github.com/swemasum/News-Article-Summarization-Tool/assets/43910072/382eaa5c-b030-46d1-83c0-2fcb8b5f54f2)

