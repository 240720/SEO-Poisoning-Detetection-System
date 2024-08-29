This project is a Django-based web application designed to detect SEO poisoning in websites by analyzing web content retrieved through Google Custom Search. The system identifies malicious patterns such as excessive keyword usage, hidden text, and URL redirects to classify sites as "Safe" or "Poisoned."

Features
Keyword Analysis: Automatically reads and processes a list of keywords from a file to detect SEO poisoning based on keyword frequency.
Google Custom Search Integration: Fetches URLs related to a search query using the Google Custom Search API.
Web Content Extraction: Scrapes website content using BeautifulSoup to analyze visible and hidden text, as well as identify redirects.
Classification Algorithm: Classifies websites based on the occurrence and frequency of poisoned keywords and other suspicious patterns.
Results Storage: Saves the classification results in a CSV file for further analysis.
User Interaction:
Home and About Views: Displays items, lists, reviews, and project details.
Feedback System: Allows users to submit and view feedback.
Menu View: Presents a search interface for users to query websites and see classification results.

Access the home page to view items, lists, and user reviews.
Use the search bar on the menu page to detect SEO poisoning by entering a search query.
View results categorized as "Safe" or "Poisoned," with detailed information on keyword frequency, hidden text, and redirects.
Submit feedback through the feedback form and review past feedback submissions.
