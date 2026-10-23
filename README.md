# Web Scraping Internship Task

## Project Overview
This project collects book information from [Books to Scrape](https://books.toscrape.com/) using Python. The data is cleaned and saved as a CSV file for further analysis.

## Objectives
- Learn the basics of web scraping
- Understand website HTML structure
- Extract useful information using Python
- Clean and organize the collected data
- Save the data in CSV format

## Tools and Libraries
- **Python**: programming language
- **Requests**: fetches webpage content
- **BeautifulSoup**: parses HTML and extracts book details
- **Pandas**: cleans, organizes, and saves the dataset
- **Google Colab**: used to write and run the code

## Data Collected
The dataset contains 1,000 books (scraped across all 50 pages).

| Column | Description |
|---|---|
| Title | Name of the book |
| Price | Price of the book (numeric) |
| Rating | Book rating |
| Availability | Availability status |
| Book_URL | Link to the book page |

## Data Cleaning
- Converted prices to numeric format
- Removed duplicate book URLs
- Removed records with missing values in key columns

**Result:** 1,000 rows and 5 columns, with no missing values or duplicates.

## How to Run
1. Install the required libraries:
```bash
   pip install requests beautifulsoup4 pandas
```
2. Run the script:
```bash
   python web_scraper.py
```
3. The dataset will be saved as `books_dataset.csv`.

## Project Files
- `web_scraper.py`: web scraping script
- `books_dataset.csv`: cleaned dataset

## Disclaimer
This project uses Books to Scrape, a practice website designed for learning web scraping.

## Author
**Maheen Saeed**




## Task 2: Exploratory Data Analysis (EDA)

### Objective
To explore and analyze the Books to Scrape dataset to identify trends, patterns, and potential data issues.

### Dataset
- Total records: 1,000 books
- Total columns: 5
- Columns: Title, Price, Rating, Availability, Book_URL

### Analysis Performed
- Explored dataset structure and data types.
- Calculated average, median, minimum, and maximum book prices.
- Analyzed book rating counts and availability.
- Created a histogram of book prices.
- Created bar charts for book ratings and average price by rating.
- Performed hypothesis testing using ANOVA.
- Checked missing values and duplicate records.

### Key Findings
- Average book price: 35.07
- Median book price: 35.98
- Minimum book price: 10.00
- Maximum book price: 59.99
- One-star books were the most common rating category, with 226 books.
- All 1,000 books were marked as in stock.
- No missing values or duplicate rows were found in the initial checks.

### Tools Used
Python, Pandas, Matplotlib, SciPy, and Google Colab.

### Notebook
See the Task 2 EDA notebook in this repository for the code, charts, and statistical results.







## Task 3: Data Visualization

### Objective
To visualize the Books to Scrape dataset using Python, Matplotlib, and Seaborn.

### Visualizations Created
- Histogram showing the distribution of book prices.
- Bar chart showing the number of books by rating.
- Bar chart comparing average book prices by rating.
- Boxplot showing the spread of book prices.

### Key Findings
These visualizations help understand book price distribution, rating patterns, and differences in average prices across rating categories.

### Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
