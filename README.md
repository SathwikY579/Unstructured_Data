# Unstructured_Data
Extracting data from websites and analyzing them
##Project Title
Unstructured Data Extraction and Analysis
###Description
This project involves extracting text data from a list of URLs provided in an input Excel file, performing textual analysis using spaCy, and storing the analysis results in an output Excel file.
###Features
Extract text data from URLs listed in an input Excel file.
Perform textual analysis (word count, unique words, sentence count) using spaCy.
Store the analysis results in an output Excel file.
###Installation
Install spaCy using pip install spacy.
Install the English language model using python -m spacy download en_core_web_sm.
###Usage
Prepare an input Excel file containing a list of URLs under the 'URL_ID' column.
Run the script Unstructured_Data.ipynb.
The script will extract text data from the URLs, perform textual analysis, and save the results in an output Excel file.
###Input Data
The input Excel file should contain a column named 'URL_ID' with a list of URLs to be analyzed.

###Output Data
The output Excel file will contain the analysis results, including word count, unique words, and sentence count for each URL.

###Dependencies
Python 3
spaCy
pandas
BeautifulSoup (bs4)
requests
