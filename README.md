# PubMed Article Fetcher and Processor

This Python project interacts with the PubMed API to fetch article IDs, retrieve detailed metadata, filter authors based on affiliations, and save the results into a CSV file.

## Code Overview

The code is modular, with clearly defined functions:

1. **`fetch_articles(query)`**:
   - Sends a search query to PubMed and retrieves a list of PubMed article IDs.

2. **`fetch_article_details(article_ids)`**:
   - Fetches detailed metadata for the articles using their PubMed IDs.

3. **`filter_authors(authors)`**:
   - Filters authors based on specific keywords in their affiliations, such as "Pharma", "Biotech", "Inc.", or "LLC".

4. **`save_to_csv(data, filename="output.csv")`**:
   - Saves the processed data into a CSV file using pandas.

5. **Sample Data**:
   - A sample dataset is included to demonstrate the CSV export functionality.

---

